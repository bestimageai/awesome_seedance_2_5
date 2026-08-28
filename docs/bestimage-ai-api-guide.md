# bestimage.ai + Seedance 2.5: Model and API Workflow Guide

[Home](../README.md) · [120 prompt recipes](../prompts/README.md) · [Advanced prompting guide](prompting-guide.md) · [15-language directory](../prompts/i18n/README.md)

The bestimage.ai team maintains this guide. bestimage.ai provides model pages that connect prompt experimentation with an API-oriented production workflow. For Seedance 2.5, choose the model by the asset you already have—not by which page sounds more advanced.

> Treat the live bestimage.ai model pages as the source of truth for limits, input fields, output behavior, pricing, and API schemas. This guide avoids hard-coding endpoints or request bodies that may change.

## Choose the right Seedance 2.5 workflow

| Starting point | Recommended model page | Best for | Your prompt must supply |
|---|---|---|---|
| An idea, script, or shot list | [Seedance 2.5 Text-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) | Concept films, social hooks, atmosphere tests, narrative scenes, previsualization | Subject, environment, timeline, camera, motion, sound, final frame |
| A required first-frame image, optionally paired with an end frame | [Seedance 2.5 Image-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) | Product ads, portraits, branded assets, illustration animation, before/after transitions | What the image locks, allowed motion, camera path, continuity, exclusions |

### Use Text-to-Video when

- visual exploration matters more than matching an existing asset;
- you need multiple art-direction options before producing a key image;
- the scene is driven by blocking, atmosphere, or a camera idea;
- you can describe every important object and continuity rule in text.

### Use Image-to-Video when

- identity, packaging, clothing, layout, or composition must remain recognizable;
- you already have approved campaign art or an ecommerce image;
- the first or final composition is part of the brief;
- review depends on comparing the output to a supplied source.

## Controls to verify on the bestimage.ai model pages

The following controls describe what to review in the live interface, not a guaranteed field list for every mode. Availability and accepted values vary. Do not translate a creative instruction into an API field without checking that mode’s current schema.

| Control | What it changes | Prompt-writing implication |
|---|---|---|
| Prompt | The creative and directing brief | Put invariants first, then the timeline, camera, audio, and exclusions |
| Translate | Converts the input prompt for model use | Preserve quoted on-screen copy, proper nouns, units, and asset labels during review |
| Optimize Prompt | Expands or restructures prompt wording | Compare with the original; make sure optimization does not invent products, claims, or shots |
| Enable Sound | Requests audio with the video | Separate dialogue, ambience, foley, and music; identify exact synchronization cues |
| Fixed camera direction | A creative instruction; only send a dedicated setting if the selected schema exposes one | Still describe subject and environment motion; avoid contradictory dolly or orbit instructions |
| Seed, if exposed | May help compare runs when supported; not a reproducibility guarantee | Keep prompt and settings unchanged while comparing one variable at a time |
| Duration | Sets the clip length | Fit the number of beats to the selected duration; reserve time for deceleration |
| Aspect ratio | A documented control for text/reference generation; first-frame composition controls image-to-video | Do not send an `aspect_ratio` field for image-to-video when its schema excludes it |
| Resolution | Selects the output size | Validate motion and continuity before spending on final-resolution iterations |
| Start / End Frame | Available in the image-to-video interface | State what each frame controls and describe the transition between them |

## Workflow A: prompt-first text-to-video

1. Pick one outcome: hook, explainer, product mood, story beat, or previs.
2. Write a one-sentence creative contract: audience, emotion, duration, and format.
3. Define the subject and environment with observable details.
4. Break the clip into two to four timed beats.
5. Give the camera one coherent path and a stopping point.
6. Add sound layers only after the visual sequence works.
7. Generate a low-risk exploration, review it, and change one variable per iteration.

```text
Create a [duration] [aspect ratio] video for [audience/use].

Subject and world: [who/what, location, time, lighting, material, palette].
00:00–00:__: [establishing beat and camera start].
00:__–00:__: [main action, performance, and physical reaction].
00:__–00:__: [turn, reveal, or payoff].
Final frame: [composition, emotion, negative space, camera stop].

Audio: [dialogue] + [ambience] + [foley] + [original music direction].
Continuity: [identity, wardrobe, object count, geography, light direction].
Avoid: [morphing, duplicates, anatomy errors, fake text, logos, watermark].
```

## Workflow B: anchor-first image-to-video

1. Confirm that every uploaded asset is original, licensed, or authorized.
2. In image-to-video, identify the required first frame and any optional end frame. Multiple independent identity, product, or environment images belong to a supported reference workflow, which also requires a video on bestimage.ai.
3. List the visual properties that must never change.
4. Describe allowed movement separately for the subject, environment, and camera.
5. Set contact, weight, inertia, occlusion, cloth, liquid, and reflection behavior where relevant.
6. End on an intentional frame that can be used in editing or as a thumbnail.

```text
Image 1 is the only [identity/product/composition] anchor. Preserve [specific invariants].
Image 2, if supplied as the end frame, defines only the approved final composition. Do not infer extra image-input slots.

Subject motion: [action, pace, gaze, hands, contact, weight].
Environmental motion: [wind, water, particles, traffic, practical light].
Camera: start at [shot/height], move [single path] at [speed], stop at [final framing].
Timeline: [timed sequence].
Audio: [layers and synchronized events].
Avoid: [reference drift, redesign, extra objects, clipping, fake text, logos, watermark].
```

## Production checklist

- Keep a record of prompt version, input assets, model page, duration, ratio, sound choice, seed, and review notes.
- Test identity and product geometry before adding elaborate effects or multi-character action.
- Check spelling and numbers frame by frame; add final typography in post when exact text is critical.
- Evaluate outputs on continuity, physical plausibility, camera logic, audio sync, and final-frame usability.
- Verify likeness permission, trademarks, music rights, location restrictions, safety claims, and local advertising rules.
- Use the live bestimage.ai pages for the current service status and API documentation; do not depend on screenshots of pre-release controls.

## Workflow C: multimodal reference generation

The [Seedance 2.5 Reference-to-Video page](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) requires **at least one reference video**. Images and audio are optional supporting inputs; neither replaces the required video. The prompt libraries' `Image 1`, `Video 1`, and `Audio 1` labels describe roles and upload order, not undocumented API fields.

1. Supply an authorized video that demonstrates the required motion, camera path, or timing.
2. Name what to borrow and what not to borrow from each reference. A motion reference must not silently override identity or product geometry.
3. If using the documented AT-reference notation, map each label to its actual array entry: `<<<image_1>>>` to `images[0]`, `<<<video_1>>>` to `videos[0]`, and `<<<audio_1>>>` to `audios[0]`. Check the current service documentation before applying this syntax; do not send labels for missing media.
4. Separate a four-panel board into four individual images before assigning four roles. A single board upload is one input, not four automatically addressable images.
5. Review timing, sound, identity, and geometry in the actual result. None of the reference videos or recordings mentioned by the briefs are bundled here.

## Prepare static references with GPT Image 2

[GPT Image 2 API on bestimage.ai](https://bestimage.ai/models/openai/gpt-image-2/) is a **separate image-generation workflow**. Use it to prepare a concept frame, an original character sheet, or a storyboard before choosing a Seedance video mode. Do not send a video timeline to it and describe the result as a generated video.

Write an image brief around subject, materials, composition, lighting, and invariants. Review anatomy, text, product geometry, likeness permissions, and brand rights before using the image. For a matching end frame, verify that the camera and object layout are compatible with the first frame.

## Generation is not the same operation as editing or extension

The [official Seedance 2.5 overview](https://seed.bytedance.com/en/seedance2_5) describes audiovisual generation, reference control, editing, and extensions. The [official launch article](https://seed.bytedance.com/en/blog/one-take-creation-flexible-referencing-introducing-seedance-2-5) further discusses timestamp-directed editing, green-screen workflows, and clay-render references.

This guide covers bestimage.ai text-to-video, image-to-video, and reference-to-video workflows. Editing and extension briefs require a service that explicitly exposes those operations. A last-frame image followed by a new generation is not automatically a source-video extension; a complete regeneration is not a local edit.

## API access and request requirements

Use `https://api.flaq.ai` as the API base URL for bestimage.ai. Authenticate with an API key issued through your bestimage.ai account and keep credentials outside public files.

When integrating, check the current documentation for the exact mode identifier, authentication, required media, duration and resolution limits, submission response, task-status values, polling interval, terminal success/failure handling, timeout, and output URL lifetime. Do not add undocumented edit/extension fields or hard-code pricing from another service.

| Purpose | Link language | Model page |
| --- | --- | --- |
| Seedance 2.5 text generation | English | [Text-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) |
| Seedance 2.5 first/end-frame generation | English | [Image-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) |
| Seedance 2.5 video-required reference generation | English | [Reference-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) |
| GPT Image 2 static reference preparation | English | [GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) |

All localized README files use these English landing pages and identify their language.

## Continue exploring

- [Seedance 2.5 Text-to-Video on bestimage.ai](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/)
- [Seedance 2.5 Image-to-Video on bestimage.ai](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/)
- [120-prompt finder](../prompts/README.md)
- [Prompt engineering and troubleshooting](prompting-guide.md)
- [Originality and asset notes](../assets/IMAGE_PROMPTS.md)

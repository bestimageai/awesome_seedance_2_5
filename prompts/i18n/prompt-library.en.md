# Seedance 2.5: six shared English prompt recipes

[All languages](README.md) · [120-scene index](../README.md) · [Home](../../README.md)

Maintained by the **bestimage.ai team**. These six localized recipes correspond to main-catalog scenes 04, 31, 37, 43, 46, and 52. They are translations/adaptations of the same scenarios, not six additional unique prompts. They do not constitute a complete English translation of the Chinese catalog. Creative briefs are untested; exact geometry, text, speech, and physics must be reviewed in actual outputs.

For a single first frame, use [Seedance 2.5 Image-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/). For multiple reference assets, [Reference-to-Video](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) also requires a reference video: assign its role explicitly. [GPT Image 2 API](https://bestimage.ai/models/openai/gpt-image-2/) is a separate image-generation workflow for preparing storyboard frames, not a video endpoint. Read the [integration guide](../../docs/bestimage-ai-api-guide.md).

## I18N-01. Ceramic coffee dripper: one controlled pour

Catalog scene: **04** · Mode: image-to-video · Duration: **20 seconds** · Format: **16:9**

```text
Use Image 1 as the first frame: one cobalt-blue ceramic dripper with six exterior ribs, one white paper filter containing dry grounds, and one clear server on pale limestone. Lock the rib count, handle-free silhouette, filter folds, server outline, and left-side morning light. The product is unbranded.

00:00–00:04: hold a close view of the dry grounds; a stainless gooseneck spout enters from the upper right without hiding the dripper.
00:04–00:11: one thin continuous stream traces a small circle inside the filter. The grounds swell gently; liquid stays below the paper rim and drips into the server.
00:11–00:16: the stream stops and the spout withdraws. Pull back a little to reveal the server filling gradually; do not turn the dripper or change its proportions.
00:16–00:20: hold the product in a clean three-quarter view with empty space on the right for later copy.

Audio: soft pouring, sparse dripping, quiet room tone; no speech or music. Preserve liquid volume continuity and solid contact. No floating coffee, extra vessels, readable text, logos, steam clouds, or watermark. Change the ceramic color only when supplying a matching new first frame.
```

## I18N-02. Reversible overshirt: wind and fabric test

Catalog scene: **31** · Mode: reference-to-video · Duration: **20 seconds** · Format: **9:16**

```text
Image 1 defines the authorized adult model's identity. Image 2 defines an unbranded rust-colored overshirt, ivory lining, two patch pockets, and five front buttons. Video 1 supplies only the slow quarter-turn and the left-to-right airflow; do not copy its person or clothing. Begin with the overshirt open and the model standing on a marked studio position.

00:00–00:05: fixed medium full shot; the model raises the open left hem just enough to show the lining, with the hand visibly gripping fabric.
00:05–00:12: the model releases the hem and turns one quarter toward camera-left. A gentle fan moves the loose hem and hair consistently toward camera-right; shoulders and pocket seams stay stable.
00:12–00:16: airflow fades. Cloth settles with weight rather than snapping into place.
00:16–00:20: hold a relaxed side pose, keeping the same camera height and lens.

Audio: quiet fan and cloth movement; no dialogue. No on-body garment reversal, instant outfit swap, extra buttons, skin retouching, body reshaping, text, logos, or watermark. This illustrates fabric motion, not a certified wind-resistance test.
```

## I18N-03. Reading app: save one highlighted passage

Catalog scene: **37** · Mode: reference-to-video · Duration: **18 seconds** · Format: **16:9**

```text
Image 1 is the approved reading screen, Image 2 the same screen with one selected passage, and Image 3 the approved saved-note state. All visible copy is already supplied in English. Video 1 controls only the cursor path and click timing. Preserve the device bezel, typography, line breaks, reading position, and interface reading direction; never invent article text.

00:00–00:04: locked front view of the device on a neutral desk; the pointer pauses beside the passage shown in Image 2.
00:04–00:09: the pointer selects that passage once, following Video 1. Match the approved highlight exactly without shifting other lines.
00:09–00:14: click the existing save control once and transition to Image 3. Do not add a toast, counter, rating, or menu that is absent from the references.
00:14–00:18: hold the saved-note state for inspection. No camera move or screen reflections over the text.

Audio: one quiet click per visible click; no speech, typing, or music. Reject altered letters, mirrored controls, wandering highlights, duplicate pointers, logos, or watermark. For localization, supply all three approved screens in the target language; do not ask the video model to translate the screen.
```

## I18N-04. Snowmelt: surface runoff and infiltration

Catalog scene: **43** · Mode: reference-to-video · Duration: **24 seconds** · Format: **16:9**

```text
Image 1 is an educator-approved cutaway of a sloping soil bed, a thin snow layer, and a clear collection tray at the lower edge. Image 2 supplies the approved arrow overlay without words or numbers. Video 1 provides only the fixed-camera demonstration timing. Keep layer boundaries and tray dimensions constant; this is a simplified teaching illustration, not measured experimental evidence.

00:00–00:06: establish the entire cutaway with a locked camera. Show a small amount of meltwater forming at the snow-soil boundary.
00:06–00:13: let part of the water move downhill along the surface toward the tray; follow Image 2's surface arrows without increasing the snow mass.
00:13–00:19: show another portion entering the upper soil pores, following the approved downward arrows. Do not make it instantly cross every layer or imply all soils behave identically.
00:19–00:24: hold both pathways together in the same view; arrows stop moving before the end.

Audio: subdued water and room tone; no narration or music. No fabricated measurements, floods, disappearing soil, contradictory flow directions, labels, logos, or watermark. Add reviewed explanatory captions in post-production.
```

## I18N-05. Courtyard home: show the actual route

Catalog scene: **46** · Mode: reference-to-video · Duration: **24 seconds** · Format: **16:9**

```text
Image 1 supplies the approved ground-floor plan of a narrow courtyard home. Images 2 and 3 establish the entry room and courtyard exactly as furnished. Video 1 is an authorized walkthrough and controls the route and camera height. Treat the plan as a spatial constraint, not an image to display. No invented upstairs views.

00:00–00:06: start just inside the entrance at ordinary adult eye level with a natural perspective; show the existing bench and courtyard doorway together.
00:06–00:14: walk slowly along the route in Video 1, keeping the doorway in sight. Pause before the threshold; the camera must not cross walls, furniture, or closed glass.
00:14–00:20: enter the courtyard through the real opening and pan gently toward the original planting bed.
00:20–00:24: stop and look back so viewers can understand the connection to the entry room.

Audio: footsteps change from interior flooring to courtyard paving, with quiet outdoor ambience; no narration. Preserve door widths, floor levels, furniture count, sunlight direction, and travel distance. No ultra-wide stretching, added rooms, luxury upgrades, location claims, readable signs, or watermark.
```

## I18N-06. Cat carrier: a voluntary first visit

Catalog scene: **52** · Mode: reference-to-video · Duration: **18 seconds** · Format: **9:16**

```text
Image 1 defines one authorized adult gray tabby cat. Image 2 defines one open soft-sided carrier with a navy shell, mesh side panel, and folded-down front door. Video 1 provides only the calm approach and entry movement. Keep coat markings, body size, carrier seams, door opening, and mesh pattern consistent.

00:00–00:05: locked low camera at the carrier entrance. The cat approaches an empty open carrier, pauses, and sniffs the edge; no person pushes or restrains it.
00:05–00:11: the cat steps inside voluntarily, front paws then hind paws, with visible floor contact. The carrier does not expand or swallow the cat through its side wall.
00:11–00:15: the cat turns once inside the available space and settles facing the open entrance.
00:15–00:18: hold the relaxed pose. Leave the door completely open.

Audio: soft paw contact, fabric movement, quiet room tone; no added purring or distress sounds. No sedation, forced handling, impossible anatomy, duplicate animal, safety certification, text, logos, or watermark. If the reference cat does not enter willingly, choose a different authorized clip rather than scripting force.
```

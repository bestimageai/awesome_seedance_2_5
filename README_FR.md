# Prompts Seedance 2.5 : guide français

[English](README.md) · [简体中文](README_ZH.md) · [日本語](README_JA.md) · [Español](README_ES.md) · [Les 15 langues](prompts/i18n/README.md)

Cette collection, **rassemblée et maintenue par l'équipe bestimage.ai**, réunit **120 scénarios distincts** : les 100 scénarios d'origine ont été réécrits et 20 nouveaux ont été ajoutés. Le socle comprend **60 scènes en chinois et 40 en anglais** ; les **20 nouvelles scènes sont disponibles chacune en chinois et en anglais**. Les 15 versions linguistiques proposent six exemples communs chacune, pas une traduction intégrale du catalogue. Les traductions ne sont pas comptées comme des scénarios supplémentaires.

Partagez un prompt original et testé en suivant les [consignes de contribution](CONTRIBUTING.md), avec les réglages, les entrées et le résultat réel. Les propositions retenues peuvent être publiées avec attribution après vérification.

## Commencer rapidement

- Copiez les [6 prompts complets en français](prompts/i18n/prompt-library.fr.md).
- Parcourez l'[index des 120 scènes](prompts/README.md).
- Découvrez les 20 nouveaux processus de production en [anglais](prompts/production-workflows.en.md) ou en [chinois](prompts/production-workflows.zh.md).
- Consultez le [guide avancé de prompting](docs/prompting-guide.md) pour le cadrage, le mouvement, le son et la continuité.
- Sur bestimage.ai, choisissez [Seedance 2.5 texte vers vidéo](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) pour une consigne textuelle, [image vers vidéo](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) pour une image de départ ou [références vers vidéo](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) pour des ressources de référence. **Ces trois pages sont en anglais. Le mode références vers vidéo exige au moins une vidéo de référence**, dont le rôle doit être défini explicitement.
- Préparez des images de référence statiques ou des images de storyboard avec l'[API GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) (**page en anglais**). Il s'agit d'un processus distinct de génération d'images, pas d'une fonction vidéo de Seedance.
- Consultez le [guide d'intégration de l'API bestimage.ai](docs/bestimage-ai-api-guide.md).

> Les paramètres, tarifs, entrées et schémas API peuvent évoluer. Consultez les pages bestimage.ai pour obtenir les informations actuelles. Les visuels conceptuels ne sont pas des sorties Seedance et ne démontrent pas les performances du modèle.

## Structure recommandée

```text
[Objectif] audience, usage, durée, format
[Références] rôle unique de chaque image ou vidéo
[Invariants] identité, produit, décor et éclairage à préserver
[Chronologie] mise en place → action → révélation → plan final
[Caméra] cadrage, hauteur, trajectoire, vitesse, mise au point, arrêt
[Son] dialogue, ambiance, bruitage, musique et synchronisation
[À éviter] dérive, doublons, erreurs anatomiques, texte inventé, logos, filigranes
```

Les briefs créatifs doivent être vérifiés dans les résultats réels, notamment la géométrie, le texte, la parole et la physique. Vérifiez les consentements, les droits sur les images et la musique, les marques, les lieux, les affirmations et les règles de la plateforme avant tout usage commercial.

## À propos de bestimage.ai

L’équipe [bestimage.ai](https://bestimage.ai/) sélectionne et maintient cette bibliothèque de prompts, qui relie les pratiques de création aux API de modèles d’image et de vidéo.

## Gagnez des commissions avec bestimage.ai

Vous publiez des tutoriels, des prompts ou des intégrations d’API ? Rejoignez le [programme d’affiliation bestimage.ai](https://bestimage.ai/affiliate-program/) et recevez des commissions en recommandant bestimage.ai à votre public.

- **20 %** sur la première commande payante admissible d’un utilisateur parrainé.
- **10 %** sur ses commandes payantes admissibles suivantes, effectuées dans les **60 jours après son inscription**.

L’admissibilité des commandes et les versements sont régis par l’[accord d’affiliation en vigueur](https://bestimage.ai/affiliate-agreement/).

## Licence

[MIT](LICENSE).

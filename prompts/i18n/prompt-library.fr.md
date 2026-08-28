# Seedance 2.5 : six recettes de prompts communes en français

[Toutes les langues](README.md) · [Index des 120 scènes](../README.md) · [Accueil](../../README.md)

Maintenu par **l'équipe bestimage.ai**. Ces six recettes localisées correspondent aux scènes 04, 31, 37, 43, 46 et 52 du catalogue principal. Ce sont des traductions ou adaptations des mêmes scénarios, et non six prompts distincts supplémentaires. Elles ne constituent pas une traduction française complète du catalogue chinois. Ces briefs créatifs n'ont pas été testés ; la géométrie précise, le texte, la parole et la physique doivent être vérifiés dans les résultats réels.

Pour une seule image de départ, utilisez [Seedance 2.5 image vers vidéo](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) (page en anglais). Avec plusieurs ressources de référence, le mode [références vers vidéo](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) (page en anglais) exige également une vidéo de référence : attribuez-lui un rôle explicite. L'[API GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) (page en anglais) est un processus distinct de génération d'images pour préparer les images d'un storyboard, et non un point de terminaison vidéo. Consultez le [guide d'intégration](../../docs/bestimage-ai-api-guide.md).

## I18N-01. Porte-filtre à café en céramique : un versement contrôlé

Scène du catalogue : **04** · Mode : image vers vidéo · Durée : **20 secondes** · Format : **16:9**

```text
Utilisez Image 1 comme première image : un porte-filtre en céramique bleu cobalt avec six nervures extérieures, un filtre en papier blanc contenant du café moulu sec et une carafe transparente sur du calcaire clair. Conservez le nombre de nervures, la silhouette sans anse, les plis du filtre, le contour de la carafe et la lumière matinale venant de gauche. Le produit ne porte aucune marque.

00:00–00:04 : maintenez un gros plan sur le café moulu sec ; un bec verseur en col de cygne en acier inoxydable entre par le coin supérieur droit sans masquer le porte-filtre.
00:04–00:11 : un mince filet continu décrit un petit cercle à l'intérieur du filtre. Le café gonfle légèrement ; le liquide reste sous le bord du papier et s'écoule goutte à goutte dans la carafe.
00:11–00:16 : le filet s'arrête et le bec se retire. Reculez légèrement pour montrer la carafe qui se remplit progressivement ; ne faites pas tourner le porte-filtre et n'en modifiez pas les proportions.
00:16–00:20 : maintenez une vue de trois quarts nette du produit avec un espace libre à droite pour un texte ajouté ultérieurement.

Son : versement doux, quelques gouttes, ambiance calme de la pièce ; ni parole ni musique. Préservez la continuité du volume de liquide et le contact entre les objets solides. Pas de café en lévitation, de récipients supplémentaires, de texte lisible, de logos, de nuages de vapeur ni de filigrane. Ne changez la couleur de la céramique que si vous fournissez une nouvelle image de départ correspondante.
```

## I18N-02. Surchemise réversible : vent et mouvement du tissu

Scène du catalogue : **31** · Mode : références vers vidéo · Durée : **20 secondes** · Format : **9:16**

```text
Image 1 définit l'identité du modèle adulte dont l'utilisation de l'image est autorisée. Image 2 définit une surchemise sans marque couleur rouille, une doublure ivoire, deux poches plaquées et cinq boutons sur le devant. Video 1 fournit uniquement le lent quart de tour et le flux d'air de gauche à droite ; ne reproduisez ni la personne ni ses vêtements. Commencez avec la surchemise ouverte et le modèle debout à un emplacement marqué dans le studio.

00:00–00:05 : plan moyen fixe ; le modèle soulève le pan gauche ouvert juste assez pour montrer la doublure, la main tenant visiblement le tissu.
00:05–00:12 : le modèle relâche le pan et effectue un quart de tour vers la gauche du cadre. Un ventilateur doux déplace régulièrement le pan libre et les cheveux vers la droite du cadre ; les épaules et les coutures des poches restent stables.
00:12–00:16 : le flux d'air diminue. Le tissu retombe sous son poids au lieu de reprendre brusquement sa place.
00:16–00:20 : maintenez une pose de profil détendue, avec la même hauteur de caméra et le même objectif.

Son : ventilateur discret et mouvement du tissu ; aucun dialogue. Pas de retournement du vêtement sur le corps, de changement instantané de tenue, de boutons supplémentaires, de retouche de peau, de remodelage du corps, de texte, de logos ni de filigrane. Cette scène illustre le mouvement du tissu, pas un essai certifié de résistance au vent.
```

## I18N-03. Application de lecture : enregistrer un passage surligné

Scène du catalogue : **37** · Mode : références vers vidéo · Durée : **18 secondes** · Format : **16:9**

```text
Image 1 est l'écran de lecture approuvé, Image 2 le même écran avec un passage sélectionné et Image 3 l'état approuvé de la note enregistrée. Tous les textes visibles sont déjà fournis en anglais. Video 1 contrôle uniquement le trajet du pointeur et le moment des clics. Préservez le cadre de l'appareil, la typographie, les sauts de ligne, la position de lecture et le sens de lecture de l'interface ; n'inventez jamais le texte de l'article.

00:00–00:04 : vue frontale fixe de l'appareil sur un bureau neutre ; le pointeur s'arrête à côté du passage montré dans Image 2.
00:04–00:09 : le pointeur sélectionne ce passage une seule fois, en suivant Video 1. Reproduisez exactement le surlignage approuvé sans déplacer les autres lignes.
00:09–00:14 : cliquez une fois sur la commande d'enregistrement existante et passez à Image 3. N'ajoutez aucune notification temporaire, aucun compteur, aucune évaluation ni aucun menu absent des références.
00:14–00:18 : maintenez l'état de la note enregistrée pour permettre son inspection. Aucun mouvement de caméra ni reflet sur l'écran masquant le texte.

Son : un clic discret par clic visible ; ni parole, ni frappe au clavier, ni musique. Rejetez les lettres modifiées, les commandes inversées, les surlignages qui dérivent, les pointeurs en double, les logos et les filigranes. Pour une localisation, fournissez les trois écrans approuvés dans la langue cible ; ne demandez pas au modèle vidéo de traduire l'écran.
```

## I18N-04. Fonte des neiges : ruissellement et infiltration

Scène du catalogue : **43** · Mode : références vers vidéo · Durée : **24 secondes** · Format : **16:9**

```text
Image 1 est une vue en coupe approuvée par un enseignant, représentant un lit de terre incliné, une mince couche de neige et un bac de récupération transparent en contrebas. Image 2 fournit la superposition de flèches approuvée, sans mots ni chiffres. Video 1 fournit uniquement le rythme de la démonstration avec caméra fixe. Conservez les limites des couches et les dimensions du bac ; il s'agit d'une illustration pédagogique simplifiée, pas de preuves expérimentales issues de mesures.

00:00–00:06 : présentez l'ensemble de la coupe avec une caméra fixe. Montrez une petite quantité d'eau de fonte qui se forme à la limite entre neige et sol.
00:06–00:13 : laissez une partie de l'eau descendre en surface vers le bac ; suivez les flèches de surface d'Image 2 sans augmenter la masse de neige.
00:13–00:19 : montrez une autre partie pénétrant dans les pores supérieurs du sol, selon les flèches descendantes approuvées. Ne lui faites pas traverser instantanément toutes les couches et ne suggérez pas que tous les sols se comportent de manière identique.
00:19–00:24 : maintenez les deux parcours ensemble dans la même vue ; les flèches cessent de bouger avant la fin.

Son : eau discrète et ambiance de la pièce ; ni narration ni musique. Pas de mesures inventées, d'inondations, de sol qui disparaît, de directions d'écoulement contradictoires, d'étiquettes, de logos ni de filigrane. Ajoutez des légendes explicatives vérifiées en postproduction.
```

## I18N-05. Maison à cour : montrer le véritable parcours

Scène du catalogue : **46** · Mode : références vers vidéo · Durée : **24 secondes** · Format : **16:9**

```text
Image 1 fournit le plan approuvé du rez-de-chaussée d'une maison étroite à cour. Image 2 et Image 3 établissent la pièce d'entrée et la cour avec leur ameublement exact. Video 1 est une visite filmée dont l'utilisation est autorisée ; elle contrôle le trajet et la hauteur de la caméra. Traitez le plan comme une contrainte spatiale, pas comme une image à afficher. Aucune vue inventée à l'étage.

00:00–00:06 : commencez juste à l'intérieur de l'entrée, à hauteur habituelle des yeux d'un adulte, avec une perspective naturelle ; montrez ensemble le banc existant et l'ouverture vers la cour.
00:06–00:14 : avancez lentement sur le trajet de Video 1 en gardant l'ouverture en vue. Arrêtez-vous avant le seuil ; la caméra ne doit traverser ni murs, ni meubles, ni vitrage fermé.
00:14–00:20 : entrez dans la cour par l'ouverture réelle et effectuez un léger panoramique vers le massif de plantes d'origine.
00:20–00:24 : arrêtez-vous et regardez en arrière afin que le public comprenne la liaison avec la pièce d'entrée.

Son : les pas passent du revêtement intérieur au dallage de la cour, avec une ambiance extérieure calme ; aucune narration. Préservez les largeurs de portes, les niveaux des sols, le nombre de meubles, la direction du soleil et la distance parcourue. Pas d'étirement dû à un très grand-angle, de pièces ajoutées, d'améliorations luxueuses, d'affirmations sur l'emplacement, de panneaux lisibles ni de filigrane.
```

## I18N-06. Sac de transport pour chat : une première visite volontaire

Scène du catalogue : **52** · Mode : références vers vidéo · Durée : **18 secondes** · Format : **9:16**

```text
Image 1 définit un chat adulte gris tigré dont les images sont autorisées à l'utilisation. Image 2 définit un sac de transport souple ouvert, à enveloppe bleu marine, panneau latéral en maille et porte avant rabattue vers le bas. Video 1 fournit uniquement l'approche calme et le mouvement d'entrée. Conservez les marques du pelage, la taille du corps, les coutures du sac, l'ouverture de la porte et le motif de la maille.

00:00–00:05 : caméra basse fixe devant l'entrée du sac. Le chat s'approche du sac vide et ouvert, s'arrête et renifle le bord ; personne ne le pousse ni ne le retient.
00:05–00:11 : le chat entre volontairement, pattes avant puis pattes arrière, avec un contact visible au sol. Le sac ne s'agrandit pas et n'absorbe pas le chat à travers sa paroi latérale.
00:11–00:15 : le chat se retourne une fois dans l'espace disponible et s'installe face à l'entrée ouverte.
00:15–00:18 : maintenez la posture détendue. Laissez la porte complètement ouverte.

Son : contact léger des pattes, mouvement du tissu, ambiance calme de la pièce ; n'ajoutez ni ronronnements ni cris de détresse. Pas de sédation, de manipulation forcée, d'anatomie impossible, d'animal en double, de certification de sécurité, de texte, de logos ni de filigrane. Si le chat de référence n'entre pas de son plein gré, choisissez un autre clip autorisé au lieu de prévoir un passage en force.
```

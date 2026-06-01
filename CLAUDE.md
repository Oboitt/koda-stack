# Creative DNA — Fokkus

> Ce fichier est l'empreinte creative de Fokkus. Chaque skill CSTACK le lit avant de creer quoi que ce soit.

## Voice

- **Tone**: Direct sans etre froid. Sportif, jamais clinique. Exigeant sans etre elitiste. Bienveillant sans etre complaisant. Factuel, pas emotionnel.
- **Language**: Bilingue FR/EN. FR = tutoiement systematique. EN = "you", plus compact.
- **Signature phrases**: "Ton corps s'entraine. Ton mental aussi.", "Le mental, ca s'entraine.", "Comme tout le reste."
- **Never say**: "bien-etre", "serenite", "harmonie", "zenitude", "communaute", "ensemble", "tribu", "famille", "revolutionnaire", "unique", "le meilleur", "amateur" (on dit "sportif"), "game-changing", "unleash". Zero emoji. Zero citation inspirante. Zero superlatif. Zero vouvoiement (sauf B2B).

## Visual Identity

- **Primary colors**: Terracotta #c65d3b, Creme #faf8f5, Noir #1a1a1a
- **Forbidden colors**: Bleu, teal, violet, vert vif (= bien-etre generique)
- **Style**: Epure, professionnel, sportif. Beaucoup d'espace. Photos authentiques (sueur, pas lifestyle). Tons chauds terreux.
- **Lighting**: Naturelle, contrastee. Lumiere de terrain de sport. Pas de studio doux. Le warm doit rester naturel, pas pousse (sinon ca fait IA).
- **Composition**: Espace genereux, une idee par ecran. Chaque element a une raison d'etre.
- **Typography**: Inter exclusivement. Titres 600-700, corps 400, labels 600 uppercase spacing 0.1em.

## Photo Modes (3 modes hierarchises)

- **Warm (60%)** : Mode dominant. Couleur naturelle tiree vers les tons chauds : terracotta, dore, ambre. Saturation contenue, jamais saturee. Grain opacity 0.3. Reference : Kodachrome 64. CSS : grayscale(0%) contrast(1.1) brightness(0.4) saturate(0.8) sepia(6%). ATTENTION : rester naturel, ne pas pousser trop sinon ca fait IA.
- **Muted (25%)** : Mode de transition. Desaturation legere, tons terreux, chaleur contenue. Grain opacity 0.3. CSS : grayscale(20%) contrast(1.08) brightness(0.42) sepia(10%). Pour plans larges, ambiances, moments de calme.
- **N&B (15%)** : Mode de ponctuation. Noir et blanc pur, contraste eleve. Grain opacity 0.5. Reserve aux moments d'intensite dramatique : un regard, un geste technique, un detail d'equipement. L'exception qui cree le contraste.

**Constantes** : Grain TOUJOURS. Contraste releve. Tons chauds (cuivre, argile, sable). Jamais de tons froids.

**Prompts OpenAI GPT Image 2** : Toujours inclure "Kodachrome 64 film, natural warm tones, fine grain, rich reds, natural light" — JAMAIS "oversaturated", "vivid colors", "HDR", "cinematic color grading" (ca fait IA).

## Content Format

- **Platforms**: Instagram Reels, TikTok, LinkedIn (texte)
- **Duration**: 15-45 secondes (TikTok/Reels), max 60s si exceptionnel
- **Structure**: Accroche choc (1.5s) → Probleme reconnaissable → Solution concrete → CTA simple
- **Aspect ratio**: 9:16 (video), carre ou 4:5 (carrousels Instagram)
- **Video format**: Avatar anime (OpenAI GPT Image 2 + SadTalker) OU voix off + texte kinetic + visuels. Jamais de face camera reelle.

## Tools

- **Image generation (photos realistes)**: OpenAI GPT Image 2 via fal.ai. Defaut pour tout visuel photorealiste. Commande : `python3 tools/flux2.py --cloud fal --model openai/gpt-image-2`
- **Image generation (backgrounds, abstraits)**: FLUX.2 Klein via Modal. Reserve aux visuels non-photorealistes. Commande : `python3 tools/flux2.py --cloud modal`
- **Video generation**: Kling 3.0 Pro via fal.ai (image-to-video, keyframe-to-keyframe, UGC avatars). Commande : `python3 tools/kling.py --start frame.jpg --prompt "..." --aspect 9:16`. SadTalker (lip-sync fallback), LTX-2 (b-roll), Remotion (montage final)
- **Voiceover**: ElevenLabs V3 uniquement pour Fokkus (jamais Qwen3-TTS)
- **Editing**: Remotion (React), FFmpeg
- **Publishing**: Buffer/Later (programmation multi-canal)

## Audience

- **Who**: Sportifs francais (et internationaux), 20-45 ans. Tennis, golf, running. S'entrainent 2-5 fois par semaine.
- **They want**: Progresser, arreter de craquer sous pression, performer en competition comme a l'entrainement.
- **They struggle with**: Stress pre-competition, perte de focus, manque de confiance, pas d'acces au coaching mental.

## Rules

- Zero emoji, nulle part, jamais
- Phrases courtes : max 20 mots en moyenne
- Verbes d'action : gerer, travailler, preparer, entrainer, progresser
- Jamais de face camera reelle -- avatar anime ou voix off uniquement
- Chaque contenu doit entrer dans un pilier : Democratisation (60%), Ressource (25%), Reinvention (15%)
- Si un contenu pourrait etre publie par Headspace ou Calm, il n'est pas Fokkus
- Si un contenu est un poster motivationnel, il n'est pas Fokkus
- Ne jamais traduire -- adapter. Chaque langue a ses references culturelles
- Chiffres sources uniquement. "90% des athletes olympiques entrainent leur mental" (US Olympic Training Center)
- Scripts video sous 100 mots pour 30s, sous 60 mots pour 15s
- Ne jamais comparer au prix d'un preparateur mental. L'accessibilite = dans ta poche + 3 minutes + adapte a ton sport.

## Messaging Pillars

1. **Democratisation** : "La preparation mentale n'est pas reservee a l'elite." Pourquoi le coaching mental doit etre accessible a tous les sportifs.
2. **Ressource** : "Le mental n'est plus un probleme a gerer, c'est une ressource." Exercices concrets, routines, techniques applicables immediatement. Le mental comme levier de performance.
3. **Reinvention** : "Reinventer la place du mental dans le sport." Le coach Max en action, l'app, la vision. Toujours en contexte.

## Taglines

- **Principale** : "Ton corps s'entraine. Ton mental aussi." / "Your body trains. Your mind should too."
- **Acquisition** : "Le coaching mental, accessible a tous les sportifs." / "Mental coaching for every athlete."
- **Produit** : "Ton coach mental dans ta poche." / "Your AI mental coach."
- **Democratisation** : "Le mental n'est pas reserve a l'elite. Il se travaille." / "Mental training isn't a privilege. It's a skill."
- **Premium** : "Travaille ton mental comme ta technique." / "Train your mind like you train your game."

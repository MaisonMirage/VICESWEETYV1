# Vice Sweety — Prompts Pomelli v4
### Hero Trompe-l'œil (fruits ENTIERS) + Équipe Boutique
#### Mangue + Fraise + Litchi
#### Réécrits à partir des VRAIES photos produit Vice Sweety

---

## L'ADN VISUEL VICE SWEETY (à respecter absolument)

Après analyse de toutes les photos produits existantes, voici ce qui fait l'identité visuelle Vice Sweety :

1. **Fond crème ultra-clean** — Toujours un fond beige/crème uni (#F5EDE3 environ), doux et chaud. Jamais de marbre noir, jamais de terrazzo, jamais de fond chargé.
2. **Zéro props** — Pas de fleurs, pas de menthe, pas de baies éparses, pas de miettes, pas de nappes. Juste le produit et son ombre.
3. **Ombre douce directionnelle** — Lumière naturelle latérale qui crée une ombre portée nette mais douce. Pas de lumière plate.
4. **Le produit est la star** — Un seul produit centré (ou un petit trio max). L'espace vide autour est essentiel — il crée le "wow".
5. **Hyper-réalisme des surfaces** — La magie c'est la texture : les pores du citron, les drupéoles de la framboise, les rides de la cacahuète, le dégradé de la mangue. Ça doit être indiscernable d'un vrai fruit.
6. **Fruits ENTIERS pour le hero** — Pas de coupe, pas d'intérieur visible. Le concept c'est l'illusion parfaite : on croit que ce sont de vrais fruits. La coupe/intérieur c'est pour les pages produits individuelles.
7. **Pas de style Cédric Grolet** — Pas de marbre noir, pas de studio froid chirurgical. Pas non plus de style food blogger (pas de flat lay chargé avec des props partout).

---

## PROMPT HERO — Trio litchi + fraise + framboise (format 16:9)

### L'idée
Exactement le même style que les photos `trio1.webp` et `trio22.webp` (angle bas, fond crème, 3 pièces espacées), mais avec les 3 pièces suivantes : litchi, fraise, framboise. Les images de référence des 3 produits doivent être données à Pomelli pour qu'il reproduise EXACTEMENT leur apparence. Le résultat doit être indistinguable d'une vraie photo.

### Images de référence à donner à Pomelli (OBLIGATOIRES)
1. `img/trio1.webp` — LA référence de composition (angle, espacement, fond, lumière)
2. `img/fraise.webp` — fraise entière exacte à reproduire
3. `img/framboise.webp` — framboise entière exacte à reproduire
4. `img/litchi.webp` — litchi entier exact à reproduire (la photo du trompe-l'œil litchi)

### Prompt
```
Recreate these three exact objects in a single photograph, arranged like the trio reference image.

WHAT TO REPRODUCE — three objects, described precisely. Use the reference images provided to match EXACTLY the shape, color, texture and finish of each object.

OBJECT 1 — LYCHEE (left position):
- Shape: near-perfect SPHERE, slightly wider than tall, about 5-6cm diameter — like a real lychee fruit. Compact and round. NOT elongated, NOT oval — a true sphere.
- Surface: covered in dozens of OVERLAPPING pointed scale-like bumps that mimic real lychee skin texture. Each bump is a small raised triangular/pointed protrusion. The bumps are tightly packed and cover the entire surface uniformly. This is NOT a smooth surface — it's heavily textured like real lychee rind.
- Finish: SEMI-MATTE — not glossy like the strawberry. The surface has a subtle sheen but no mirror reflection. Each individual bump catches light softly on its tip, creating a complex pattern of tiny micro-highlights across the whole surface.
- Color: bright cherry RED — the SAME red tone as the strawberry and raspberry. NOT coral, NOT orange-toned, NOT pinkish — a true vivid red, uniform across the entire surface, no gradient. All three objects must read as the same family of red.
- Top: a small brown woody STEM sits at the very top — short, stubby, natural-looking, slightly rough texture like a real dried twig. About 1cm long.
- Light behavior: the textured surface creates rich shadows in the crevices between bumps, giving the object incredible depth and dimension even in soft light
- NO biscuit base — the lychee sits directly on the surface

OBJECT 2 — STRAWBERRY (center position):
- Shape: classic strawberry, slightly tilted/leaning to one side, pointed bottom, wider top
- Surface: ultra-glossy mirror-like RED glaze — smooth, wet-looking, like a candy apple
- Color: uniform bright cherry red, no gradient
- Top: 5-6 small pointed leaves in matte dark green (sugar paste), contrasting with the glossy red body
- A single bright white specular highlight on the upper-left curve of the surface
- A few tiny air bubbles visible in the glaze surface
- NO biscuit base — the strawberry sits directly on the surface

OBJECT 3 — RASPBERRY (right position):
- Shape: compact dome/cone, wider at bottom, rounded top — SAME SIZE as the strawberry (about 6-7cm)
- Surface: ultra-glossy mirror RED glaze over individually sculpted drupelets (the round bumps of a raspberry)
- Each of the 20-30 drupelets catches its own small white highlight, creating a complex multi-highlight pattern
- Color: same bright red as the strawberry
- NO biscuit base — the raspberry sits directly on the surface

THE ARRANGEMENT:
- Camera angle: LOW, approximately 15-20 degrees from the surface (eye-level with the objects)
- The three objects are placed in a loose HORIZONTAL LINE, not perfectly aligned — staggered slightly in depth
- Left: lychee (small sphere). Center: strawberry (medium). Right: raspberry (same size as strawberry)
- Generous spacing between each — about 1.5 to 2 times the width of each object
- The objects are in the LOWER THIRD of the frame
- The upper 60% of the image is EMPTY cream background
- Shallow depth of field: the center object (strawberry) is sharpest, the lychee and raspberry are very slightly softer

THE SURFACE & LIGHT:
- Surface: smooth, warm cream/beige (#F5EDE3), completely clean and uniform — ZERO texture, ZERO pattern
- NOT marble, NOT terrazzo, NOT wood — a perfectly flat warm cream surface
- Soft warm directional light from the left side
- Each object casts a soft warm shadow to the right
- The glossy objects (strawberry, raspberry) have sharp bright white specular highlights
- The semi-matte object (lychee) has soft diffused light with subtle micro-highlights on each bump — no single strong specular highlight
- The background gently fades to a slightly lighter cream toward the top — no visible wall or horizon line
- Color temperature: warm, natural, like late morning sunlight in a bright studio

CRITICAL RULES:
- The result MUST look like a real photograph taken with a professional camera — NOT a 3D render, NOT an illustration
- Do NOT add any other objects: no flowers, no leaves, no herbs, no crumbs, no scattered berries, no plates, no fabric, no utensils
- Do NOT cut open any of the objects — they are all WHOLE and INTACT
- Do NOT change the colors or textures described above — the lychee is SEMI-MATTE with textured bumps, the strawberry and raspberry are GLOSSY smooth/drupelets
- NO biscuit, NO cookie base, NO sablé under any of the objects — they sit directly on the cream surface
- WIDE FORMAT 16:9 landscape — this is for a website hero banner
- The overall feeling should be: calm, minimal, editorial, premium
```

---

## PROMPT 3 : SECTION "NOTRE VICE" — L'équipe dans la boutique

### L'idée
On veut montrer l'humain derrière Vice Sweety. Pas un portrait corporate. C'est lifestyle : 2-3 personnes jeunes, cool, dans un espace qui respire Vice Sweety (deep purple, néon rose). L'énergie est positive, créative, ambitieuse.

### Images de référence à donner à Pomelli
- Le logo Vice Sweety (`assets/Vice_Sweety_Logo_FullTransparent.png`)
- Des photos d'intérieur de petites boutiques design tendance (Google "premium small dessert shop interior pink neon young team")
- Les photos existantes de l'équipe si disponibles (`img/hamza-portrait.webp`, etc.)

### Prompt
```
Lifestyle editorial photography of the young team behind "Vice Sweety" premium dessert brand in their boutique in Marseille. 2-3 people in their mid-20s, diverse, stylish, passionate about their craft.

THE PEOPLE:
- 2-3 young adults (mid-20s), natural and relaxed, genuine smiles
- Wearing matching Vice Sweety branded black aprons with the pink script logo
- One person is carefully finishing a trompe-l'œil fruit with a brush (artisan at work)
- Another is holding a Vice Sweety branded cup with a colorful smoothie, laughing
- They look like young entrepreneurs who love what they do — creative energy, pride, warmth

THE BOUTIQUE:
- The interior has the Vice Sweety DNA: deep purple walls (#1a0a2e) as the main accent
- A glowing pink neon "Vice Sweety" sign on the wall behind them (the script logo, glowing soft pink, not harsh)
- Touches of turquoise: turquoise bar stools, or a turquoise accent shelf
- A display of trompe-l'œil fruits visible in a glass case — the same hyper-realistic fruit desserts
- The counter is light marble or light wood — keeping it bright despite the dark accent wall
- The overall vibe: it's a small premium takeaway shop that feels like stepping into a Miami beach bar

THE LIGHT:
- Bright natural daylight flooding in from large windows on one side
- The neon sign casts a subtle pink glow on the wall
- The light is warm and inviting — this is a place you WANT to walk into
- NOT dark or moody — the deep purple is an accent, not the dominant mood

CAMERA:
- Medium shot, showing the team from the waist up with the boutique visible behind them
- Slight candid feel — they're caught in a moment of work and fun
- Sharp focus on the people, the neon sign softly glowing in the background
- Professional lifestyle photography, Kinfolk/Monocle magazine quality
- WIDE FORMAT 16:9 landscape
- Color temperature: warm, natural, inviting
```

---

## PROMPT 4 : SECTION "NOTRE VICE" — Alternatif (sans personnes, juste la boutique)

### L'idée
Si Pomelli a du mal avec les personnes, cette version montre juste l'intérieur de la boutique Vice Sweety — mais elle est tellement belle et instagrammable qu'elle raconte toute l'histoire seule.

### Prompt
```
Interior photography of "Vice Sweety" premium dessert boutique in Marseille. A small, beautiful takeaway shop that feels like stepping into a Miami dream.

THE SPACE:
- Compact but designed with obsessive detail
- One feature wall in deep purple (#1a0a2e) with a glowing neon "Vice Sweety" script sign in soft pink — the hero element
- Other walls: bright white or pale blush pink, keeping the space light and airy
- A sleek counter in light marble or pale wood
- Behind the counter: a display case showing rows of trompe-l'œil fruits — the hyper-realistic fruit-shaped desserts glow like jewels under warm light
- Turquoise accents: bar stools, menu board frame, or a small neon palm tree outline
- The menu board: dark background with pink and turquoise text
- A few branded Vice Sweety cups visible on the counter — clear cups with pink palm tree pattern, deep purple boxes
- Black and white checkered floor tiles (classic Miami diner vibe)
- One or two real tropical plants (monstera, small palm)

THE LIGHT:
- Bright natural daylight flooding from the front windows
- The neon sign creates a beautiful pink glow zone on the purple wall
- The combination of natural warm light + pink neon glow creates a dreamy, inviting atmosphere
- The trompe-l'œil fruits in the display case are illuminated and colorful

ATMOSPHERE:
- This is the kind of place that makes people stop on the street and take a photo through the window
- It's premium but approachable — not cold luxury, not cheap fast food
- It balances the "vice" (dark purple, neon) with the "sweet" (pink, turquoise, sunlight, warmth)

CAMERA:
- Wide angle from the entrance, showing the full space
- The neon sign is the visual anchor in the background
- Sharp focus throughout, architectural photography quality
- WIDE FORMAT 16:9 landscape
- Color temperature: warm with the pink neon tint
```

---

## PROMPT 5 : TROMPE-L'ŒIL FULL-WIDTH (remplace hero-flatlay.webp)

### L'idée
L'image actuelle du bloc "Trompe-l'œil" est un flat lay vu du dessus, terne et faible. On veut la même énergie que le trio hero : angle bas, fond crème, produits alignés — mais avec 5-6 fruits trompe-l'œil différents pour montrer la diversité de la gamme. C'est la photo "catalogue éditorial" — elle doit donner envie de tout goûter.

### Images de référence à donner à Pomelli (OBLIGATOIRES)
1. `img/trio1.webp` ou le hero trio généré — LA référence d'angle et de lumière
2. Les photos individuelles de chaque trompe-l'œil que tu as : fraise, framboise, litchi, citron, mangue, passion, etc.

### Images de référence à donner à Pomelli
1. L'image générée des 6 fruits (la première version) — pour la composition, l'angle, le fond
2. Les zoom photos de chaque produit réel dans `img/` (citron-zoom.webp, fraise-zoom.webp, passion-zoom.webp, peche-zoom.webp)

### Prompt
```
Professional food photography of six hyper-realistic fruit-shaped desserts (trompe-l'œil pâtisseries) arranged in a row on a warm cream surface. These are PASTRIES that mimic real fruits — each one is a work of edible art. Use the reference images to match the exact textures.

THE SIX OBJECTS (left to right, this order is CRITICAL for color alternation):

1. LEMON (far left):
- Shape: classic oval lemon, slightly pointed at both ends, about 8cm long
- Surface: MATTE with a dense coat of fine SUGAR CRYSTALS or granulated texture covering the entire surface — like the fruit was rolled in fine caster sugar. The tiny granules catch the light individually, creating a sparkling, frosty appearance. Up close you can see hundreds of tiny white-ish crystals sitting on top of the yellow surface.
- Color: bright vivid acid yellow, uniform, the sugar crystal layer adds a slightly frosted/whitish shimmer on top
- A small green sugar paste leaf at the stem end
- Finish: the opposite of glossy — dry, granular, crystalline, frosted

2. PASSION FRUIT (center-left):
- Shape: smooth perfect SPHERE, about 6-7cm diameter — like a billiard ball, NOT wrinkled like a real passion fruit
- Surface: ultra-GLOSSY mirror glaze in deep PLUM PURPLE / BURGUNDY — so shiny you can see the environment reflected in it (visible square window/light reflection). The glaze is flawless, wet-looking, like liquid glass.
- GOLD DECORATION: scattered across the entire surface are tiny speckles, splatters and veins of EDIBLE GOLD DUST and gold leaf fragments. The gold is NOT uniform — it's artistically splattered, with some areas having dense clusters and others sparse. The gold catches the light brilliantly against the dark purple.
- A single bright white specular highlight on the upper curve
- This piece is the SHOWSTOPPER of the lineup — the contrast of dark purple + gold is dramatic and luxurious

3. STRAWBERRY (center):
- Shape: classic strawberry silhouette, wider at top, pointed bottom, slightly tilted/leaning to one side
- Surface: ultra-GLOSSY MIRROR cherry-red glaze — smooth, wet-looking, like a candy apple. The glaze is so reflective it looks liquid.
- Several tiny AIR BUBBLES are trapped in the glaze surface — 5-8 tiny spherical bubbles visible, some catching light. This is a signature detail of real mirror glaze work.
- Top: 5-6 small pointed LEAVES in matte dark green SUGAR PASTE, sculpted by hand — they contrast sharply with the glossy red body
- One bright white specular highlight on the upper-left curve
- Color: uniform bright cherry red, no gradient

4. LYCHEE (center-right):
- Shape: near-perfect SPHERE, about 5-6cm, compact and round
- Surface: covered in dozens of OVERLAPPING pointed SCALE-LIKE BUMPS mimicking real lychee rind — each bump is a small raised triangular protrusion, tightly packed. This is NOT a smooth surface — it's the most heavily textured piece in the lineup.
- Finish: SEMI-MATTE — subtle sheen but no mirror reflection. Each bump tip catches a tiny micro-highlight, creating a complex light pattern across the whole surface.
- Color: bright cherry red, same red family as the strawberry
- Top: small brown woody STEM, short, stubby, about 1cm
- The texture creates rich shadows in the crevices between bumps — incredible depth

5. PEACH (center-right):
- Shape: round sphere, slightly taller than wide, about 7cm. A small brown woody STEM on top.
- Surface: VELVET SPRAY FINISH (cocoa butter spray technique used on premium French entremets) — ultra-fine, powdery, velvety matte. The texture looks like suede or fine sandpaper. Up close you can see the millions of tiny powder particles creating a soft, fuzzy appearance.
- Color: a smooth GRADIENT from golden yellow at the top → warm orange in the middle → soft pinkish-RED BLUSH on one side. The gradient is AIRBRUSHED — too smooth, too seamless, too perfect to be natural. It looks like it was applied with a spray gun.
- THIS IS A PASTRY, NOT A REAL PEACH: the giveaway is the perfectly uniform velvet texture with ZERO imperfections, zero bruises, zero natural irregularities. The gradient is too precise. It should clearly read as an entremet coated in velvet spray.

6. MANDARINE (far right):
- Shape: sphere, slightly FLATTENED at top and bottom (like a real mandarine), about 6cm
- Surface: dense, finely textured ORANGE PEEL pattern — thousands of tiny uniform dimples covering the entire surface, like real mandarine skin but coated in a thin layer of MATTE ORANGE GLAZE that makes it slightly too regular, too perfect
- A small brown dried STEM and one dark green sugar paste LEAF at the top
- Color: vivid warm orange, uniform, no gradient
- Finish: matte to semi-matte, the dimpled texture catches light in a complex wavy pattern

THE ARRANGEMENT:
- Camera angle: LOW, approximately 15-20 degrees from the surface (eye-level with the objects)
- The six objects in a loose HORIZONTAL LINE, slightly staggered in depth — not perfectly aligned
- Generous spacing between each — about 1 to 1.5x the width of each object
- Objects in the LOWER THIRD of the frame
- Upper 50% is EMPTY cream background
- The order left-to-right MUST be: yellow → purple → red → red-textured → peach → orange (color alternation)

THE SURFACE & LIGHT:
- Surface: smooth, warm cream/beige (#F5EDE3), completely clean and uniform — ZERO texture
- Soft warm directional light from the left side
- Each object casts a soft warm shadow to the right
- The GLOSSY objects (passion, strawberry) have sharp white specular highlights
- The MATTE objects (lemon, peach, mandarine) have soft diffused light
- The TEXTURED object (lychee) has complex micro-highlights on each bump
- Shallow depth of field: center objects (passion + strawberry) sharpest, edges slightly softer
- Color temperature: warm, natural, late morning studio light

CRITICAL RULES:
- MUST look like a real photograph — NOT a 3D render, NOT an illustration
- These are PASTRIES mimicking fruits — they should look like edible art, not real fruits from a grocery store
- The passion fruit MUST have visible gold dust/speckles on its purple surface
- The lemon MUST have visible sugar crystal granules on its surface
- The peach MUST look like a velvet-sprayed entremet, NOT a real peach
- NO other objects: no flowers, no plates, no fabric, no props
- ALL objects WHOLE and INTACT — no cuts
- NO biscuit base under any object
- WIDE FORMAT 16:9 landscape
- The feeling: calm, minimal, editorial, premium — like a Vogue food editorial spread
```

---

## PROMPT 6 : ATELIER ARTISANAL (remplace vitrine-boutique.webp dans "Notre Vice")

### L'idée
La section "Notre Vice" raconte l'histoire de Vice Sweety. L'image actuelle est un rendu AI qui fait fake. On veut une photo lifestyle crédible : les mains d'un artisan en train de travailler sur un trompe-l'œil. C'est l'authenticité, le fait-main, la passion. Pas de visage nécessaire — juste les mains, le produit, et l'ambiance atelier.

### Images de référence à donner à Pomelli
- Photos de pâtissiers en train de glacer des entremets (Google "pastry chef glazing entremet hands close up")
- Les photos de tes trompe-l'œil (fraise, litchi, etc.) pour que Pomelli sache quoi mettre dans la scène

### Prompt
```
Close-up lifestyle photography of artisan hands carefully glazing a hyper-realistic fruit-shaped dessert (trompe-l'œil pâtisserie) in a bright, warm workshop.

THE HANDS:
- Two hands visible: one holding the dessert steady on a small turning stand, the other applying a final layer of glossy red glaze with a small pastry brush
- The hands are young, clean, skilled — wearing no gloves (artisan authenticity)
- Natural skin tones, no heavy editing

THE DESSERT BEING MADE:
- A strawberry-shaped trompe-l'œil on a small metal turning stand/pedestal
- The glaze is being applied — it's glossy, wet, cherry red, dripping slightly
- The strawberry is almost finished — you can see the precision of the work
- A few other finished trompe-l'œil fruits visible in soft focus in the background: a yellow lemon, a red raspberry, placed on a cream-colored work surface

THE WORKSPACE:
- A clean, bright pastry workshop — NOT industrial, NOT a home kitchen
- The work surface is light marble or pale wood
- Soft natural light coming from a window on the left
- Shallow depth of field: the hands and strawberry are razor sharp, the background gently blurred
- In the soft background: a hint of branded Vice Sweety elements — maybe a dark apron with the pink logo partially visible, or a branded cup on a shelf

THE MOOD:
- This is craft. This is care. This is someone who obsesses over every detail.
- Warm, intimate, authentic — like a behind-the-scenes documentary shot
- NOT staged or corporate. It should feel like a stolen moment during production.

CAMERA:
- Close-up / medium close-up — from hands to mid-chest area max
- Slightly overhead angle (about 30-40 degrees), looking down at the work
- Professional lifestyle photography, Kinfolk/Cereal magazine quality
- Landscape format (16:9 or 3:2)
- Color temperature: warm, golden, natural
```

---

## PROMPT 7 : INSTAGRAM LIFESTYLE (4 images uniques)

### L'idée
La grille Instagram du site recycle les mêmes images que les catégories. Pour un site award-winner, il faut 4 images lifestyle uniques qui montrent la marque "en situation" — pas des packshots produit. Elles doivent être carrées (1:1) pour la grille Instagram.

### Prompt 7A — Smoothie en terrasse
```
Lifestyle photography: a young woman's hand holding a Vice Sweety branded clear plastic cup filled with a vibrant orange-to-yellow mango smoothie. The cup has pink palm tree and flamingo patterns printed on it, with "Vice Sweety" in pink script.

Setting: outdoor Mediterranean terrace in Marseille, golden hour sunlight, blurred background showing pink bougainvillea and warm stone buildings. The smoothie catches the sunset light, glowing warm orange.

Mood: summer, carefree, golden, aspirational.
Camera: close-up on the hand and cup, shallow depth of field, warm color temperature.
FORMAT: SQUARE 1:1
```

### Prompt 7B — Glaçage miroir en cours
```
Extreme close-up macro photography of glossy cherry-red mirror glaze being poured over a spherical dessert mold. The glaze is thick, smooth, and impossibly shiny — you can see reflections in it. It cascades down the sides of the sphere in perfect rivulets.

The background is a clean, bright pastry workshop — blurred, with warm natural light from a window. A few drops of red glaze have pooled on the clean white work surface below.

Mood: satisfying, mesmerizing, premium craftsmanship. The kind of image you watch on loop.
Camera: extreme close-up, shallow depth of field, sharp focus on the glaze surface, warm color temperature.
FORMAT: SQUARE 1:1
```

### Prompt 7C — Table entre amis
```
Overhead flat lay photography of a small round marble café table with Vice Sweety desserts being shared between friends. Visible on the table:
- 2-3 Vice Sweety branded cups (one pink milkshake with whipped cream, one orange smoothie)
- A small open branded black box with pink palm tree pattern, containing 3 trompe-l'œil fruit desserts (a red strawberry, a yellow lemon, a red raspberry)
- 2-3 pairs of hands reaching toward the desserts — casual, fun, social
- One phone on the table (someone was about to take a photo of the food)

The table is on a sunny terrace. Warm Mediterranean light. Soft shadows. The branded packaging ties it all together.

Mood: social, fun, sharing, the Vice Sweety experience with friends.
Camera: directly overhead (90 degrees), warm natural light, sharp focus.
FORMAT: SQUARE 1:1
```

### Prompt 7D — Devanture boutique
```
Street photography of a small, beautiful storefront at golden hour. The facade is painted in deep matte purple (#1a0a2e). A glowing pink neon "Vice Sweety" script sign is visible through the large window, casting a soft pink glow.

Through the window you can see: a bright, inviting interior with warm lights, a display case of colorful desserts, and turquoise accent details. A small queue of 2-3 people waiting outside — young, stylish, holding their phones.

The street is a charming Marseille side street — warm stone buildings, a palm tree visible, evening golden light hitting the facade.

Mood: discovery, FOMO, "I need to go there", instagrammable destination.
Camera: wide-ish street shot (the storefront fills about 60% of the frame), warm golden hour light, professional street photography.
FORMAT: SQUARE 1:1
```

---

## PROMPT 8 : HERO MOBILE (portrait 9:16)

### L'idée
Le hero trio actuel est en 16:9 paysage — parfait pour desktop mais les fruits deviennent minuscules sur mobile. Il faut une version portrait qui cadre les 3 fruits en plus gros, empilés verticalement ou en triangle rapproché.

### Images de référence à donner à Pomelli
- Le hero trio déjà généré (pour que Pomelli reproduise exactement les mêmes 3 objets)
- `img/litchi.webp`, `img/fraise.webp`, `img/framboise.webp`

### Prompt
```
Recreate these three exact trompe-l'œil desserts in a VERTICAL portrait composition, arranged in a tight triangular cluster.

THE THREE OBJECTS (same as the landscape hero version — match them EXACTLY):
- A LYCHEE: red sphere with overlapping pointed scale-like bumps, semi-matte finish, small brown woody stem on top
- A STRAWBERRY: ultra-glossy mirror cherry-red glaze, smooth wet surface, dark green sugar paste leaves on top
- A RASPBERRY: glossy mirror-red glaze over sculpted drupelets, dome/cone shape

THE ARRANGEMENT:
- The three objects are clustered in a TIGHT TRIANGLE in the CENTER of the frame
- Strawberry at the top-center (slightly behind), lychee bottom-left, raspberry bottom-right
- They are close together — almost touching — creating an intimate grouping
- The cluster sits in the LOWER HALF of the frame
- The upper 40-50% is EMPTY cream background (space for text overlay on mobile)

CAMERA:
- Slightly elevated angle: about 25-30 degrees (looking slightly down at the cluster)
- The three objects fill about 40-50% of the frame — they should be BIG and detailed
- Shallow depth of field: all three are sharp, background very softly blurred

SURFACE & LIGHT:
- Same warm cream surface (#F5EDE3), clean, uniform
- Soft warm directional light from the left
- Soft shadows to the right
- Warm, natural color temperature

CRITICAL RULES:
- MUST match the exact same objects from the landscape version — same colors, textures, sizes
- PORTRAIT FORMAT 9:16 (vertical, for mobile hero)
- Calm, minimal, editorial, premium
- NO props, NO biscuit, NO cuts — whole objects only
```

---

## Notes d'utilisation

Pour chaque prompt :
1. Coller le prompt dans Pomelli
2. **TRÈS IMPORTANT** — ajouter comme images de référence les fichiers listés au-dessus de chaque prompt. Ce sont les VRAIES photos Vice Sweety, Pomelli doit s'en inspirer pour le réalisme et le style.
3. Pour les prompts 1 et 2 (hero), les images de référence sont CRITIQUES — elles montrent le vrai rendu des trompe-l'œil (fond crème clean, ombres douces, coulis qui coule, textures hyper-réalistes)
4. Générer 4 variations, garder la meilleure
5. Nommer les fichiers : `hero-trompeloeil.webp`, `equipe-boutique.webp` ou `boutique-interior.webp`
6. Les mettre dans le dossier `img/`

### Ce qu'il faut ÉVITER (erreurs des essais précédents) :
- ❌ Vrais fruits éparpillés autour des trompe-l'œil
- ❌ Fleurs, feuilles de menthe, pétales en décoration
- ❌ Surface texturée (terrazzo, marbre veiné)
- ❌ Trop de pièces serrées les unes contre les autres
- ❌ Props (assiettes turquoise, nappes, ustensiles)
- ❌ Miettes et sucre glace partout
- ❌ Style "flat lay food blogger Pinterest"
- ❌ Fruits coupés / intérieur visible (ça rend 3D/fake avec Pomelli)
- ❌ Biscuit/sablé visible en dessous
- ❌ Rendu 3D / plastique / cartoon — si ça ressemble pas à une VRAIE photo, c'est raté

### Ce qu'il FAUT :
- ✅ Fond crème uni, chaud, clean
- ✅ Espace vide généreux entre les pièces
- ✅ Fruits ENTIERS uniquement — l'illusion parfaite
- ✅ Textures hyper-réalistes sur les surfaces (pores, drupéoles, rides, dégradés)
- ✅ Ombres douces directionnelles
- ✅ Style éditorial minimaliste premium
- ✅ Le viewer doit penser "ce sont de vrais fruits" — rien d'autre

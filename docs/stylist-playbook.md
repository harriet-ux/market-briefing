# The Stylist's Playbook

*The working knowledge a high-end personal stylist uses to dress a client well — colour science, body architecture, the craft of putting a look together, and a translation of all of it into rules an app's recommendation engine can execute.*

> **How to read this document.** Parts 1–3 are the reference library: the "why" behind good dressing, written for a human reader. Part 4 is the operational spec: the same knowledge compressed into deterministic, codeable rules for a "dress-me-for-my-day" engine. Where genuine expert disagreement exists (most of all in seasonal colour analysis), it is flagged explicitly rather than smoothed over.

> **A note on framing.** Modern professional styling treats body-shape and proportion guidance as *tools for emphasis*, not rules about "flaws." A silhouette strategy is a way to direct the eye toward what a client wants to feature and create the lines they find pleasing — never a correction of a problem. Every rule below is optional, and client preference outranks it (see §4.6).

---

## Part 1 — Colour Theory for Dressing

### 1.1 The colour wheel and outfit harmonies

The colour wheel is the stylist's map for combining hues. Five harmony types cover almost every deliberate colour outfit:

| Harmony | Definition (positions on the wheel) | Effect | Concrete outfit example |
|---|---|---|---|
| **Complementary** | Two hues directly opposite (e.g. blue/orange, purple/yellow, red/green) | Highest contrast, high energy, "pop" | Cobalt-blue dress with tan/orange-toned accessories; a rust knit with teal trousers |
| **Analogous** | Two–three hues adjacent on the wheel (e.g. blue + blue-green + green) | Harmonious, subtle, low-tension | Olive trousers, sage shirt, forest-green jacket; blue jeans with a teal top |
| **Monochromatic** | One hue in several values/tints/shades/tones | Elongating, elegant, sophisticated; reads as one long column | Camel coat over cream knit over mocha trouser; head-to-toe tonal navy |
| **Triadic** | Three hues evenly spaced (120° apart), e.g. red/yellow/blue or purple/orange/green | Vibrant, playful, balanced but bold | Mustard top, plum bag, teal shoe; primary-brights outfit |
| **Split-complementary** | A base hue + the two hues *adjacent to its complement* (e.g. blue + red-orange + yellow-orange) | Complementary "pop" with less tension than true complementary; more forgiving | Navy suit with a coral OR peachy-terracotta accent instead of pure orange |

Practical guidance stylists actually use:
- **Complementary** is the go-to when a client wants to stand out or create a focal point; use one colour as the outfit and the other as a smaller accent rather than 50/50.
- **Analogous and monochromatic** are the "quiet luxury" harmonies — safest, most flattering, least likely to look costume-y.
- **Triadic** is the riskiest for everyday and works best with one dominant colour and the other two as accents.
- The **"3-colour rule"**: keep a single outfit to roughly three colours (neutrals barely count against this) to stay coherent.

Sources: [HowToWear – Color theory / colour wheel when getting dressed](https://howtowearfashion.com/styling-tips/how-to-use-the-color-wheel-when-getting-dressed), [Sessions College Color Calculator](https://www.sessions.edu/color-calculator/), [Melco Fabrics – Color harmonies for outfits](https://www.melcofabrics.com.au/blogs/the-sewing-room/creating-a-color-harmonious-outfit-a-beginners-guide-to-color-harmonies), [The Paper Mill Store – Complementary to Monochromatic](https://blog.thepapermillstore.com/color-theory-color-harmonies/), [Lookiero – Colour wheel for matching clothes](https://lookiero.co.uk/blog/colour-wheel-matching-clothes), [NeceSera – The 3-colour rule](https://www.necesera.com/blogs/news/the-3-color-principle-in-fashion).

### 1.2 Neutrals: the anchors and extenders

Neutrals — **black, white, navy, grey, beige/greige, camel, brown, olive, stone/cream** — are the backbone of a versatile wardrobe. Functionally they do two jobs:

1. **Anchor.** A neutral gives an outfit a "centre of gravity" — the structured piece (blazer, coat, boot, bag) around which the eye organises everything. The anchor need not be the boldest item; it is the one with presence and structure.
2. **Extend.** Because neutrals combine with almost anything (including each other), they multiply the number of workable outfits from a fixed number of pieces.

Key operating rules:
- **A neutral pairs with any statement colour** and with other neutrals. Reliable neutral-on-neutral combinations: navy + camel + white (universally flattering), grey + blush, cream + mocha + tan, black + white (highest contrast), olive + stone.
- **The "one statement colour + neutrals" rule.** The safest way to wear colour: keep the base neutral and let a single item carry the colour (a sage tee, rust chinos, a cobalt shoe). This is the most-used real-world colour formula because it is almost impossible to get wrong.
- Neutrals divide into **warm** (camel, beige, cream, warm brown, olive) and **cool** (true grey, pure white, black, navy leaning blue). Matching the neutral's temperature to the client's undertone (§1.3) sharpens the look.
- Because neutral outfits are low on colour interest, **texture and proportion carry the outfit** — fabric contrast is what stops an all-neutral look reading flat.

Sources: [Cedar & Lily – Neutral color combinations](https://cedarandlilyclothier.com/blogs/blog/neutral-color-combinations), [Shopping on Champagne – The modern way to wear neutrals](https://www.shoppingonchampagne.com/blog/the-modern-way-to-wear-neutrals), [OGLmove – What are neutral colours](https://oglmove.com/blogs/knowledge/what-are-neutral-colors-in-clothing), [Westwood Hart – Navy, camel & grey](https://westwoodhart.com/blogs/westwood-hart/how-to-wear-navy-camel-grey-mens-fashion-guide).

### 1.3 Skin undertone → colours and metals

**Undertone** is the constant hue *beneath* the skin's surface (distinct from surface "tone," which tans and fades). Three categories:

- **Warm** — yellow, peach, golden beneath the skin.
- **Cool** — blue, pink, or red beneath the skin.
- **Neutral** — a balance of both; can wear either temperature.

**How stylists determine undertone (use several tests, not one):**

| Test | Warm signal | Cool signal |
|---|---|---|
| **Vein test** (inner wrist, natural light) | Veins look green | Veins look blue/purple |
| **Metal / foil test** (gold vs silver against skin) | Gold makes skin look clearer, "alive" | Silver makes skin look clearer |
| **White test** (pure white vs cream next to face) | Cream/ivory flatters more | Pure white flatters more |
| **Sun reaction** | Tans easily, rarely burns | Burns easily, tans little |
| **Eye/hair warmth** | Golden, honey, warm brown tones | Ashy, cool brown, blue-grey tones |

The **foil/metal test is the single most reliable** because it directly answers the practical question ("which metals and, by extension, which temperature of colour suits me?"). If tests conflict, the person is likely **neutral**.

**Undertone → metal (a hard rule the engine can use):**
- **Warm → yellow gold, rose gold, brass, copper.**
- **Cool → silver, white gold, platinum, steel.**
- **Neutral → both; can also mix metals.**

**Undertone → colour temperature:** warm undertones are flattered by warm-based colours (coral, tomato red, mustard, olive, warm teal, cream, camel); cool undertones by cool-based colours (blue-red/berry, emerald, cool pink, blue, pure white, grey). Neutral undertones can wear muted/balanced versions of most hues.

Sources: [Delia Langan – Determine your undertone for gold/silver/rose gold](https://delialangan.com/blogs/news/how-to-determine-your-undertone-for-gold-silver-or-rose-gold-jewelry), [Palette Hunt – Gold vs silver for your skin tone](https://www.palettehunt.com/guide/gold-vs-silver-jewelry-for-your-skin-tone), [VRAI – Silver or gold for your skin tone](https://www.vrai.com/journal/post/should-i-choose-silver-or-gold-jewelry-for-my-skin-tone), [Louis Faglin – Matching jewellery to undertone](https://global.louisfaglin.com/blogs/blog/matching-jewelry-to-your-skin-undertone-the-ultimate-guide).

### 1.4 Seasonal colour analysis (4-season and 12-season)

Seasonal colour analysis sorts a person's natural colouring into a "season" whose palette harmonises with them. It rests on **three dimensions**:

1. **Undertone / Hue** — warm vs cool.
2. **Value** — overall lightness vs depth of the person's hair, skin, and eyes (light blonde/fair/light eyes = high value; dark hair/deep skin/dark eyes = low value).
3. **Chroma (saturation)** — whether the colouring is bright/clear or muted/soft.

**The four base seasons:**

| Season | Undertone | Character | Palette signature |
|---|---|---|---|
| **Spring** | Warm | Light + clear/bright | Coral, peach, turquoise, clear warm greens, golden yellows |
| **Summer** | Cool | Light + soft/muted | Soft blues, dusty pinks, lavender, soft grey, mauve |
| **Autumn** | Warm | Deep + muted/rich | Olive, rust, mustard, warm brown, teal, terracotta |
| **Winter** | Cool | Deep + bright/high-contrast | Pure white, black, jewel tones (emerald, sapphire, fuchsia), icy brights |

**The 12-season system** subdivides each season into three, because two people can both be "Autumn" yet suit visibly different palettes — the 4-season grid was missing resolution. Each season gets a "true" version plus two that borrow from an adjacent season, defined by which secondary dimension dominates:
- **Spring** → Light Spring, True/Warm Spring, Bright/Clear Spring
- **Summer** → Light Summer, True/Cool Summer, Soft/Muted Summer
- **Autumn** → Soft/Muted Autumn, True/Warm Autumn, Deep Autumn
- **Winter** → Deep Winter, True/Cool Winter, Bright/Clear Winter

(A 16-season variant exists that adds further edge cases.) Determination order in practice: establish undertone first, then value, then chroma, testing by draping fabric near the face and comparing which version "lifts" the face.

**Limits and criticisms — state these plainly; the science is genuinely soft here:**
- **It is partly subjective.** Trained analysts sometimes disagree on the same client; people have paid for analysis multiple times and received different seasons each time.
- **Lighting, the specific swatches used, and the analyst's own visual calibration all introduce variability.** "Before/after" photos are often misleading because the "before" simply has worse lighting.
- **The four seasons are a simplification of a continuous spectrum** of human colouring. Some people sit clearly inside a season; many sit at the edges between two.
- **No one looks good in *every* colour of their season, or bad in *every* colour outside it.** Treat the palette as a strong prior, not a cage.

For an app, the pragmatic stance is: use season as a *soft palette bias*, let the more robust, less-subjective **undertone** and **contrast level** (§1.5) do the heavy lifting, and always let the client override.

Sources: [Palette Hunt – 12-season analysis explained](https://www.palettehunt.com/guide/12-season-color-analysis-explained), [Color Analysis App – Four seasons complete guide](https://color-analysis.app/blog/complete-guide-four-seasons-color-palette), [Color Analysis App – Is seasonal colour analysis worth it](https://color-analysis.app/blog/is-seasonal-color-analysis-worth-it), [PalettePath – 12-season explained](https://palettepath.com/color-analysis/12-season-color-analysis-explained/), [ColorMe – 12-season system](https://colorme.style/12-season-color-analysis/), [Laura K Collins – The truth about seasonal colour analysis](https://laurakcollins.com/the-truth-about-seasonal-color-analysis-perspective-of-a-hairstylist/).

### 1.5 Value and personal contrast

**Contrast** here means *value* contrast — the difference in lightness between a person's hair, skin, and eyes.

- **High contrast:** e.g. dark hair + fair skin + light eyes. Natural drama.
- **Low contrast:** e.g. blonde/silver hair + fair skin + pale eyes (or deep skin + deep hair + deep eyes that are close in value). Soft, blended.
- **Medium contrast:** a noticeable but not extreme difference.

**How to determine it:** photograph the bare face and convert to greyscale — the size of the light-to-dark jump between hair, skin, and eyes is the contrast level.

**The golden rule: dress at roughly your own contrast level.**
- **High-contrast people** thrive in strong value differences: black-and-white, deep-with-light colour blocking. Soft tonal outfits can leave them looking washed-out/underdressed.
- **Low-contrast people** suit tonal dressing — adjacent values of one colour family (values only 1–3 steps apart). Sharp black-and-white combinations overwhelm them; the outfit becomes the focal point and the person "disappears."
- **Contrast matters most at the neckline** (closest to the face). A high-contrast person can wear a low-contrast lower half but needs some contrast up top; a low-contrast person should avoid sharp value jumps near the face even if the rest of the outfit plays more.

This is arguably **more actionable and less subjective than season**, because greyscale value is measurable.

Sources: [A Well Styled Life – Find your contrast level](https://awellstyledlife.com/how-to-find-your-personal-contrast-level/), [Inside Out Style – Value contrast levels](https://insideoutstyleblog.com/2014/03/getting-your-value-contrast-levels-right.html), [Signature Style Systems – Why contrast matters more than season](https://signaturestylesystems.com/why-your-value-contrast-level-matters-more-than-your-season/), [Palette Hunt – High vs low contrast colouring](https://www.palettehunt.com/guide/high-contrast-vs-low-contrast-coloring-explained).

### 1.6 Colour psychology in dressing (kept practical)

Colour sends a message before a word is spoken. Practical associations a stylist leans on when a client says *"I want to feel/read as ___"*:

| Colour | Communicates | Good for |
|---|---|---|
| **Red** | Energy, passion, power, urgency | Standing out, confidence moments, presentations, dates |
| **Blue (navy/mid)** | Trust, stability, competence, calm | Interviews, first meetings, authority without aggression |
| **Black** | Elegance, authority, control, "emotional armour" | Formal wear, wanting to feel in charge / undisturbed |
| **White/cream** | Clean, fresh, simple, honest | Crisp, minimal, warm-weather polish |
| **Green (olive/forest)** | Balance, natural, grounded, reassuring | Approachable, calm competence |
| **Yellow/gold** | Optimism, warmth, creativity | Energy, sociability (use as accent) |
| **Pink (blush→hot)** | Soft/romantic (pale) to bold/playful (bright) | Warmth, approachability, or statement |
| **Grey** | Neutral, professional, understated | Backdrop, quiet authority |
| **Purple** | Creativity, luxury, individuality | Distinctiveness |

Rule of thumb: warm brights (red, yellow) project energy and confidence; cool tones (blue, green) project calm and trust. Use this to choose the *statement colour* once the "how do you want to feel?" input is known.

Sources: [Velvet Image Lab – Psychology of colour / what your outfit says](https://velvetimagelab.com/blogs/main/the-psychology-of-color-what-your-outfit-colors-say-about-you), [The Good Trade – Colour psychology to pick clothing](https://www.thegoodtrade.com/features/clothing-color-psychology/), [SELVANE – Psychology of colour in fashion](https://www.selvane.co/blogs/knowledge/the-psychology-of-color-in-fashion-how-hue-saturation-and-value-affect-perception).

---

## Part 2 — Body Shapes & Proportion

> **Framing reminder:** these are strategies for *directing the eye* and creating lines a client likes, not corrections. The "goal" stated for each shape is the *conventional* balancing objective; a client may legitimately want the opposite (e.g. an hourglass who wants to downplay curves for a work context). The engine should treat these as defaults the user can invert.

### 2.1 The major shapes, with strategies

The five classic female shapes are read from the relationship between **shoulders/bust, waist, and hips**.

#### Hourglass — bust and hips balanced, waist clearly defined
**Conventional goal:** maintain the balance and showcase the defined waist; avoid adding bulk that hides it.

| Element | Do | Avoid |
|---|---|---|
| Silhouette | Fitted/semi-fitted that follows the waist; wrap styles; belts | Boxy, shapeless, "column" pieces that swallow the waist |
| Necklines | Softly rounded — oval, deep oval, jewel, scoop, V | Extremes that fight the balanced frame |
| Sleeves/shoulders | Set-in, nothing that over-widens shoulders | Heavy shoulder detail (unbalances the even top/bottom) |
| Waist | Emphasise it — nipped seams, belts, high-waist tuck | Drop-waist, straight sack shapes |
| Trousers | High- or mid-rise, straight or bootcut that skims curves | Baggy low-rise that hides the waist |
| Skirts/dresses | Wrap, sheath, fit-and-flare, bodycon | Stiff full skirts that add width top-and-bottom |

#### Pear / Triangle — hips wider than shoulders; weight in the lower body
**Conventional goal:** add visual volume/interest up top, keep the lower body clean, define the waist.

| Element | Do | Avoid |
|---|---|---|
| Upper body | Bright colours, bold patterns, detail, embellishment at bust/shoulders | Busy detail on the hips/thighs |
| Necklines | Wide — boat/bateau, square, Sabrina, off-shoulder | Very narrow necklines that shrink the top |
| Sleeves/shoulders | Puff, cap, structured shoulder, shoulder pads, ruffles | Nothing that narrows the shoulder line |
| Tops | End at the waist or hipbone (crop or hip-length) | Tops ending at the widest hip point |
| Bottoms | Darker/neutral colours; A-line skirts; high-waisted bootcut; straight leg | Tight tapers, clingy thin fabrics through the thigh, low rise, horizontal detail on hips |
| Dresses | A-line, wrap, tulip, empire, fit-and-flare | Bodycon that grips the hip |

#### Apple / Round / Oval — fuller midsection, often broader bust/shoulders, narrower hips, slimmer legs
**Conventional goal:** draw the eye up (face/décolletage), create vertical lines, skim the middle, show off legs.

| Element | Do | Avoid |
|---|---|---|
| Necklines | V-neck, plunging, scoop, Sabrina — open up the chest | High halters, high crew, anything that closes the neckline |
| Waist | Empire (seam just under bust) or soft wrap; let fabric glide, not grip | Tight waistbands that cut into the middle, clingy jersey at the belly |
| Silhouette | Vertical lines, long open layers (longline cardigan/blazer), monochrome column | Boxy cropped tops, bulky belts at the waist |
| Bottoms | Straight-leg or bootcut; high-waisted trousers to elongate and support | Skinny jeans that emphasise the top-heavy balance |
| Dresses | Empire and A-line (flows out from under bust), wrap | Bodycon at the midsection |
| Best assets | Legs and décolletage — feature them | — |

#### Rectangle / Straight — shoulders, waist, and hips similar in width; little waist definition
**Conventional goal:** *create* the appearance of a waist and curves; break up the straight line.

| Element | Do | Avoid |
|---|---|---|
| Waist creation | Belts, peplum tops, fitted/cinched blazers, ruched or wrap waists, princess seams | Straight shift shapes that reinforce the column (unless that's the desired minimalist look) |
| Add curve | Targeted volume at hips — A-line and full skirts, peplum "hip flare," colour-blocking that narrows the waist | — |
| Bottoms | High-waisted trousers/skirts to mark the narrowest point and lengthen legs | — |
| Dresses | Wrap, fit-and-flare, A-line, empire; details like curved seams, gathers, soft ruching | — |
| Tops | Details that add dimension (ruffles, texture, layering) | Very boxy, straight-cut tops if a curvier look is wanted |

#### Inverted Triangle — shoulders/bust wider than hips
**Conventional goal:** balance a strong upper body by adding visual weight/volume below the waist and softening the shoulder line.

| Element | Do | Avoid |
|---|---|---|
| Necklines | Deep, narrow — scoop, U, V (draw the eye down and in) | Wide/low — bateau, square, off-shoulder, Sabrina (they widen the shoulder further) |
| Shoulders/sleeves | Soft, unstructured, raglan/set-in without padding | Shoulder pads, puff sleeves, heavy epaulettes, boat necks |
| Bottoms | Add volume/interest below — wide-leg, flares, pleated and full/A-line skirts, prints and lighter colours on the bottom | Skinny bottoms that exaggerate the top-heavy balance |
| Tops | Simple, darker, uncluttered | Bold detail/pattern across the chest and shoulders |
| Waist | Define it to re-introduce a curve | — |

Sources: [The Concept Wardrobe – Hourglass](https://theconceptwardrobe.com/build-a-wardrobe/hourglass-body-shape), [Concept Wardrobe – Inverted triangle](https://theconceptwardrobe.com/build-a-wardrobe/inverted-triangle-body-shape), [Concept Wardrobe – Pear](https://theconceptwardrobe.com/build-a-wardrobe/pear-body-shape), [Concept Wardrobe – Apple](https://theconceptwardrobe.com/build-a-wardrobe/apple-body-shape), [Concept Wardrobe – Rectangle](https://theconceptwardrobe.com/build-a-wardrobe/how-to-dress-the-rectangle-body-shape), [Sumissura – Inverted triangle](https://www.sumissura.com/en-us/blog/inverted-triangle-body-shape), [Sumissura – Apple body shape](https://www.sumissura.com/en-us/blog/apple-body-shape), [Sumissura – Rectangle body shape](https://www.sumissura.com/en-us/blog/rectangle-body-shape), [Stitch Fix – Triangle body shape](https://www.stitchfix.com/women/blog/style-guide/how-to-dress-a-triangle-body-shape/), [Macy's – Dresses for apple shapes](https://www.macys.com/s/guides/best-dress-for-apple-shaped-women/).

### 2.2 Universal proportion principles (transcend shape)

These apply to everyone, regardless of shape:

- **Rule of thirds.** Divide the vertical outfit unevenly — roughly 1/3 : 2/3 rather than 1/2 : 1/2. The classic version is a cropped or tucked top (upper third) over high-waisted bottoms (lower two-thirds). Odd/asymmetric proportions are more visually engaging than a body cut in half. Belting a long dress to create a 1/3–2/3 break beats letting it hang as one column.
- **Define the waist (or deliberately don't).** A marked waist is the single most reliable way to create shape; a straight column is the deliberate minimalist alternative. Both are valid — it's a choice, not a hierarchy.
- **High waist = longer legs.** A high-rise shifts the visual waistline up and lengthens the leg line automatically. This is the highest-leverage lengthening move.
- **Vertical lines lengthen and slim:** long open layers, monochrome columns, centre-front plackets, narrow-column trousers/skirts, V-necks.
- **Where hems hit matters.** A hem lands the eye at whatever width it crosses. End tops and jackets at a *narrow* point (waist, high hip) rather than at the widest hip. Skirt/dress hems: end at a slimmer part of the leg (above/below the knee, mid-calf, ankle) rather than the widest part of the calf.
- **Balance volume: fitted-with-loose.** Pair a voluminous piece with a fitted one (wide-leg trouser + fitted top; oversized knit + slim bottom). Loose-on-loose reads shapeless; tight-on-tight reads under-styled for many contexts.
- **Eliminate unwanted horizontal breaks** if the goal is height/length — contrasting waistbands, hems at the widest point, and clashing belts all "stop" the eye and reset apparent height.

Sources: [Jo-Lynne Shane – Rule of thirds in fashion](https://jolynneshane.com/fashion-tips-understanding-the-rule-of-thirds.html), [Fabulous After 40 – Rule of thirds](https://www.fabulousafter40.com/how-to-apply-the-fashion-rule-of-thirds-to-your-outfits/), [EILEEN FISHER – Three easy proportions](https://www.eileenfisher.com/a-sustainable-life/journal/a-simple-wardrobe/three-easy-proportions.html).

### 2.3 Height and scale

Scale is about matching the *size of prints, details, and accessories* to the *size of the frame*, and managing apparent height.

- **Petite (roughly under 5'4"):** the job is proportion management, not restriction. Keep the vertical line unbroken; sit the waist high; get hems to the right spot; keep jackets short (cropped/waist-length reveal leg and keep the waist visible — a mid-thigh jacket cuts the body at its widest and shortens the frame). Scale prints and accessories *down*: finer/tighter-repeat prints, smaller collars, daintier jewellery, narrower belts, smaller bags, more delicate eyewear. A big bold print *can* work — keep it to one piece and let the rest stay quiet. Minimise hard horizontal breaks.
- **Tall:** can carry larger-scale prints, bigger accessories, wider belts, longer jackets, and dramatic proportions that would overwhelm a petite frame. Horizontal breaks, contrasting waistbands, midi lengths, and colour-blocking are *tools*, not hazards — they can visually manage height. Can wear maxi lengths and column dressing with authority.
- **General scale rule:** accessory and print scale should echo bone structure/frame — a fine-boned person in chunky jewellery (or a large-framed person in tiny jewellery) reads as "off." Match the mass.

Sources: [Sumissura – Style tips for shorter women](https://www.sumissura.com/en-us/blog/style-tips-for-small-women), [Petite Studio – How to dress to look taller](https://www.petitestudionyc.com/blogs/lifestyle/i-m-5-3-here-s-how-to-dress-to-look-taller-effortlessly), [PixieGirl – Petite guide to proportions](https://www.pixiegirl.com/blog/post/the-petite-guide-how-to-dress-for-your-proportions-1962).

---

## Part 3 — The Stylist's Craft

### 3.1 The client intake

Before dressing anyone, a stylist runs a discovery interview. The essential inputs:

- **Lifestyle & routine.** How do the days actually split — work / parenting / social / gym / travel? (The wardrobe must be *practical* for real daily activities. A common framing: "what does a typical weekday and a typical Saturday look like?")
- **Profession & how they want to be perceived at work.** Reveals formality baseline and the image they're dressing toward.
- **What they want to *feel*.** Confident, powerful, approachable, sexy, invisible, put-together, creative. This drives colour psychology and silhouette drama.
- **Comfort & no-go zones.** Body areas they won't reveal; fabrics/fits they hate; heel height limits; anything non-negotiable.
- **Colours they love and hate.** Both are constraints; a colour they refuse to wear is a hard exclude regardless of what "suits" them.
- **Style inspiration / references.** Who they admire; their Pinterest/saved images (their aspirational aesthetic — see §3.9).
- **Current pain points.** What's frustrating now; what they reach for on repeat; when they last felt great in an outfit.
- **Budget & investment appetite.** Per-piece ceiling; splurge-vs-save priorities.
- **Upcoming events / specific needs.** Named occasions to dress for; gaps in the wardrobe.
- **Practical constraints.** Climate, commute, dress code at work, laundry/care tolerance.

Sources: [Visualist – 10 questions stylists should ask](https://www.visualistapp.com/blog/personal-stylist-client-questionnaire-identifying-painpoints), [Corporate Fashionista – Virtual styling client questionnaire (PDF)](https://www.corporatefashionista.com/vssqform.pdf), [Forever Styled – New client style survey](https://foreverstyled.com/contact/style-survey/).

### 3.2 Dress codes decoded

From most casual to most formal. "Relaxed but intentional" is the through-line — no code means "anything goes."

| Code | Women — pieces | Men — pieces | Context |
|---|---|---|---|
| **Casual** | Clean well-fitted jeans, tee/knit, presentable flats/trainers, simple dress | Dark clean jeans/chinos, tee or casual shirt, trainers/loafers | Everyday, weekend |
| **Smart casual** | Blazer + dark jeans/chinos or midi dress/skirt, loafers or block heels, elevated knit | Blazer or smart jacket, chinos or dark denim, shirt or fine knit, loafers | Polished *social* setting |
| **Business casual** | Blouse + tailored trousers/skirt, sheath dress, blazer optional, low/block heels or flats | Blazer/sports coat + collared shirt (tie optional), chinos or trousers, leather shoes | Modern workplace; polished, no full suit needed |
| **Business formal** | Tailored trouser- or skirt-suit, or formal dress; closed heels; understated jewellery | Dark suit + tie, dress shirt, formal leather shoes | Boardrooms, court, executive, client-facing — the corporate equivalent of black tie |
| **Cocktail** | Knee-length/midi dress or dressy separates; heels; statement accessory | Dark suit, tie optional, dress shoes | Weddings, holiday parties, fundraisers, galleries — the most common "dressy" code |
| **Black tie** | Floor-length gown or elegant dressy midi/formal separates; fine jewellery; evening clutch | Tuxedo, black bow tie, patent/formal shoes | Formal evenings, weddings, galas |
| **White tie** | Formal full-length ball gown; elevated jewellery; gloves optional | Tailcoat, white bow tie, white waistcoat, wing collar | The most formal code — state, royal, ceremonial |
| **Festive** | Cocktail base + seasonal sparkle/velvet/rich colour | Dark suit + festive accessory (velvet blazer, bold tie) | Holiday parties — cocktail with permission to shine |

Sources: [Emily Post – Attire guide: dress codes casual to white tie](https://emilypost.com/advice/attire-guide-dress-codes-from-casual-to-white-tie), [All That's Stylist – Dress code guide](https://service.allthatsstylist.com/en/glossary/dress-code-guide), [ARC Events – Black tie, white tie, cocktail](https://www.arc.events/journal/the-only-things-you-need-to-know-to-interpret-a-dress-code).

### 3.3 Fit — the #1 rule, and tailoring priorities

**Fit outranks everything** — brand, price, trend, colour. A well-fitting inexpensive garment beats an expensive one worn straight off the peg; a modest budget plus a tailor almost always beats a large budget without one. Fit is the layer that decides whether a garment "works" at all; everything else is secondary.

Tailoring priorities (highest return first):
1. **Get the shoulders right on structured pieces first** — the shoulder seam is the hardest and most expensive thing to alter, so *buy* for the shoulders and tailor the rest.
2. **Nip the waist / take in the sides** of jackets, shirts, and dresses to follow the body.
3. **Hem trousers, skirts, and sleeves to the correct length** — the cheapest, highest-impact alteration (correct break on trousers; sleeve ending at the wrist bone).
4. **Taper trouser legs / sleeves** where a slimmer line is wanted.
5. Rule of thumb: **a $20–30 alteration on a $100 garment outperforms a $500 garment worn unaltered.** Budget for tailoring as part of the cost of the piece.

Sources: [Aesthetics Game – Fit over fashion](https://aesthetics-game.app/blog/four-fs/fit-over-fashion), [Sartoria Litrico – Golden rules of tailoring](https://www.sartorialitrico.it/en/fashion/the-5-golden-rules-of-haute-tailoring-for-the-modern-man-how-to-choose-the-perfect-suit/), [Cedar & Lily – Tailoring for women](https://cedarandlilyclothier.com/blogs/blog/tailoring-for-women).

### 3.4 Fabric & texture

- **Weight ↔ season.** Knits, wool, tweed, flannel, corduroy, velvet read as autumn/winter; linen, cotton lawn, silk, chambray read as spring/summer. Match fabric weight to temperature both for comfort and for "rightness."
- **Drape** is how a fabric hangs — from fluid (silk, jersey, rayon — skims and flows) to structured (denim, tweed, taffeta — holds a shape). Fluid drapes skim the body and suit soft/curvy looks; structured fabrics build architecture and hold a silhouette. Note: humidity makes fabric heavier/clingier, cold stiffens it.
- **Mixing textures** adds depth to a limited (especially neutral) palette. Rules:
  - **Balance heavy with light** — pair a chunky/textured piece (tweed, cable knit, leather) with something smooth/fluid (silk, satin, fine cotton).
  - **Anchor texture play with a tight colour palette** — the fewer the colours, the more freely you can mix textures.
  - **Cap it at ~3 textural elements** per outfit unless very deliberate.
  - **Reliable pairings:** leather + silk (polished edge), silk + lace (refined/feminine), knit + denim (casual), wool + cotton (everyday).
  - **Accessories are the easiest way to add texture** (a textured bag, scarf, or knit) without rebuilding the outfit.

Sources: [MasterClass – Mixing and matching textures](https://www.masterclass.com/articles/how-to-create-outfits-by-mixing-and-matching-clothing-textures), [Sewing Trip – Fabric drape and texture guide](https://sewingtrip.com/fabric-drape-and-texture-guide/), [Argent – Masterclass on mixing textures](https://argentwork.com/blogs/the-outfit-pitch/a-masterclass-on-mixing-textures).

### 3.5 Pattern mixing

Four safe rules let almost anyone mix prints without clashing:
1. **Vary the scale.** Pair a small-scale print with a large-scale one; the smaller print then behaves almost like a neutral. Two same-scale prints compete and read as chaos.
2. **Bridge with a shared colour.** The two prints should share at least one colour — that common thread is what makes disparate patterns look intentional.
3. **Use a neutral buffer.** A neutral piece (tee, blazer, trouser) or neutral ground in one print gives the eye a place to rest and physically separates busy prints.
4. **Ratio ~70/30.** Let one print dominate (~70% of the look) and the other accent (~30%) rather than a 50/50 fight.

Beginner path: start from classic, simple prints (stripes, polka dots, small florals) as the "foundation," then layer one bolder print on top.

Sources: [MasterClass – How to mix prints and patterns](https://www.masterclass.com/articles/how-to-mix-prints-and-patterns-to-create-a-stylish-outfit), [The Wardrobe Consultant – A stylist's recipe for mixing patterns](https://www.thewardrobeconsultant.com/blog/a-stylists-recipe-for-mixing-patterns-like-a-pro), [Articles of Style – Simple guide to pattern-mixing](https://articlesofstyle.com/blogs/news/a-simple-guide-to-patternmixing).

### 3.6 Capsule wardrobe, cost-per-wear, versatility

- **Capsule principle:** maximum outfits from a minimum of pieces; every item must mix and match with the rest. Each piece earns its place by working in several looks.
- **Combinatorics of versatility:** outfits ≈ **(tops × bottoms + dresses) × (layers + 1) × shoes.** A small, cohesive set explodes into many outfits *only if the colours coordinate* — hence a tight palette (neutrals + 1–2 accents) is the enabler.
- **Cost-per-wear (CPW):** the true value metric.
  - Basic: **CPW = price ÷ estimated total wears.**
  - Better: **CPW = (price + lifetime care cost − resale value) ÷ estimated total wears.**
  - Benchmark: **under ~$2/wear = an efficient, well-used purchase.** A pricey but frequently worn coat can undercut a cheap one that rarely leaves the closet.
- **Buying rule that follows:** a versatile piece worn across many outfits beats a cheaper piece that seldom gets worn. Invest in the versatile, durable, high-frequency items (outerwear, shoes, denim, tailoring); economise on the low-frequency/trend items.

Sources: [Go Elm & Co – Capsule wardrobe & CPW formula](https://goelmbrands.com/blogs/news/mens-capsule-wardrobe-essentials-2026), [AOL / Real Simple – Cost-per-wear math](https://www.aol.com/articles/capsule-wardrobe-guide-spending-less-104729967.html), [Closet Capsule Calculator](https://miniwebtool.com/closet-capsule-calculator/).

### 3.7 Accessorising

- **One focal point rule.** One item is the star; the rest support it. Bold statement earrings → keep the necklace delicate or skip it. A statement necklace → understated earrings. Never let two accessories fight for the face.
- **Metal choice** follows undertone (§1.3): warm → gold, cool → silver, neutral → either/mix. Keep metals consistent within a look for polish (matching metals reads most cohesive); intentional mixing is fine for neutral undertones.
- **Necklace length ↔ neckline** (echo or fill the neckline):

  | Neckline | Best necklace | Length |
  |---|---|---|
  | Crew / high / turtleneck | Long pendant or layered longer chains | 30–36"+ |
  | V-neck | Pendant/Y that mirrors the V | ~18" (princess) |
  | Scoop / round | Curved collar or princess that follows the curve | 16–18" |
  | Boat / bateau / high | Short choker or collar; or long over the fabric | 14–16" or 30"+ |
  | Strapless / sweetheart | Choker or short statement to fill the open space | 16–24" |
  | Collared shirt | Short pendant inside the collar, or long over | 16–18" or 30"+ |

  *(Standard lengths: collar 12–14", choker 14–16", princess 17–19", matinee 20–24", opera 28–36", rope 36"+.)* For **layering**, stack ~16" + 18" + 20–22" with ≥2" between chains.
- **Belts for proportion.** A belt marks the waist and sets the rule-of-thirds break; match the belt to the effect wanted — a narrow tonal belt lengthens, a contrasting/wide belt creates a strong horizontal (good for tall, cautious for petite).
- **Bag & shoe logic.** Shoes are the single fastest way to change an outfit's perceived formality (flats → heels moves casual → dressy). Scale the bag to the frame (§2.3) and to the occasion (structured/small = dressier; slouchy/large = casual). Keep bag and shoe within the same broad formality band.

Sources: [Atolea – Necklines and necklaces pairing guide](https://atoleajewelry.com/blogs/waterproof-jewelry-blog/necklines-and-necklaces), [Statement Collective – Necklace lengths guide](https://www.statementcollective.com/blogs/whats-good/necklace-lengths), [Brilliant Earth – Necklace length guide](https://www.brilliantearth.com/news/necklace-length/), [The Wardrobe Consultant – Necklace to neckline](https://www.thewardrobeconsultant.com/blog/necklace-pairings-101-how-to-match-your-necklace-to-your-neckline).

### 3.8 Occasion, weather, layering, day-to-night

- **Occasion & weather first.** Formality target (from the dress code / activity) and temperature/precipitation set the hard constraints before aesthetics enter. Fabric weight and coverage follow the forecast; footwear follows both weather and formality.
- **Layering logic.** Build outfits that can be *deconstructed* as conditions or context change. A structured blazer over a dressier shell + tailored trouser is "boardroom" with the blazer on and "cocktail" with it off. Layers also solve variable temperature (office AC → evening outdoors).
- **Day-to-night, by leverage (highest first):**
  1. **Change the shoes** — flats → heels is the fastest formality jump.
  2. **Remove a layer** — lose the blazer/cardigan to reveal a dressier or shimmier shell.
  3. **Swap the bag** — work tote → clutch.
  4. **Escalate the jewellery** — simple by day, add statement earrings/stacked pieces by night.
  5. **Add a bold lip / stronger colour** to finish.
  Best day-to-night base pieces: a simple dress (LBD), a jumpsuit, a shirtdress, a silk/charmeuse blouse, a good skirt — pieces neutral enough to be recontextualised by accessories alone.

Sources: [Emily Westenberger – Transition day to night](https://emilywestenberger.com/blogs/welcome-to-my-world/how-to-transition-your-outfit-from-day-to-night), [The Noli Shop – Day-to-night without changing](https://www.thenolishop.com/blogs/noli-blog/how-to-transition-outfits-day-to-night), [Hayden Hill – Versatile day to night outfits](https://hayden-hill.com/blogs/journal/day-to-night-outfits).

### 3.9 Style archetypes, and reconciling taste with reality

Common archetypes (most people are a **blend of two**):

| Archetype | Ethos | Signature pieces / palette |
|---|---|---|
| **Classic** | Polish, structure, longevity over trend | Navy/beige/white/black; blazer, white shirt, straight trousers, loafers/pumps |
| **Minimalist** | Clean lines, no clutter; fit & fabric over decoration | Monochrome neutrals; structured coat, wide-leg trouser, plain tee, sleek trainers |
| **Romantic** | Softness, delicate detail, grace | Blush/cream; flowing fabrics, lace, ruffles, soft prints |
| **Bohemian** | Creative, easy, layered, eclectic | Warm neutrals/rust/olive; maxi dress, kimono, layered jewellery, ankle boots |
| **Edgy** | Bold shapes, dark tones, attitude | Black/charcoal; leather jacket, ripped denim, combat boots, statement belt |
| **Dramatic** | Statement silhouettes, strong colour, impact | Bold, sculptural, high-contrast |
| **Natural** | Comfortable, relaxed, fuss-free | Casual, tactile, low-maintenance |

Coherent common blends: classic-minimalist, romantic-bohemian, edgy-classic.

**Reconciling a client's aspirational aesthetic (their Pinterest) with body and lifestyle.** The archetype defines the *vocabulary* (colours, shapes, mood); body-shape and proportion rules define *which cut of that vocabulary* actually flatters; lifestyle/occasion defines *what's appropriate and practical*. A stylist keeps the mood the client loves but selects the version of it that works — e.g. a client who pins flowing bohemian maxis but is petite gets the *bohemian mood* delivered in petite-scaled prints and a high waist so it doesn't swamp her. The aesthetic is honoured; the execution is adjusted.

Sources: [Bits & Bangles – Style archetypes decoded](https://www.bitsandbangles.com/blogs/news/your-style-archetype-decoded-and-how-to-dress-for-it), [Maki Fashion – Style archetypes guide](https://makifashion.com/style-archetypes/), [Sterling Style Academy – Fashion vs style archetype](https://sterlingstyleacademy.com/fashion-archetype-and-style-archetype-a-guide-for-personal-stylists/).

---

## Part 4 — App Engine Rules (the codeable spec)

This section translates Parts 1–3 into deterministic heuristics for a recommendation engine that has (a) a wardrobe of tagged garments and (b) a daily context. It assumes each garment carries structured tags and each user carries an onboarding profile.

### 4.0 Data model (assumed tags)

**Garment tags**
- `category`: top | bottom | dress | outer | shoe | bag | jewellery | belt | accessory
- `subtype`: e.g. blazer, knit, tee, blouse, wide-leg, straight, skinny, a-line, sheath, wrap, bootcut, midi-skirt, trench, etc.
- `formality`: integer 1–5 (1 casual … 5 white tie) — see 4.1
- `warmth`: 1 (hot-weather, e.g. linen/short) … 5 (heavy, e.g. wool coat)
- `fabric`, `drape`: fluid | structured
- `color_primary` (+ optional `color_secondary`): mapped to a hue family + `neutral` boolean
- `color_temperature`: warm | cool | neutral
- `value`: 1 (very light) … 5 (very dark)  — for contrast math
- `pattern`: solid | small-scale | large-scale, + `pattern_colors[]`
- `neckline` (tops/dresses): v | scoop | crew | boat | square | halter | sweetheart | turtleneck | off-shoulder
- `rise` (bottoms): low | mid | high
- `leg` (bottoms): skinny | straight | bootcut | wide | flare
- `length` (tops/jackets/skirts/dresses): crop | waist | hip | mid-thigh | knee | midi | maxi
- `shoulder_detail` (tops/outer): none | padded | puff | structured
- `metal` (jewellery): gold | silver | rose | mixed
- `scale` (accessory/print): fine | medium | bold
- `waist_definition` (dress/top): fitted | belted | empire | wrap | straight/boxy

**User profile (from onboarding)**
- `body_shape`: hourglass | pear | apple | rectangle | inverted_triangle
- `undertone`: warm | cool | neutral
- `color_season` (optional, soft): one of 4/12 seasons
- `contrast_level`: high | medium | low
- `height_scale`: petite | average | tall
- `style_archetype_primary`, `style_archetype_secondary`
- `loved_colors[]`, `hated_colors[]` (hated = hard exclude)
- `no_go_zones[]` (e.g. "no bare arms", "no above-knee", "no heels over X")
- `emphasis_prefs`: which areas the user *wants* to feature or downplay (lets them invert §2 defaults)

### 4.1 Formality scale (single source of truth)

| Level | Name | Example anchor pieces |
|---|---|---|
| 1 | Casual | jeans, tee, trainers |
| 2 | Smart casual | dark denim/chinos + blazer or midi dress, loafers |
| 3 | Business casual / cocktail-lite | tailored trousers + blouse, sheath dress, low heel |
| 4 | Business formal / cocktail | suit, cocktail dress, heels |
| 5 | Black tie → white tie | gown, tux/tailcoat |

Every recommendation computes a **target formality** from context (4.3) and only selects garments whose `formality` is within ±1 of target (never mix a level-1 and level-4 item in one look unless an explicit "high-low" style flag is set).

### 4.2 Inputs to collect for "dress me for my day"

**Daily context (per-request):**
1. `weather_temp` (°C/°F) and `feels_like`
2. `precipitation` (none | rain | snow)
3. `activity` / occasion (e.g. office, client meeting, casual day, date, wedding-cocktail, gym-to-brunch)
4. `dress_code` if known (maps directly to formality)
5. `feeling_goal` (confident | powerful | approachable | calm | attractive | low-key | creative)
6. `duration_day_to_night` (single-context | needs-to-transition)
7. `movement_level` (lots of walking/standing | seated | minimal)
8. `effort_level` (throw-on | standard | full-effort)
9. `anchor_piece` (optional: a specific garment the user wants to build around)

**Static (from profile):** body_shape, undertone, color_season, contrast_level, height_scale, style_archetype, loved/hated colours, no-go zones, emphasis prefs.

### 4.3 Input → constraint mapping

| Input | Sets constraint on |
|---|---|
| `dress_code` / `activity` | **Target formality** (4.1). Activity without a code → infer: office=3, client/exec=4, casual=1–2, date=3, wedding=4, gym-adjacent=1. |
| `feeling_goal` | **Statement-colour selection** via colour psychology (§1.6): powerful→red/black; calm/trust→blue/green; approachable→soft warm tones; low-key→tonal neutrals; attractive→one bold focal colour + fitted silhouette. |
| `weather_temp` | **Garment `warmth`.** Map temp bands → allowed warmth range and mandatory/forbidden layers. Cold → require outer + warmth≥4; hot → warmth≤2, forbid heavy layers. |
| `precipitation` | **Footwear + outer.** rain → waterproof/closed shoe, exclude suede/open; add trench/raincoat. snow → boots. |
| `movement_level` | **Footwear comfort + fit ease.** lots of walking → cap heel height, allow trainers/flats even at formality 2–3; seated formal event → heels OK. |
| `duration_day_to_night` | **Layerability.** needs-to-transition → pick a base at the *lower* formality with a removable layer and an accessory upgrade path (§3.8). |
| `effort_level` | **Number of pieces / complexity.** throw-on → prefer one-piece (dress/jumpsuit) + 2 accessories; full-effort → allow layering, pattern mixing, statement accessories. |
| `anchor_piece` | **Seed.** Lock it in; build harmony/formality/warmth around it. |
| `body_shape` | **Silhouette rules** (4.5). |
| `undertone` | **Metal** (hard) + **colour temperature bias** (soft). |
| `color_season` / `loved`/`hated` | **Palette bias** (soft) / **hard exclude** (hated). |
| `contrast_level` | **Value spread** of the outfit, esp. at the neckline (4.4). |
| `height_scale` | **Print/accessory scale + jacket length + horizontal breaks** (§2.3). |
| `style_archetype` | **Aesthetic vocabulary** — subtype/fabric/palette preference weighting (4.6). |

### 4.4 Colour-pairing rules (engine-applicable)

Apply in order:

1. **Hard exclude** any garment whose colour ∈ `hated_colors`.
2. **Neutral-with-anything.** A garment tagged `neutral` may pair with any other garment. An outfit of all-neutrals is always colour-valid (rely on texture/value for interest).
3. **One-statement-colour rule (default).** At most **one** non-neutral hue family per outfit unless a harmony rule (below) is explicitly invoked. Everything else must be neutral. This is the safe default and the go-to for `effort_level = throw-on`.
4. **If two+ colours are used, they must form a named harmony:**
   - *Analogous* — hue families adjacent on the wheel (safe; default for multi-colour).
   - *Complementary / split-complementary* — opposite (or near-opposite) families; use 70/30, the second colour as accent (bolder, higher-energy — gate behind `effort_level ≥ standard`).
   - *Monochromatic* — same family, different `value` (always safe; also serves low-contrast users well).
   - *Triadic* — only if `effort_level = full-effort` and `style_archetype ∈ {dramatic, bohemian, edgy}`; one dominant + two accents.
5. **Undertone → metal (hard):** jewellery `metal` must match `undertone` (warm→gold/rose, cool→silver, neutral→any). Keep metals consistent within a look unless undertone=neutral.
6. **Undertone → colour temperature (soft bias, not exclude):** prefer garments whose `color_temperature` matches undertone; if `color_season` present, up-weight in-palette hues. Never hard-exclude on season alone (it is subjective — §1.4).
7. **Contrast level → value spread:**
   - `high` → allow/prefer a large `value` gap between pieces (e.g. value 1 top + value 5 bottom); ensure at least *some* value contrast **at the neckline** (top vs. face framing).
   - `low` → keep pieces within ~1–2 value steps (tonal); **avoid** sharp value jumps at the neckline.
   - `medium` → moderate spread.
8. **3-colour ceiling.** Count non-neutral colours; if >3, reject or demote the outfit.

### 4.5 Body-shape → silhouette rules (if/then on tags)

Rules are keyed on garment tags and expressed as *prefer* (up-weight) / *avoid* (down-weight or exclude). All are overridable by `emphasis_prefs` (a user who wants the opposite flips the rule).

**Universal proportion rules (apply to all shapes):**
- Prefer outfits producing a **1/3 : 2/3 vertical split** (e.g. `length=crop|waist` top tucked into `rise=high` bottom).
- Prefer `rise=high` bottoms (leg-lengthening) unless archetype/preference says otherwise.
- Prefer waist definition (`waist_definition ∈ {fitted, belted, wrap, empire}`) *when a shaped look is the goal*.
- Enforce **fitted-with-loose**: if one piece is `drape=structured/volume` (wide/full), pair with a fitted counterpart; down-weight loose+loose.
- Hem/length: avoid ending a top/jacket at the widest body point for the shape.

**Hourglass**
- Prefer: `waist_definition ∈ {fitted, belted, wrap}`; `subtype ∈ {wrap, sheath, fit-and-flare}`; `neckline ∈ {scoop, v, jewel, oval}`; `leg ∈ {straight, bootcut}`; `rise ∈ {mid, high}`.
- Avoid: `waist_definition = straight/boxy`; oversized/shapeless; heavy `shoulder_detail` (unbalances).

**Pear / Triangle**
- Prefer (top): `neckline ∈ {boat, square, off-shoulder}`; `shoulder_detail ∈ {puff, structured, padded}`; bright/patterned tops; `length ∈ {waist, hip}` (end at/above hip).
- Prefer (bottom): darker/neutral colour; `subtype ∈ {a-line, wrap}`; `leg ∈ {bootcut, straight}`; `rise=high`.
- Avoid: tops ending at widest hip; `leg=skinny` in thin cling fabric; low rise; bold pattern/detail on the bottom.

**Apple / Round**
- Prefer: `neckline ∈ {v, scoop, sweetheart}`; `waist_definition ∈ {empire, wrap}`; vertical/open long layers (`length=maxi` cardigan/blazer, open); `leg ∈ {straight, bootcut}`, `rise=high`; fluid drape that skims.
- Avoid: tight waistbands/belts at the natural waist; `neckline ∈ {turtleneck, high-halter}`; clingy jersey at midsection; `leg=skinny` with a fitted top.

**Rectangle / Straight**
- Prefer: waist-creating pieces — `waist_definition ∈ {belted, wrap, peplum, fitted}`; `subtype ∈ {wrap, fit-and-flare, a-line, peplum}`; details adding hip/waist dimension (ruffle, ruche, princess seam); `rise=high`.
- Avoid: straight boxy shift shapes *when curves are the goal* (fine if archetype=minimalist and a column is wanted).

**Inverted Triangle**
- Prefer: `neckline ∈ {v, scoop, u}` (deep/narrow); soft/unstructured shoulders; volume on the bottom — `leg ∈ {wide, flare}`, `subtype ∈ {a-line, pleated, full}` skirts, lighter colour/pattern on bottom; define the waist.
- Avoid: `neckline ∈ {boat, square, off-shoulder}`; `shoulder_detail ∈ {padded, puff}`; `leg=skinny`; bold pattern across the chest.

**Height scale (modifiers on top of shape):**
- `petite` → prefer `scale=fine` prints/accessories; prefer `length ∈ {crop, waist}` jackets; avoid strong contrasting horizontal breaks (contrasting waistband/belt, hem at widest hip); strongly prefer `rise=high` + tuck; monochrome column up-weighted.
- `tall` → allow `scale=bold` prints/accessories, wider belts, `length ∈ {mid-thigh, maxi}`, deliberate horizontal breaks/colour-blocking permitted.

### 4.6 Reconciling Pinterest aesthetic vs. body-shape vs. occasion (priority order)

When rules conflict, resolve in this strict order (highest wins):

1. **Hard constraints — never violated:** `hated_colors`, `no_go_zones`, weather safety (warmth/precip), and **occasion formality** (showing up in the wrong formality band is the one truly costly error). If the wardrobe can't meet formality, flag a gap rather than downgrade.
2. **Undertone→metal** and **contrast neckline** rules (cheap to satisfy, high visual payoff).
3. **Body-shape silhouette defaults** — *unless* the user's `emphasis_prefs` invert them. These shape *which cut* of the desired aesthetic is chosen.
4. **Style archetype (the Pinterest aesthetic)** — governs the *vocabulary*: which subtypes, fabrics, palette mood, and level of drama to prefer *among the options that already satisfy 1–3*. The engine keeps the mood the user loves and picks the version of it that fits their body, the weather, and the occasion.
5. **Colour-harmony niceties and rule-of-thirds polish** — tie-breakers among otherwise-valid outfits.

Practical statement of the reconciliation: **The aesthetic decides the vibe; the body rules decide the fit of that vibe; the occasion and weather decide what's allowed at all.** So a bohemian-leaning petite user going to a cocktail event gets a *cocktail-formality (level 4), petite-scaled, high-waisted* outfit rendered in *bohemian vocabulary* (flowing fabric, warm palette, layered delicate jewellery within the one-focal-point rule) — every layer of priority satisfied without abandoning her taste.

### 4.7 Recommendation algorithm (putting it together)

```
1. Compute target_formality from dress_code/activity.               (§4.1, §4.3)
2. Compute warmth_range + footwear/outer constraints from weather.  (§4.3)
3. Candidate set = garments where
      formality ∈ [target-1, target+1]
      AND warmth ∈ warmth_range
      AND color ∉ hated_colors
      AND not violating no_go_zones.
4. If anchor_piece given, force-include it and constrain the rest to
   match its formality/warmth/colour harmony.
5. Choose a statement colour from feeling_goal (colour psychology),
   or default to neutral base + one loved accent colour.            (§1.6, §4.4)
6. Build silhouette:
      - pick base (dress OR top+bottom) honouring body_shape rules   (§4.5)
        and the 1/3–2/3 + fitted-with-loose proportion rules.
      - apply height_scale modifiers.
7. Apply colour-pairing rules (neutral-with-anything, one-statement,
   harmony type, 3-colour ceiling) and contrast-level value spread.  (§4.4)
8. Add footwear (weather + movement + formality) and one focal
   accessory set (metal = undertone; one-focal-point rule;
   necklace length = neckline).                                      (§3.7, §4.4)
9. If duration = needs-to-transition, ensure a removable layer and a
   day→night accessory upgrade exists.                               (§3.8)
10. Rank surviving outfits by: archetype fit → harmony quality →
    rule-of-thirds/proportion polish → CPW/versatility.              (§4.6, §3.6)
11. Return top N with a one-line "why" per outfit (formality met,
    palette logic, shape logic) for transparency.
```

**Fit caveat the engine must surface, not compute:** the engine can pick the right *pieces*, but §3.3 (fit is #1) is a physical property it can't verify. Recommendations should carry a standing reminder that fit/tailoring outranks selection — a well-chosen but poorly fitting garment still fails.

---

## Sources

Colour theory & harmonies
- https://howtowearfashion.com/styling-tips/how-to-use-the-color-wheel-when-getting-dressed
- https://www.sessions.edu/color-calculator/
- https://www.melcofabrics.com.au/blogs/the-sewing-room/creating-a-color-harmonious-outfit-a-beginners-guide-to-color-harmonies
- https://blog.thepapermillstore.com/color-theory-color-harmonies/
- https://lookiero.co.uk/blog/colour-wheel-matching-clothes
- https://www.necesera.com/blogs/news/the-3-color-principle-in-fashion

Neutrals & palette building
- https://cedarandlilyclothier.com/blogs/blog/neutral-color-combinations
- https://www.shoppingonchampagne.com/blog/the-modern-way-to-wear-neutrals
- https://oglmove.com/blogs/knowledge/what-are-neutral-colors-in-clothing
- https://westwoodhart.com/blogs/westwood-hart/how-to-wear-navy-camel-grey-mens-fashion-guide

Undertone & metals
- https://delialangan.com/blogs/news/how-to-determine-your-undertone-for-gold-silver-or-rose-gold-jewelry
- https://www.palettehunt.com/guide/gold-vs-silver-jewelry-for-your-skin-tone
- https://www.vrai.com/journal/post/should-i-choose-silver-or-gold-jewelry-for-my-skin-tone
- https://global.louisfaglin.com/blogs/blog/matching-jewelry-to-your-skin-undertone-the-ultimate-guide

Seasonal colour analysis & its limits
- https://www.palettehunt.com/guide/12-season-color-analysis-explained
- https://color-analysis.app/blog/complete-guide-four-seasons-color-palette
- https://color-analysis.app/blog/is-seasonal-color-analysis-worth-it
- https://palettepath.com/color-analysis/12-season-color-analysis-explained/
- https://colorme.style/12-season-color-analysis/
- https://laurakcollins.com/the-truth-about-seasonal-color-analysis-perspective-of-a-hairstylist/

Contrast / value
- https://awellstyledlife.com/how-to-find-your-personal-contrast-level/
- https://insideoutstyleblog.com/2014/03/getting-your-value-contrast-levels-right.html
- https://signaturestylesystems.com/why-your-value-contrast-level-matters-more-than-your-season/
- https://www.palettehunt.com/guide/high-contrast-vs-low-contrast-coloring-explained

Colour psychology
- https://velvetimagelab.com/blogs/main/the-psychology-of-color-what-your-outfit-colors-say-about-you
- https://www.thegoodtrade.com/features/clothing-color-psychology/
- https://www.selvane.co/blogs/knowledge/the-psychology-of-color-in-fashion-how-hue-saturation-and-value-affect-perception

Body shapes
- https://theconceptwardrobe.com/build-a-wardrobe/hourglass-body-shape
- https://theconceptwardrobe.com/build-a-wardrobe/inverted-triangle-body-shape
- https://theconceptwardrobe.com/build-a-wardrobe/pear-body-shape
- https://theconceptwardrobe.com/build-a-wardrobe/apple-body-shape
- https://theconceptwardrobe.com/build-a-wardrobe/how-to-dress-the-rectangle-body-shape
- https://www.sumissura.com/en-us/blog/inverted-triangle-body-shape
- https://www.sumissura.com/en-us/blog/apple-body-shape
- https://www.sumissura.com/en-us/blog/rectangle-body-shape
- https://www.stitchfix.com/women/blog/style-guide/how-to-dress-a-triangle-body-shape/
- https://www.macys.com/s/guides/best-dress-for-apple-shaped-women/

Proportion & scale
- https://jolynneshane.com/fashion-tips-understanding-the-rule-of-thirds.html
- https://www.fabulousafter40.com/how-to-apply-the-fashion-rule-of-thirds-to-your-outfits/
- https://www.eileenfisher.com/a-sustainable-life/journal/a-simple-wardrobe/three-easy-proportions.html
- https://www.sumissura.com/en-us/blog/style-tips-for-small-women
- https://www.petitestudionyc.com/blogs/lifestyle/i-m-5-3-here-s-how-to-dress-to-look-taller-effortlessly
- https://www.pixiegirl.com/blog/post/the-petite-guide-how-to-dress-for-your-proportions-1962

Client intake
- https://www.visualistapp.com/blog/personal-stylist-client-questionnaire-identifying-painpoints
- https://www.corporatefashionista.com/vssqform.pdf
- https://foreverstyled.com/contact/style-survey/

Dress codes
- https://emilypost.com/advice/attire-guide-dress-codes-from-casual-to-white-tie
- https://service.allthatsstylist.com/en/glossary/dress-code-guide
- https://www.arc.events/journal/the-only-things-you-need-to-know-to-interpret-a-dress-code

Fit & tailoring
- https://aesthetics-game.app/blog/four-fs/fit-over-fashion
- https://www.sartorialitrico.it/en/fashion/the-5-golden-rules-of-haute-tailoring-for-the-modern-man-how-to-choose-the-perfect-suit/
- https://cedarandlilyclothier.com/blogs/blog/tailoring-for-women

Fabric & texture
- https://www.masterclass.com/articles/how-to-create-outfits-by-mixing-and-matching-clothing-textures
- https://sewingtrip.com/fabric-drape-and-texture-guide/
- https://argentwork.com/blogs/the-outfit-pitch/a-masterclass-on-mixing-textures

Pattern mixing
- https://www.masterclass.com/articles/how-to-mix-prints-and-patterns-to-create-a-stylish-outfit
- https://www.thewardrobeconsultant.com/blog/a-stylists-recipe-for-mixing-patterns-like-a-pro
- https://articlesofstyle.com/blogs/news/a-simple-guide-to-patternmixing

Capsule wardrobe & cost-per-wear
- https://goelmbrands.com/blogs/news/mens-capsule-wardrobe-essentials-2026
- https://www.aol.com/articles/capsule-wardrobe-guide-spending-less-104729967.html
- https://miniwebtool.com/closet-capsule-calculator/

Accessorising
- https://atoleajewelry.com/blogs/waterproof-jewelry-blog/necklines-and-necklaces
- https://www.statementcollective.com/blogs/whats-good/necklace-lengths
- https://www.brilliantearth.com/news/necklace-length/
- https://www.thewardrobeconsultant.com/blog/necklace-pairings-101-how-to-match-your-necklace-to-your-neckline

Day-to-night & layering
- https://emilywestenberger.com/blogs/welcome-to-my-world/how-to-transition-your-outfit-from-day-to-night
- https://www.thenolishop.com/blogs/noli-blog/how-to-transition-outfits-day-to-night
- https://hayden-hill.com/blogs/journal/day-to-night-outfits

Style archetypes
- https://www.bitsandbangles.com/blogs/news/your-style-archetype-decoded-and-how-to-dress-for-it
- https://makifashion.com/style-archetypes/
- https://sterlingstyleacademy.com/fashion-archetype-and-style-archetype-a-guide-for-personal-stylists/
</content>
</invoke>

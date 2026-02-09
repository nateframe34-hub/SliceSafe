# SliceSafe Pro — 25 Remixed Nano Banana Pro Prompts
### (Library Template -> SliceSafe Remix)

---

## TIER 1: HIGHEST PRIORITY

---

## #1: The "Neither Hand Goes Near The Blade" Safety Demo

**Based on template**: "Photorealistic Product Photography in a Forest Setting" (ecommerce-main-image.json)

**Content highlights extracted**:
- Safety demonstration showing hand placement far from blade
- Macro product clarity with environmental context
- Calm, controlled, confident mood

**Remixed prompt (English — use for generation)**:
```json
{
  "master_prompt": {
    "global_settings": {
      "resolution": "8K",
      "aspect_ratio": "4:5",
      "image_type": "photorealistic product demonstration photography",
      "detail_level": "ultra-high detail, macro clarity on hand placement and blade separation",
      "noise": "none",
      "artifacts": "none",
      "focus": "sharp subject, controlled depth of field f/2.8"
    },
    "subject": {
      "object_type": "standing upright mandoline vegetable slicer",
      "product_name": "SliceSafe Pro",
      "body_material": "premium light-blue molded housing",
      "blade": {
        "material": "stainless steel",
        "visibility": "clearly visible through transparent mid-section housing",
        "highlight": "single specular glint on blade edge"
      },
      "top_handle": {
        "detail": "ergonomic top-mounted handle with both hands gripping confidently",
        "hand_position": "thumbs on top, fingers curled around sides, relaxed knuckles, 8-10 inches above blade"
      },
      "food_hopper": {
        "content": "half-cucumber being pressed downward"
      },
      "collection_container": {
        "material": "clear transparent plastic",
        "content": "perfectly uniform cucumber rounds, 2mm thick, glistening vibrant green, cascading in"
      },
      "base": {
        "material": "rubberized dark-gray non-slip feet",
        "surface_contact": "firmly planted on countertop, zero wobble"
      },
      "thickness_dial": "visible on side of unit"
    },
    "environment": {
      "setting": "modern kitchen countertop",
      "base_surface": "white quartz with fine gray veining",
      "surroundings": [
        "warm white subway tile backsplash",
        "copper pendant light casting warm fill",
        "fresh herbs in small glass jar to the left"
      ],
      "background": "soft kitchen bokeh at f/2.8",
      "atmosphere": "calm, clean, effortless"
    },
    "lighting": {
      "type": "soft directional window light",
      "direction": "large window camera-right",
      "highlights": "gentle glint on stainless blade and glossy blue housing",
      "backlight": "subtle warm pendant glow from above",
      "shadows": "soft, natural"
    },
    "camera": {
      "angle": "30-degree downward, chest height",
      "lens_style": "editorial cooking photography, macro product clarity",
      "depth_of_field": "shallow f/2.8, background softened"
    },
    "color_palette": [
      "light blue (product)",
      "vibrant cucumber green",
      "warm white and gray (quartz)",
      "copper accent",
      "stainless steel silver"
    ],
    "global_constraints": {
      "no_text": true,
      "no_logos": true,
      "no_watermark": true,
      "hands_above_blade": "CRITICAL — both hands must be clearly on top handle, 8+ inches above blade line at all times"
    }
  }
}
```

**Modifications**:
- Replaced cosmetic bottle subject with SliceSafe Pro mandoline with all product-specific details
- Replaced forest environment with modern kitchen setting appropriate for product demo
- Added critical safety constraint (hands above blade) as a global constraint
- Kept the original's structured JSON approach, macro clarity, shallow DOF, and detailed lighting/camera specs

**Specs**:
- **Aspect Ratio:** 4:5 (portrait, mobile feed)
- **Text Overlay:** "Neither hand goes near the blade." — white bold sans-serif, bottom 20%. Green checkmark arrows to hands. Red X arrow to blade area.
- **Requires Reference Images:** Yes (attach SliceSafe Pro product photos)

---

## #2: The "Blood Sacrifice" Meme -> Resolution

**Based on template**: "Hyper-Realistic Commercial Product Photography — Vertical Split-Screen" (product-marketing.json)

**Content highlights extracted**:
- Before/after emotional contrast
- Cool desaturated LEFT (fear/injury) vs warm saturated RIGHT (safety/confidence)
- Split-screen with dramatic mood shift

**Remixed prompt (English — use for generation)**:
```json
{
  "master_prompt": {
    "global_settings": {
      "style": "Hyper-realistic split-screen comparison photography",
      "layout": "Vertical split-screen, two distinct modules divided by thin 4px white line",
      "resolution": "8K UHD, cinematic lighting",
      "details": "Extreme clarity, contrasting mood between halves"
    },
    "module_1_left": {
      "subject": {
        "type": "Person's left hand held up toward camera, palm facing viewer",
        "details": "Bright red adhesive bandages on index finger and middle finger tips, fingers slightly spread in defeated gesture",
        "background_object": "Traditional flat silver mandoline slicer on dark cutting board, exposed blade catching harsh light"
      },
      "scattered_elements": [
        "Uneven potato slices on cutting board",
        "Cold harsh overhead fluorescent lighting"
      ],
      "background": {
        "color": "Cool, desaturated, clinical tones",
        "lighting": "Flat overhead fluorescent, unflattering"
      },
      "mood": "Defeated, relatable, slightly humorous — only the red bandages are saturated"
    },
    "module_2_right": {
      "subject": {
        "type": "Both hands confidently gripping top handle of light-blue SliceSafe Pro mandoline",
        "details": "Relaxed hands, no bandages, healthy skin, pushing vibrant red bell pepper through food hopper"
      },
      "result_elements": [
        "Perfect thin bell pepper rings cascading into clear collection container",
        "Vibrant red and yellow pepper colors"
      ],
      "background": {
        "color": "Warm golden tones, butcher block countertop, soft kitchen bokeh",
        "lighting": "Warm directional side-light from window"
      },
      "mood": "Confident, easy, bright, inviting"
    },
    "surface_details": {
      "left": "Dark cutting board, clinical feel",
      "right": "Warm butcher block, homey feel"
    },
    "composition": {
      "scale": "Both halves shot at same scale so hands are similar in size",
      "contrast": "Lighting, color, and mood shift must be immediately obvious between halves"
    }
  }
}
```

**Modifications**:
- Replaced milkshake/Nescafe products with mandoline injury scene (left) and SliceSafe Pro safety demo (right)
- Kept the split-screen two-module structure with contrasting lighting/mood between sides
- Adapted floating elements to scattered vegetable slices and bandage details
- Maintained the original's dramatic mood contrast as the core visual hook

**Specs**:
- **Aspect Ratio:** 1:1 (square, feed optimized)
- **Text Overlay:** LEFT: "Every mandoline owner knows." (white italic). RIGHT: "Never again." (white bold). Bottom bar: "SliceSafe Pro — $69.99". Red X top-left, green checkmark top-right.
- **Requires Reference Images:** Yes

---

## #3: The "Viral Cucumber Salad" Trend Hijack

**Based on template**: "Cinematic Food Ad of Chocolate Crepes" (social-media-post.json)

**Content highlights extracted**:
- Food-first hero shot that doubles as native social content
- UGC creator style — looks like organic recipe content, not an ad
- Warm natural daylight, hyper-realistic textures

**Remixed prompt (English — use for generation)**:
```
Cinematic overhead flat-lay food photograph of a stunning Asian-inspired cucumber salad in a large white ceramic serving bowl, paper-thin translucent cucumber rounds layered and overlapping, glistening with light sesame-chili oil dressing, scattered with toasted white sesame seeds and thin-sliced red chili rings, drops of vibrant chili crisp oil pooling in the curves. Cucumber slices impossibly uniform and thin, visual proof of mandoline precision. Salad styled casually on a light butcher block countertop surrounded by a small dish of sesame seeds, light wood chopsticks on a ceramic rest, a cut lime cross-section, and a folded off-white linen napkin. A green-colorway standing mandoline slicer sits naturally in the upper-right, clear collection container still holding a few cucumber rounds, half-cucumber in the food hopper as if just set aside after slicing. A hand reaches into the upper-left holding a small ramekin of dressing. Warm natural daylight from overhead ring light, bright even illumination typical of food content creators, vibrant color saturation. Subtle imperfections for UGC authenticity — one cucumber round overlapping bowl edge, a sesame seed on the counter. A smartphone partially visible at bottom edge, screen-down. Hyper-realistic textures, professional food styling, 8K resolution, perfectly framed for social media and native ad storytelling. No text, no logos, no watermarks.
```

**Modifications**:
- Replaced chocolate crepes with Asian cucumber salad (viral trend)
- Kept the original's single-paragraph dense format, food-first hero composition, warm daylight emphasis
- Added UGC authenticity details (phone edge, slight imperfections) specific to trend-jacking strategy
- Placed product naturally in scene (not centered — it should feel incidental, not staged)
- Used green colorway to harmonize with cucumber-heavy palette

**Specs**:
- **Aspect Ratio:** 4:5 (portrait, Instagram feed)
- **Text Overlay:** "the secret to that cucumber salad" — lowercase handwritten font, bottom-center. "SliceSafe Pro | link in bio" — tiny bottom-right. NO arrows or checkmarks — this works by not looking like an ad.
- **Requires Reference Images:** Yes

---

## #4: The "6:15pm Weeknight Dread" Moment

**Based on template**: "Intimate Lifestyle Documentary Couple Photo" (social-media-post.json)

**Content highlights extracted**:
- Relatable weeknight moment — just got home, have to cook
- Warm golden-hour kitchen, documentary film aesthetic
- Calm confidence, not forced joy

**Remixed prompt (English — use for generation)**:
```json
{
  "generation_request": {
    "meta_data": {
      "task_type": "weeknight_lifestyle_documentary_photo",
      "priority": "highest",
      "language": "en",
      "style_version": "v1.0_golden_hour_kitchen_confidence"
    },
    "output": {
      "aspect_ratio": "4:5",
      "resolution": "high",
      "num_images": 1
    },
    "scene": {
      "environment": "lived-in home kitchen, white cabinets, dishes in drying rack, olive oil bottle and salt cellar on counter, child's drawing on refrigerator held by magnet",
      "props": "tablet propped against backsplash showing recipe, sheet pan lined with parchment waiting for slices, wooden cutting board with pile of already-sliced sweet potato rounds",
      "moment": "a quiet weeknight cooking moment, calm and capable, the golden-hour light streaming through window above sink"
    },
    "subjects": {
      "type": "single woman",
      "pose": "standing at counter using a light-blue standing mandoline slicer, both hands on top handle pressing a large sweet potato through the food hopper",
      "body_language": "relaxed posture, sleeves rolled up, confident and at ease",
      "wardrobe": {
        "woman": "slightly rumpled chambray button-up with sleeves rolled to elbows, dark slim pants — just got home from work"
      },
      "expressions": {
        "woman": "slight genuine half-smile, calm focus, quiet satisfaction of someone who found an easier way"
      }
    },
    "product_details": {
      "product": "SliceSafe Pro mandoline in light blue",
      "position": "in subject's hands, both hands clearly on TOP handle",
      "vegetable": "large sweet potato, deep purple-orange skin visible in food hopper",
      "results": "uniform golden-orange sweet potato rounds on cutting board to her left"
    },
    "camera": {
      "camera_type": "35mm documentary lens look",
      "lens": "50mm",
      "aperture": "f/4",
      "focus": "sharp on woman and product, background softly present",
      "framing": "medium shot, kitchen context visible",
      "perspective": "natural eye-level, slightly left, as if standing in kitchen doorway"
    },
    "lighting": {
      "type": "golden-hour window light streaming through kitchen window",
      "key_light": "warm directional sunlight creating rim light on hair and shoulders",
      "contrast": "medium, warm",
      "shadows": "long golden shadows across counter"
    },
    "color_grading": {
      "palette": "warm golden tones, orange sweet potato accent, chambray blue echoing product, light-blue SliceSafe Pro as cool focal point",
      "white_balance": "warm",
      "saturation": "natural, slightly warm",
      "look": "documentary lifestyle editorial, intimate weeknight moment"
    },
    "film_effects": {
      "grain": "fine 35mm film grain",
      "halation": "subtle warmth around window light",
      "softness": "slight analog softness in background",
      "vignette": "very subtle natural vignette"
    },
    "global_constraints": {
      "no_text": true,
      "no_logos": true,
      "no_watermark": true,
      "no_ai_plastic_skin": true,
      "hands_above_blade": "CRITICAL — both hands on top handle at all times"
    }
  }
}
```

**Modifications**:
- Replaced couple embrace scene with solo woman cooking with SliceSafe Pro
- Kept full JSON structure: scene, subjects, camera (35mm), lighting, color_grading, film_effects, global_constraints
- Changed warm tungsten to golden-hour window light to reinforce "6:15pm just got home" narrative
- Added product-specific details (sweet potato, hands-on-top) within the template's subject structure
- Maintained documentary realism aesthetic — "caught in the moment" not "ad shoot"

**Specs**:
- **Aspect Ratio:** 4:5 (portrait, mobile feed)
- **Text Overlay:** "6:15pm. Dinner in 25 minutes." — upper-left, white bold sans-serif. "Prep that used to take 15 minutes now takes 2." — below. "SliceSafe Pro — $69.99" — bottom-center.
- **Requires Reference Images:** Yes

---

## #5: The "Guards Don't Work" Insight

**Based on template**: "Great Wall Mixed Media Comparison" (infographic-edu-visual.json)

**Content highlights extracted**:
- Visual argument: old approach fails (left) vs new approach works (right)
- Clear left-to-right narrative progression
- Distinct visual treatment per side

**Remixed prompt (English — use for generation)**:
```json
{
  "objective": "Create a side-by-side comparison image showing a failed traditional mandoline safety guard versus the SliceSafe Pro's integrated safety design",
  "image_specifications": {
    "style": "Photorealistic product comparison photography",
    "layout": "Horizontal split — Left side: traditional mandoline failure, Right side: SliceSafe Pro solution",
    "aspect_ratio": "16:9"
  },
  "left_side": {
    "content_type": "Traditional flat mandoline with detached safety guard",
    "features": [
      "Generic silver flat mandoline on white marble countertop",
      "Translucent plastic safety guard with prongs, DETACHED and sitting next to the mandoline — not on it",
      "Guard looks clunky, awkward, ill-fitting — clearly removed because it doesn't work",
      "Exposed blade catching harsh cold overhead light, looking threatening",
      "A few uneven, poorly-cut carrot slices suggesting failed attempts",
      "Single unopened adhesive bandage in wrapper sitting ominously nearby"
    ],
    "lighting": "Flat, cool overhead fluorescent — makes plastic look cheap and blade look dangerous",
    "mood": "Abandoned, frustrated, anticipatory dread",
    "positioning": "Left half of image"
  },
  "right_side": {
    "content_type": "SliceSafe Pro mandoline in use with hands-on-top safety",
    "features": [
      "Light-blue standing SliceSafe Pro upright on same marble countertop",
      "Woman's hands confidently on TOP handle, carrot loaded in food hopper",
      "Perfect uniform carrot coins filling clear collection container below",
      "Stainless steel blade catching warm attractive glint",
      "Thickness dial visible on side",
      "Rubberized base firmly planted"
    ],
    "lighting": "Warm dimensional side-light from camera-right — makes product look premium and inviting",
    "mood": "Confident, modern, premium, safe",
    "positioning": "Right half of image"
  },
  "visual_elements": {
    "border_division": "Natural negative space on white marble as the visual divider — clean breathing room between zones",
    "color_palette": {
      "left": "Cool grays, silver, desaturated carrot orange, clinical white — cheap and dangerous",
      "right": "Warm tones, vibrant carrot orange, premium light blue, stainless glint — safe and premium"
    }
  },
  "camera": {
    "angle": "25 degrees above countertop",
    "depth_of_field": "f/3.5, both products in focus, far background softened",
    "framing": "Both products fully visible from hopper to base"
  },
  "output_format": {
    "type": "Image",
    "use_case": ["Meta feed ad", "Facebook link ad", "Product comparison"],
    "high_resolution": true,
    "no_text": true,
    "no_logos": true
  }
}
```

**Modifications**:
- Replaced Great Wall sketch/photo comparison with mandoline guard failure vs SliceSafe Pro solution
- Kept the structured left_side/right_side JSON format with features arrays, distinct lighting per side, and visual_elements section
- Added mood and color_palette per side to reinforce the narrative shift
- The detached guard is the key insight element — it triggers instant recognition in every mandoline owner

**Specs**:
- **Aspect Ratio:** 16:9 (landscape, Facebook feed/link ads)
- **Text Overlay:** LEFT: "Be honest: you took the guard off." (white italic). RIGHT: "What if the whole thing was the guard?" (white bold). Hand-drawn red circle on detached guard, green circle on hands-on-top.
- **Requires Reference Images:** Yes

---

## TIER 2: STRONG PERFORMERS

---

## #6: The "Sharp Is Safer" Paradox

**Based on template**: "Hyper-realistic Fanta Orange Product Shot with Splash" (ecommerce-main-image.json)

**Remixed prompt:**
```
Hyper-realistic cinematic macro photograph of a surgical-grade stainless steel mandoline blade slicing through a cucumber in cross-section, captured at the exact moment of separation. Blade edge gleaming with precise specular highlight, slicing effortlessly with zero compression or tearing of cucumber flesh. Cucumber cross-section shows perfect cellular detail, seeds visible, skin edge clean as a scalpel cut. A paper-thin translucent cucumber round is separating from the main body, barely detached, frozen in the moment of separation. Behind the blade, the light-blue body of the SliceSafe Pro mandoline housing softly out of focus. A second completed slice visible below, perfectly matching thickness. Lighting is dramatic and premium: clean directional studio light from camera-left creating bright specular line on blade edge, subtle rim light defining blade contour and cucumber surface moisture. Shallow depth of field with creamy bokeh, high contrast, ultra-sharp focus on the exact cut point and blade-meets-vegetable contact zone. Clean studio setup with no visible supports, no text overlays, no graphic elements. Color palette dominated by cool steel silver, fresh cucumber green, and soft light-blue from product body. Photorealistic materials, advertising-grade composition, scientific precision aesthetic, macro realism, 8K resolution.
```

**Specs:**
- **Aspect Ratio:** 1:1
- **Text Overlay:** "DULL BLADE: Push hard -> Slip -> Cut" (red X) vs "SHARP BLADE: Glide smooth -> Control -> Safe" (green check). Bottom: "Sharp is actually SAFER."
- **Requires Reference Images:** Yes

---

## #7: The "10-Second Cleanup" Proof

**Based on template**: "Hyper-realistic Tea Exploded View Infographic" (infographic-edu-visual.json)

**Remixed prompt:**
```
Hyper-realistic 2x2 grid instructional photograph on a pure white background showing four sequential cleanup steps for a light-blue standing mandoline slicer. PANEL 1 (top-left): The mandoline held under a running chrome kitchen faucet, water cascading over blade area and collection container, food residue washing away, hand safely gripping top handle away from blade. PANEL 2 (top-right): A small cleaning brush with bristles sweeping across the stainless steel blade surface from the safe top side, bristle detail visible at macro clarity. PANEL 3 (bottom-left): The clean mandoline being patted dry with a white kitchen towel, gleaming stainless steel and spotless light-blue housing, water droplets catching light. PANEL 4 (bottom-right): The mandoline folded compact being placed into a kitchen drawer alongside other utensils, fitting neatly. Clean studio lighting across all four panels, consistent warm natural light from camera-right. Ultra-detailed DSLR photography style, sharp focus, each panel crisp and clear at f/5.6. Minimal clean aesthetic, evenly spaced panels with thin white borders. 8K resolution. No text, no logos, no watermarks.
```

**Specs:**
- **Aspect Ratio:** 1:1
- **Text Overlay:** Large "10 SECONDS" with stopwatch icon centered. Labels: "1. Rinse" "2. Brush" "3. Dry" "4. Store". Bottom: "10-second cleanup. Fingers never go near the blade."
- **Requires Reference Images:** Yes

---

## #8: The "Pre-Cut Produce" Money Drain

**Based on template**: "Great Wall Mixed Media Comparison" (infographic-edu-visual.json)

**Remixed prompt:**
```json
{
  "objective": "Side-by-side comparison showing expensive pre-cut produce versus fresh SliceSafe Pro-cut vegetables",
  "image_specifications": {
    "style": "Photorealistic food comparison photography",
    "layout": "Horizontal split — Left: overpriced pre-cut package, Right: fresh mandoline-sliced vegetables",
    "aspect_ratio": "4:5"
  },
  "left_side": {
    "content_type": "Grocery store pre-cut vegetable package",
    "features": [
      "Clear plastic container of pre-cut stir-fry mix",
      "Yellow price sticker reading $6.99 clearly visible",
      "Vegetables slightly wilted and oxidized",
      "Condensation inside plastic packaging",
      "Wasteful, overpriced appearance"
    ],
    "lighting": "Grocery-store fluorescent, unflattering",
    "color_palette": "Dull, desaturated, plastic sheen"
  },
  "right_side": {
    "content_type": "Fresh vegetables sliced with SliceSafe Pro",
    "features": [
      "Same volume of vibrant, perfectly sliced vegetables on wooden cutting board",
      "Bell pepper strips, zucchini rounds, carrot coins — dramatically fresher",
      "SliceSafe Pro in light blue behind vegetables, thickness dial visible",
      "Whole bell pepper in food hopper",
      "Small chalkboard price tag reading $1.50"
    ],
    "lighting": "Warm natural window light, inviting",
    "color_palette": "Vibrant reds, oranges, greens against warm wood"
  },
  "visual_elements": {
    "border_division": "Subtle gradient transition",
    "color_contrast": "Dull plastic left vs vibrant fresh right"
  }
}
```

**Specs:**
- **Aspect Ratio:** 4:5
- **Text Overlay:** LEFT: "$6.99 — PRE-CUT" (red). RIGHT: "$1.50 — 60 SECONDS" (green). Bottom: "Stop paying 3x more for pre-cut produce."
- **Requires Reference Images:** Yes

---

## #9: The "Restaurant Salad Secret"

**Based on template**: "Great Wall Mixed Media Comparison" (infographic-edu-visual.json)

**Remixed prompt:**
```json
{
  "objective": "Side-by-side comparison of amateur hand-cut salad versus restaurant-quality mandoline-sliced salad",
  "image_specifications": {
    "style": "Food editorial comparison photography",
    "layout": "Horizontal split — Left: amateur salad, Right: restaurant-quality salad",
    "aspect_ratio": "1:1"
  },
  "left_side": {
    "content_type": "Hand-cut amateur salad",
    "features": [
      "Chunky uneven vegetables on white plate",
      "Thick tomato wedges, irregular cucumber chunks, torn lettuce",
      "Haphazard, unappetizing presentation"
    ],
    "lighting": "Flat overhead cafeteria-style, boring"
  },
  "right_side": {
    "content_type": "Restaurant-quality shaved salad",
    "features": [
      "Paper-thin radish rounds, translucent cucumber ribbons, uniform carrot shavings",
      "Delicate frisee, microgreens, light vinaigrette glistening",
      "Vegetables so thin they catch light through edges",
      "SliceSafe Pro in light blue visible in soft focus behind plate"
    ],
    "lighting": "Warm directional side-light, editorial food photography"
  }
}
```

**Specs:**
- **Aspect Ratio:** 1:1
- **Text Overlay:** LEFT: "Your salad". RIGHT: "Restaurant salad". Arrow to mandoline: "The secret." Bottom: "This is why your salads never look like the restaurant's."
- **Requires Reference Images:** Yes

---

## #10: The "3-Part Safety System" Explainer

**Based on template**: "Premium Liquid Glass Bento Grid Product Infographic" (infographic-edu-visual.json)

**Remixed prompt:**
```
Input Variable: SliceSafe Pro Mandoline
Language: English

System Instruction:
Create an image of a premium clean product infographic with 3 highlighted safety zones.

1) Product Display:
-> Hero product: real photography of SliceSafe Pro mandoline in light blue, centered on pure white background, shot straight-on at slight 10-degree angle
-> Full product visible from top handle to rubberized base
-> Ultra-sharp focus at f/8, premium studio lighting from three directions

2) Three Safety Zones (highlighted with subtle glowing outlines):
-> ZONE 1 (TOP — soft green glow): Handle and food hopper area. Label: "HANDS-ON-TOP DESIGN — Hands stay above, always"
-> ZONE 2 (MIDDLE — soft blue glow): Blade area and enclosed housing. Label: "SHARP-GLIDE BLADE — Less pressure = more control"
-> ZONE 3 (BOTTOM — soft amber glow): Rubberized non-slip base. Label: "NON-SLIP STABLE BASE — Locks in place, won't wobble"

3) Visual Style:
-> Clean white background with subtle soft shadow grounding product
-> Thin minimalist connector lines from zones to labels
-> Modern editorial sans-serif font for labels
-> Premium, clean, Apple-style product infographic aesthetic

4) Technical: 8K resolution, photorealistic product rendering, no AI artifacts
```

**Specs:**
- **Aspect Ratio:** 4:5
- **Text Overlay:** Header: "3-Part Safety System". Three zone labels as described. Bottom: "Most mandolines have 1 safety feature. This one has 3."
- **Requires Reference Images:** Yes

---

## #11: The "Meal Prep Transformation"

**Based on template**: "Kashmiri Food Infographic" (infographic-edu-visual.json)

**Remixed prompt:**
```json
{
  "project": "MealPrepFlatLay",
  "metadata": {
    "style": "Hyper-Realistic",
    "theme": "Sunday Meal Prep",
    "resolution": "8K_Ultra_HD"
  },
  "scene_setup": {
    "background": "Light_Butcher_Block_Countertop",
    "lighting": "Bright_Overhead_Natural_Skylight",
    "camera": {
      "type": "DSLR_Full_Frame",
      "angle": "90_degree_overhead_flat_lay",
      "focus": "Sharp_Throughout",
      "depth_of_field": "Deep_f5.6"
    }
  },
  "render_elements": {
    "base_anchor": {
      "object": "SliceSafe Pro mandoline in light blue",
      "position": "center-top of frame",
      "state": "half bell pepper in food hopper, freshly used"
    },
    "surrounding_elements": [
      {"item": "Six glass meal prep containers in two neat rows", "content": "perfectly uniform sliced vegetables — carrot coins, cucumber rounds, zucchini slices, bell pepper strips, sweet potato rounds"},
      {"item": "Woman's hand reaching from right", "action": "transferring slices from mandoline collection container into meal prep container"},
      {"item": "Whole vegetables", "details": "one red pepper, two carrots, a zucchini"},
      {"item": "Roll of plastic wrap and colorful snap-on lids stacked to side"}
    ]
  },
  "mood": "Organized, satisfying, accomplished, meal-prep influencer aesthetic",
  "color_palette": ["vibrant vegetable oranges, reds, greens, yellows", "warm butcher block wood", "clear glass containers", "light-blue product accent"]
}
```

**Specs:**
- **Aspect Ratio:** 1:1
- **Text Overlay:** "Sunday meal prep in 10 minutes. Not 2 hours." Bottom: "SliceSafe Pro — $69.99"
- **Requires Reference Images:** Yes

---

## #12: The "No Gloves Required" Signal

**Based on template**: "Fitness Lifestyle Photo JSON" (product-marketing.json)

**Remixed prompt:**
```json
{
  "scene_type": "product_safety_demonstration",
  "setting": {
    "location": "modern home kitchen",
    "environment": "clean, bright, warm",
    "lighting": "natural window light from camera-left"
  },
  "subject": {
    "type": "person's hands — close-up",
    "position": "both hands confidently on top handle of SliceSafe Pro mandoline",
    "hand_details": "bare hands, no gloves, no bandages, clean healthy skin, short nails, relaxed fingers — zero white-knuckle tension",
    "action": "pressing a potato down through food hopper"
  },
  "objects": [
    {
      "type": "SliceSafe Pro mandoline",
      "color": "light blue",
      "placement": "centered in frame, in active use",
      "collection_container": "filled with perfect golden potato slices"
    },
    {
      "type": "black cut-resistant Kevlar glove",
      "placement": "discarded on countertop to the left, crumpled casually as if tossed aside because not needed",
      "significance": "THE STORY — safety glove exists but is unnecessary with this product"
    }
  ],
  "camera": {
    "angle": "20 degrees above, eye naturally drawn from bare hands to discarded glove",
    "framing": "close-up on hands, product, and glove",
    "depth_of_field": "f/3.2, sharp on hands and product, glove slightly softer"
  },
  "mood": "confident, relaxed, trust in the product",
  "color_palette": ["warm skin tones", "light blue product", "white marble counter", "black glove as contrast", "golden potato slices"]
}
```

**Specs:**
- **Aspect Ratio:** 4:5
- **Text Overlay:** Arrow to glove: "YOU SHOULDN'T NEED THIS" (red). Arrow to hands: "WHEN YOUR HANDS STAY HERE" (green). Bottom: "No gloves required."
- **Requires Reference Images:** Yes

---

## #13: The "Uniform Cooking Results" Logic

**Based on template**: "Great Wall Mixed Media Comparison" (infographic-edu-visual.json)

**Remixed prompt:**
```
Photorealistic top-down photograph at 90 degrees of two sheet pans side by side on a kitchen counter, fresh from the oven with visible steam. LEFT PAN: Roasted vegetables hand-cut in uneven chunks, consequences visible — some charred black, some pale undercooked, some collapsed, thick pieces hard in center. Frustrating, unappetizing. RIGHT PAN: Same vegetables roasted to uniform golden-brown perfection, every slice identical thickness, even caramelization, glistening olive oil, herbs distributed perfectly. Magazine-worthy. Between both pans at top of frame, the light-blue SliceSafe Pro mandoline with empty collection container. Warm overhead kitchen light even across both pans. Sharp focus throughout at f/5.6. Left side shows the problem, right side shows the solution. Photorealistic, food comparison photography, 8K. No text, no logos, no watermarks.
```

**Specs:**
- **Aspect Ratio:** 1:1
- **Text Overlay:** LEFT: "HAND CUT" (red X). RIGHT: "SLICESAFE CUT" (green check). Bottom: "Same recipe. Same oven. Different slices."
- **Requires Reference Images:** Yes

---

## #14: The "Drawer Ornament" Replacement

**Based on template**: "Hyper-Realistic Split-Screen" adapted vertically (product-marketing.json)

**Remixed prompt:**
```json
{
  "master_prompt": {
    "global_settings": {
      "style": "Vertical split storytelling — before/after",
      "layout": "Top half: problem, Bottom half: solution",
      "resolution": "8K",
      "aspect_ratio": "4:5"
    },
    "module_1_top": {
      "subject": {
        "type": "Cluttered kitchen drawer pulled open, shot from 45 degrees above",
        "details": "Traditional flat silver mandoline buried under garlic press, can opener, tangled rubber bands, peeler, random utensils"
      },
      "mood": "Dusty, unused, forgotten, chaotic",
      "lighting": "Flat overhead, unflattering, showing dust",
      "color_grading": "Dull, desaturated, dusty"
    },
    "module_2_bottom": {
      "subject": {
        "type": "Clean modern kitchen countertop with SliceSafe Pro in light blue standing upright",
        "details": "Actively in use — hands on top handle, fresh zucchini loaded, perfect rounds filling collection container"
      },
      "mood": "Clean, organized, modern, in use",
      "lighting": "Warm window light, inviting",
      "color_grading": "Warm, bright, clean"
    }
  }
}
```

**Specs:**
- **Aspect Ratio:** 4:5
- **Text Overlay:** TOP: "SOUND FAMILIAR?" BOTTOM: "THIS ONE YOU'LL ACTUALLY USE". Bottom bar: "The mandoline you'll actually use. — $69.99"
- **Requires Reference Images:** Yes

---

## #15: The "Hard Veggie Resistance" Demo

**Based on template**: "Ultra-Cinematic Luxury Cold Brew Product Photography" (product-marketing.json)

**Remixed prompt:**
```json
{
  "master_prompt": {
    "product": {
      "type": "standing mandoline vegetable slicer",
      "brand_name": "SliceSafe Pro",
      "body": "premium light-blue molded housing",
      "blade": "surgical-grade stainless steel, mid-cut through dense sweet potato",
      "base": "rubberized dark-gray feet firmly planted on dark granite, zero movement"
    },
    "composition": {
      "scene_type": "ultra-cinematic product action photography",
      "orientation": "vertical",
      "aspect_ratio": "4:5",
      "camera_angle": "30 degrees, capturing full product from hopper to base",
      "subject_position": "centered, stable, grounded — emphasizing no wobble despite force",
      "motion": "frozen mid-slice — perfect sweet potato disc separating with clean edges"
    },
    "environment": {
      "background": "dark granite countertop, modern kitchen soft-focused behind",
      "atmosphere": "stability, control, power"
    },
    "lighting": {
      "style": "warm studio light from camera-right",
      "key_light": "directional highlighting orange sweet potato flesh and blue housing",
      "rim_lights": "subtle fill from left",
      "highlights": "blade glint, orange flesh vibrancy"
    },
    "camera_settings": {
      "lens": "85mm portrait",
      "depth_of_field": "shallow f/2.8, sharp on cutting point and hands",
      "focus_point": "blade-meets-sweet-potato contact zone"
    },
    "render_quality": {
      "resolution": "8K",
      "style": "hyper-realistic product demonstration",
      "textures": "accurate stainless steel, dense sweet potato flesh, rubberized grip"
    },
    "mood": {
      "tone": "confident, powerful, stable",
      "emotion": "trust, capability, no fear of hard vegetables"
    }
  }
}
```

**Specs:**
- **Aspect Ratio:** 4:5
- **Text Overlay:** "SWEET POTATO. NO SLIP. NO FORCE. NO FEAR." Arrow to base: "Non-slip rubberized base". Arrow to hands: "Hands stay on top."
- **Requires Reference Images:** Yes

---

## TIER 3: TEST-WORTHY

---

## #16: The "Slaw in 3 Minutes"

**Based on template**: "Cinematic Food Ad of Chocolate Crepes" (social-media-post.json)

**Remixed prompt:**
```
Cinematic food photograph of a large white ceramic bowl overflowing with fresh vibrant homemade coleslaw — paper-thin cabbage shreds in pale green and purple, matchstick carrots in bright orange, tossed in creamy dressing with visible black pepper and fresh dill garnish. Slaw looks restaurant-quality, shreds impossibly thin and uniform. To the right, a half-head of green cabbage on wooden cutting board. Behind the bowl, the green-colorway standing mandoline slicer with thin cabbage shreds still in its clear collection container. A woman's hand tossing the slaw with wooden tongs from the left. Warm natural window light, bright and fresh. Vibrant greens, purples, oranges against white ceramic and warm wood. 45-degree camera angle. Hyper-realistic textures, professional food styling, 8K resolution, perfectly framed for social media and recipe content storytelling. No text, no logos, no watermarks.
```

**Specs:** 4:5 | "FROM THIS -> TO THIS -> IN 3 MINUTES" | Ref images: Yes

---

## #17: The "Paper-Thin Chip Perfection"

**Based on template**: "Cinematic Food Ad of Chocolate Crepes" (social-media-post.json)

**Remixed prompt:**
```
Cinematic food photograph of homemade potato chips spread across brown parchment paper on a rustic wooden table. Chips paper-thin, golden-crispy, lightly salted with visible flaky sea salt crystals, some perfectly flat, others with beautiful natural curls from frying. Translucent at edges where light passes through, proving extreme thinness. In background at soft focus, the light-blue standing mandoline slicer with thickness dial turned to thinnest setting. Next to mandoline, raw paper-thin potato slices fanned out showing pre-frying uniformity. Small ceramic bowl of flaky sea salt and rosemary sprig as styling accents. Warm golden side-light from camera-left creating beautiful highlights on crispy surfaces. Slow, mouthwatering macro feel with smooth composition. 30-degree camera angle. Shallow depth of field f/2.8. Hyper-realistic textures, artisanal food photography, 8K resolution. No text, no logos, no watermarks.
```

**Specs:** 1:1 | "CHIP-SHOP THIN. HOME KITCHEN EASY." | Ref images: Yes

---

## #18: The "Stop Before The Nub" Safety Ritual

**Based on template**: "Tea Exploded View Infographic" (infographic-edu-visual.json)

**Remixed prompt:**
```
Hyper-realistic instructional photograph on a clean white background showing a light-blue standing mandoline slicer from a side angle with a partially-sliced carrot in the food hopper. Carrot two-thirds sliced with approximately 2 inches remaining. Clean educational layout with a white dotted line indicating the safe stopping point. Above the line, woman's hands in safe position on top handle. Below mandoline, clear collection container filled with perfect carrot coins. Clean studio lighting, macro realism, sharp focus throughout at f/5.6. Minimal aesthetic, educational diagram feel photographed beautifully. Ultra-detailed DSLR style, 8K resolution. No text in the image generation.
```

**Specs:** 4:5 | Red "STOP LINE". "SAFE ZONE" above. "Save the nub for stock" below. | Ref images: Yes

---

## #19: The "Stability Test" Demo

**Based on template**: "Ultra-Cinematic Cold Brew" adapted (product-marketing.json)

**Remixed prompt:**
```json
{
  "master_prompt": {
    "product": {
      "type": "standing mandoline slicer",
      "brand_name": "SliceSafe Pro",
      "body": "light-blue housing",
      "base": "rubberized non-slip feet in sharp focus, gripping counter surface"
    },
    "composition": {
      "camera_angle": "low angle, 10 degrees above counter level — emphasizing base stability",
      "subject_position": "grounded, immovable despite force applied",
      "action": "person pressing down firmly on top handle with visible arm tension, butternut squash in hopper"
    },
    "environment": {
      "surface": "slightly wet countertop with water droplets visible — proving grip holds even on wet surfaces",
      "results": "perfect butternut squash rounds in collection container"
    },
    "lighting": {
      "style": "clean studio from camera-right",
      "highlights": "water droplets catching light, blade glint"
    },
    "render_quality": {
      "resolution": "8K",
      "depth_of_field": "f/3.5"
    }
  }
}
```

**Specs:** 1:1 | Red circle on feet: "NON-SLIP GRIP". "WOBBLE = DANGER. STABLE = SAFE." | Ref images: Yes

---

## #20: The "TikTok Injury Prevention" PSA

**Based on template**: "Candid Paparazzi Street Portrait" (social-media-post.json)

**Remixed prompt:**
```
Candid social-media-style photograph, two-zone vertical composition with soft gradient transition. Upper zone: close-up of a thumb with small adhesive bandage on the tip, held up toward camera in self-deprecating gesture, blurred smartphone in other hand showing social media feed. Handheld camera feel, slightly tilted, cool phone-screen light, documentary realism. Lower zone: light-blue SliceSafe Pro mandoline in use, both hands safely on top handle pushing cucumber through, perfect slices dropping into collection container. Warm kitchen lighting, clean modern background. The transition between zones is a soft gradient, not a hard split. Overall composition feels like native social media content, not polished ad. Color grading mimics phone photography with boosted contrast, subtle film grain. Cinematic color grading with teal and warm tones. Photorealistic, UGC-native PSA aesthetic, 9:16 vertical. No text, no logos, no watermarks.
```

**Specs:** 9:16 (Stories/Reels) | "DON'T BE THE NEXT VIRAL INJURY VIDEO" top. "POV: You want the cucumber salad but you like your fingers" bottom. | Ref images: Yes

---

## #21: The "Vegetable Avoidance Cycle" Insight

**Based on template**: "Bento Grid Product Infographic" (infographic-edu-visual.json)

**Remixed prompt:**
```
Input Variable: SliceSafe Pro Mandoline
Language: English

Create an image of a clean, modern infographic showing a circular avoidance cycle with the product breaking it.

Visual Style: Clean modern infographic overlay on soft-focus warm kitchen background

Cycle Diagram (3 stages connected by curved arrows in a loop):
-> Stage 1: Icon/illustration of stressed person at cutting board with uncut vegetables. Label: "CHOPPING IS HARD"
-> Stage 2: Icon/illustration of takeout container and delivery app on phone. Label: "SKIP VEGETABLES"
-> Stage 3: Icon/illustration of guilty person with empty takeout container. Label: "FEEL GUILTY"
-> Arrows connect stages in continuous loop

Breaking Element:
-> The SliceSafe Pro mandoline in light blue, positioned OUTSIDE the cycle
-> Bold arrow breaks through between Stage 1 and Stage 2
-> Product is in sharp focus, well-lit, while cycle stages are softer
-> Label: "BREAK THE CYCLE"

Style: Photorealistic product + clean vector-style diagram overlay. Warm natural kitchen lighting in background. 1:1 aspect ratio. Premium, modern aesthetic.
```

**Specs:** 1:1 | Cycle labels as described. Bottom: "Make vegetables so easy you actually eat them." | Ref images: Yes

---

## #22: The "Quality vs Cheap" Comparison

**Based on template**: "Great Wall Mixed Media Comparison" (infographic-edu-visual.json)

**Remixed prompt:**
```json
{
  "objective": "Side-by-side quality comparison: cheap flimsy mandoline versus premium SliceSafe Pro",
  "image_specifications": {
    "style": "Product quality comparison photography",
    "layout": "Horizontal split",
    "aspect_ratio": "16:9"
  },
  "left_side": {
    "content_type": "Cheap plastic flat mandoline",
    "features": ["Transparent flimsy plastic, visibly flexing under potato weight", "Wobbly, unstable", "Thin stamped blade looking dull", "Safety guard ill-fitting"],
    "lighting": "Harsh flat overhead — emphasizing cheap plastic sheen",
    "color_palette": "Cool, flat, dollar-store aesthetic"
  },
  "right_side": {
    "content_type": "SliceSafe Pro in light blue",
    "features": ["Standing tall, solid, stable, premium", "Stainless steel blade gleaming", "Thickness dial visible", "Rubberized base firmly planted", "Clear collection container"],
    "lighting": "Warm directional from camera-right — premium product highlights",
    "color_palette": "Warm, dimensional, engineered quality"
  }
}
```

**Specs:** 16:9 | LEFT: "$15 — CHEAP = SCARY" (red). RIGHT: "$69.99 — QUALITY = SAFE" (green). | Ref images: Yes

---

## #23: The "Thickness Dial" Precision

**Based on template**: "Fanta Orange Product Shot" macro style (ecommerce-main-image.json)

**Remixed prompt:**
```
Hyper-realistic macro beauty shot of the thickness adjustment dial on a light-blue standing mandoline slicer, filling the left third of the frame. Dial in sharp macro focus showing numbered settings and tactile grip texture, specular highlight on the dial's metallic center. Extending right across a clean white marble surface, four rows of cucumber slices arranged in a gradient from paper-thin translucent on the left to thick substantial rounds on the right. Thinnest slices so thin light passes through showing seed patterns. Thickest are robust gratin-style rounds. Each row perfectly uniform within itself, demonstrating precision at every setting. Lighting dramatic and premium: clean directional studio light from camera-left, subtle rim light defining slice edges and dial contour. Shallow depth of field with sharp focus on dial and nearest slices, gentle softening on furthest. High contrast, ultra-sharp textures. Color palette: cool steel silver, fresh cucumber green, light-blue product, white marble. Photorealistic, advertising-grade precision beauty shot, 8K resolution. No text, no logos, no watermarks.
```

**Specs:** 16:9 | Labels: "SALAD THIN" | "CHIP PERFECT" | "STIR-FRY" | "GRATIN SLICES". Center: "Perfect slices. Every time. Any thickness." | Ref images: Yes

---

## #24: The "Compact Storage" Solution

**Based on template**: "Cinematic Product Shot of Hand Cream" (product-marketing.json)

**Remixed prompt:**
```
Cinematic overhead photograph of an organized kitchen drawer pulled open, shot from 45 degrees above. Inside, the light-blue SliceSafe Pro mandoline stored folded flat, fitting neatly alongside wooden spoon, silicone spatula, whisk, and measuring cups. Mandoline takes up minimal space, approximately footprint of a large spatula, standing out as the most modern and premium item due to light-blue color and clean design. A hand reaching in to grab the mandoline, about to pull it out for use, suggesting regular use. Bamboo drawer divider system keeping everything organized. Kitchen counter visible above drawer with warm natural light. Clean studio-quality lighting, high-end commercial aesthetic, advertising appeal, minimalist. Warm wood tones, light-blue product accent, clean whites. Photorealistic, 8K. No text, no logos, no watermarks.
```

**Specs:** 4:5 | "STORES FLAT. GETS USED OFTEN." Bottom: "If it's bulky, it lives in a drawer unused." | Ref images: Yes

---

## #25: The "Beginner Confidence Builder"

**Based on template**: "Intimate Lifestyle Documentary Kitchen Photo" (social-media-post.json)

**Remixed prompt:**
```json
{
  "generation_request": {
    "meta_data": {
      "task_type": "empowerment_lifestyle_portrait",
      "style_version": "v1.0_beginner_confidence_kitchen"
    },
    "output": {
      "aspect_ratio": "4:5",
      "resolution": "high"
    },
    "scene": {
      "environment": "simple bright modern kitchen suggesting someone early in their cooking journey — a few basic cookbooks on shelf, small herb plant on windowsill, minimal equipment",
      "props": "cutting board with knife pushed aside as if she chose the mandoline instead",
      "moment": "first time using the product successfully, pleasant surprise"
    },
    "subjects": {
      "type": "single young woman, late 20s",
      "pose": "using light-blue SliceSafe Pro mandoline, both hands on top handle in correct safe position",
      "body_language": "genuine mix of pleasant surprise and growing confidence — eyebrows slightly raised, real smile forming, eyes looking down at perfect slices",
      "wardrobe": {
        "woman": "casual oversized sweater, hair in messy bun — approachable, not a chef"
      }
    },
    "camera": {
      "camera_type": "digital",
      "lens": "50mm",
      "aperture": "f/2.8",
      "focus": "sharp on expression and hands",
      "framing": "medium shot",
      "perspective": "slightly below eye level — empowering, looking up at her subtly"
    },
    "lighting": {
      "type": "bright natural window light from camera-left",
      "mood": "fresh, optimistic, encouraging"
    },
    "color_grading": {
      "palette": "bright warm tones, light-blue product as cool focal point",
      "look": "empowerment lifestyle photography, beginner-friendly"
    },
    "global_constraints": {
      "no_text": true,
      "no_logos": true,
      "no_ai_plastic_skin": true,
      "hands_above_blade": "CRITICAL"
    }
  }
}
```

**Specs:** 4:5 | Thought bubble: "I CAN DO THIS." Bottom: "I'm ready for a mandoline... but I'm scared." CTA: "SliceSafe Pro — Built for beginners. $69.99" | Ref images: Yes

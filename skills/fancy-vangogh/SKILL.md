---
name: fancy-vangogh
description: Create or revise an illustration from a photo or written scene in the Fancy-VanGogh visual language, with reference-calibrated cartoon characters and graphic environment strokes. Use when this specific style is requested, not for generic Van Gogh oil paintings.
---

# Fancy-VanGogh illustrator

Create a new illustration using the drawing rules distilled from the reference collection: expressive ink-cartoon subjects, connected color planes and environmental strokes that build forms. A photo with outlines, a stock animation face or a global paint-texture finish can still miss the target. Use actual inspected images with the available built-in image generator.

Read [drawing rules and full anchors](references/drawing-rules.md) and [character/environment construction](references/character-environment.md). Choose the relevant [workflow recipe](references/workflows.md). For an unfamiliar object read [transfer grammar](references/visual-grammar.md); for substantial sky or a visible sun/moon read [sky and light](references/sky-and-light.md). [Calibration](references/evidence.md) distinguishes original observations, human preferences and tested limits. Development galleries and generated guides are not runtime dependencies.

## Reference inputs

Use the user's visual references when available. For image-led matching, inspect the relevant originals via [artwork sources](references/artwork-sources.md) or use copies supplied by the user. Attach images only when the host makes them available to the generator. A URL or an uninspected image is not an attachment.

For a text or photo request without accessible style images, generate using the written drawing rules. Keep the photo as content and report that the result used text-only style guidance. If the user requests comparison to a particular inaccessible drawing, ask for the relevant image.

## Establish content, contacts and framing

For a photo, identify the individual's head/hair relationships, features, expression, occlusions, costume and action. Do not assume a supplied sample depicts the user. Keep meaningful patterns, important counts, supports, touching hands and overlaps. For unnamed objects, record silhouette, openings, scale and visible contacts before inferring their class. For text, keep specified entities, interactions and mood, composing unstated details.

Background replacement preserves the subject-contact group—used seat/support, held objects, companions and essential foreground props—while redesigning the surrounding setting for this moment. Name the new major forms and placements positively. If an earlier candidate acquired extra props, derive an explicit inventory from the source and inspect additions, complete handles/openings and actual supports. Creative setting additions remain available when requested.

For a rope, leash, cable or other flexible connector, trace both endpoints and the path through each hand or occlusion. For a confusing path, describe its ordered exposed segments and interruptions by grips/supports before local twists or texture. Two convincing grips do not prove a single continuous line. Distinguish a documented free tail from a generated duplicate or fork.

A new setting/viewpoint requested from a photo still uses that photo as content; a previous full illustration is an edit target when the user asks to revise it. Record that distinction. A drawn guide can carry source content but does not establish exact identity. Record aspect ratio, subject scale and required visible extent independently of the guide crop; specify head/hand/body regions when scale drifts. Cropped contacts are unverified. Newly revealed anatomy or scenery is inference.

## Design the subject

Choose a few identity-bearing shape relationships and translate them into individually designed curves/planes. Stronger abstraction needs deliberate proportion/feature choices; fewer details on unchanged portrait anatomy are insufficient. Preserve this individual's expression and age cues instead of a recurring painter, cute/young replacement or heroic face. Give multiple people contrasting head/feature relationships. In crowds distinguish focal, smaller, back-facing and occluded figures; check required counts including silhouettes inside openings, without drawing features through hidden heads.

Use moderate natural near-black contours, linked unequal silhouette/feature turns, selective contact emphasis, grouped hair/fur and connected skin/garment planes with bounded shadows. Smooth confident strokes are valid. Neither random jitter, uniformly heavy borders nor globally thin realistic strands establish hand drawing. Keep meaningful garment/headwear patterns as graphic groups on their planes.

Choose eye opening, lid coverage and pupil placement together from source expression/occlusion/scale. Open focal eyes can retain unequal exposed whites; dot eyes and closed curves are legitimate when appropriate. Simplifying a visible iris or its reflections must not accidentally erase the pupil and gaze, including in an animal's colored eyes. Do not invent eye detail beneath dark lenses/masks/fringe or confuse downward gaze with closed eyes. Clear frames and lids are separate constructions; smaller full white disks do not solve missing lid coverage. For tinted glasses record frame, tint and observed visibility. See [feature, hair and contour decisions](references/character-environment.md).

Protect user-liked character drawing during environment changes. E's quiet grouped hair/white-eye/face planes and I's more articulated swept hair/bent feature curves/concentrating pose are an accepted range, not a requirement to keep reducing accents. Source likeness, eye fidelity and counts are separate. For animals inspect species silhouette, joints/action, facial abstraction and grouped body/fur planes together; a correct silhouette or smaller eyes alone is insufficient. Focal-crow evidence does not establish mammal rendering.

## Build each material at its own scale

Assign only the regional operations needed for this scene:

- Subjects: silhouette/feature contours and connected base/shadow planes.
- Plants/earth: connected crown/clump/landform bases with richer directional groups varying through branches, volume, overlap and distance. A good canopy does not prove foreground leaves or distant shrubs are right. Choose plant-compatible mark shapes; cypress curls are not universal leaf anatomy.
- Water: first distinguish a quiet contained volume, flat local fragments or rolling open-surface bands; only then choose local marks. Group flow/shadows/reflected color around the scene's forms. Correct reflections alone do not fix an evenly stamped field.
- Wood/built objects: structural edges/planes first; broad surface-aligned bands and selective wear/material marks. Inspect continuity and edges as well as direction; wide chipped bands can still resemble grain rendering.
- Sky: select quiet planes, broken bands or connected cloud/flow masses separately from water/ground. Full coverage can remain calm through low contrast; open planes are also valid. Use the matching sky mode.

Rich smooth rounded marks are supported. Preserve layered environmental density while judging form, direction and variation; do not clean every background into sparse symbols. The distinction follows surface and role: a foreground plant stays richly marked, a far person remains cartoon. Keep designed clothing patterns separate from material texture. For mixed smooth/transparent materials and masked or crowded faces, inspect the region-specific edges, planes and visible openings; see [conditional material/feature checks](references/character-environment.md). Shared viewpoint, contacts/overlap and bounded lighting integrate the systems without a cutout halo or a global bristle/canvas/impasto finish.

## Assign reference operations

Inspect selected full originals before attachment. Choose a primary whole-drawing anchor for this scene's hardest contour/material organization, adding originals only for missing operations. Usually a character/interaction original and an environment original suffice; a suitable drawn guide may need only one environment anchor. These are options, not tool weights or a fixed attachment count. Save actual order and regional roles.

Specify the exact region: ordinary people and a portrait depicted on a tablet/canvas can differ inside one original. Transfer its contour/plane/grouping operations, leaving donor identities, props, silhouette signatures and arrangement behind. A cypress original can supply internal crown groups without supplying a cypress skyline. Crops aid inspection; full originals supply hierarchy. Attach only role-matched images and choose a coherent sky mode.

Positively design replacement masses instead of relying only on exclusions. Inspect contamination even when excluded. If material construction repeatedly fails, change a meaningful anchor/conditioning/layout decision. For a different palette map connected dark bases, larger middle-value groups and smaller light accents rather than copying hues. Use only relevant prompt detail:

> New ink-contour and opaque-color comic illustration. [Original] supplies [named regional construction]; [photo/guide] supplies [content/contact]. Subject: [individual shape/feature decisions], connected planes, moderate selective contours. Setting: [unequal near/middle/far masses], [material group directions], [sky mode]. Keep [counts/contacts/framing/view]. Transfer operations without donor story/identity. [Scene-specific exclusions], no global painted or photographic finish.

## Choose the lightest useful route

- **Text:** one complete scene with selected originals. A focal-animal guide is a conditional option after failed appropriate construction, not a requirement.
- **Photo:** direct complete translation remains available for untested or successful sources. For a source/task repeatedly restoring portrait hair/features or controlling the setting, use a suitable drawn subject/contact group early. Establish one when needed and inspect the actual drawing and contacts against the photo; a neutral backdrop, flat shading or stage completion alone does not qualify it. A diagnosed structural redraw may use the source-derived drawing plus a role-matched original without the raw photo. Preserve suitable expression; inspect protected regions again. Generate the complete scene from a usable guide without automatically reattaching the raw photo.
- **Revision:** define protected content/drawing, failing region and replacement operation. Inspect the entire result after the bounded edit. Reuse suitable source-derived guides when identity/action fit; existence or relative preference is not blanket approval. An edit is a new drawing, not an exact composite.

Use [workflow recipes](references/workflows.md) for conditional head reconstruction, framing changes and viewpoint repair. Do not impose empty-background/character/integration passes, overlays or a ritual polishing chain. After repeated failure, change meaningful conditioning or report the limitation. Semantic-only source descriptions are diagnostic when identity disappears, not validated photo translation.

## Inspect and deliver

Save exact prompt, attachment roles/order and output in the user's project. For photo/guide routes retain a source comparison. Judge separately:

1. Content/framing: identity cues, expression, action, counts, required visible extent and actual contacts/occlusion.
2. Subject: individualized shape/feature construction and connected planes, not outlined portrait anatomy or a generic replacement.
3. Materials: large forms at thumbnail scale; belonging of direction/grouping/scale at detail scale. Check each visible depth and patterned surfaces separately.
4. Whole scene: shared space, unequal near/middle/far masses and detail/contrast, overlaps, intentional calm/activity, palette/light, no donor story or halo.

If `inspect_fancy_pair` is available or requested, use the [optional inspection recipe](references/workflows.md): choose content-pair or regional-style mode from its current schema, and keep per-region model results separate from visual and human acceptance.

For strong fisheye, plan camera height/tilt, optical-center region, subject/held-object near-to-far scale and coordinated upper, upright/opening and floor/support bends. Inspect all families: a huge hand/bowed counter in a mostly straight room fails. Re-layout with unequal masses rather than a symmetric tunnel or one enlarged limb; a dark circular border is not proof. Geometry, face and every material pass separately; this is a drawing plan, not calibrated lens simulation.

Retain S/T contour balance, quiet-subject/rich-environment E/G and later E/I character preferences with their [limits](references/evidence.md). A pleasing region or relative preference does not approve the whole skill. For development compare a retained baseline and test changed decisions on another scene, recording conditioning/sampling differences. Unseeded examples establish no success rate. For ordinary use show the strongest complete candidate and identify material mismatches concisely.

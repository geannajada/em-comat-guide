# EM COMAT Study Guide

**35 new figures extracted from all three supplied textbooks, with diagnosis and key clues beside each image.** The two earlier attributed images remain, for 37 image assets total.

## Find the images

Open `index.html`. On Overview, use the **Version 11 · 35 new textbook figures** buttons to jump directly to a system gallery. The same **Textbook image gallery** appears near the top of each illustrated tab. Expand it to see the images and notes. Select an image to enlarge it; use its reference button to open the related diagnosis/management section.

Galleries are grouped by system to preserve the existing layout and avoid loading every image into the reading path at once. Diagnoses and clues are visible beside each image, without an answer-reveal step. On narrow screens the explanation stacks below its image.

## Upload to GitHub

1. Extract `EM_COMAT_Study_Guide_GitHub.zip`.
2. Replace `index.html` and upload the complete `images` folder, including its new `textbooks` subfolder.
3. Include `README.md`, `CONTENT_AUDIT.md` and `IMAGE_SOURCES.md` alongside the HTML.
4. Commit the extracted files and let the existing Pages deployment complete.

Do not upload only the HTML: the local image folders are required. No build or external script library is needed. The ZIP itself is not the home page. Local images work offline; external source links need internet access.

## What changed

- 10 figures from First Aid Step 2 CK 11e, 15 from Clinical Pattern Recognition, and 10 from Harrison 22e.
- ECGs and conduction comparisons; chest and abdominal imaging; intracranial bleeding; pregnancy ultrasound; renal obstruction and urine sediment; fractures/crystals; retinal emergencies; zoster and spinal infection.
- Every image has a diagnosis, visual clue, decision connection, source page/figure and recorded credit. Original arrows and labels are retained. No AI reconstruction or diagnostic retouching was used.
- Added direct gallery navigation and links from images to the corresponding clinical reference.
- Preserved the v10 clinical material, 152 numbered reference blocks, 39 pathways, all system tabs, search, emphasis and reference controls.

`IMAGE_SOURCES.md` records image provenance and extraction scope. `CONTENT_AUDIT.md` remains the v10 clinical audit; version 11 adds visual material rather than repeating the full medical audit.

## Scope and privacy

The user confirmed permission to publish the extracted textbook figures. Figure credits are preserved in the guide/source ledger; this does not independently establish a new open license. Source PDFs and private score reports are not packaged. The separate private study-priorities file is also excluded.

Images are selected for their educational value and the user's repair priorities, not a claim of measured NBOME image frequency. Some compressed textbook originals have limited resolution. A full-size view cannot recover details absent from the original.

## Validation

All 35 extracted crops were visually inspected against the source pages and captions. Automated testing checks original navigation/search behavior and the new galleries, image assets, source captions and reference links. All 42 existing behavior checks and 93 new image/gallery checks passed, with no runtime errors. Static checks also confirmed retained IDs, local image files, descriptive alt text and package privacy.

Browser layout rendering has not been reverified because the local browser preview was previously blocked by security policy. Crop inspection and DOM checks do not substitute for browser visual/mobile inspection. No live GitHub repository or deployed site was changed.

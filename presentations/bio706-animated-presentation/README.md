# BIO 706 · Phage therapy

A cinematic scientific browser presentation. No account, installation, API key, subscription, or internet connection is required. All illustrations, fonts, styles, animations, content and notes are embedded in the HTML file.

## Open and present — no coding

1. Download and unzip `BIO706-Browser-Presentation.zip`.
2. Open `BIO706-Phage-Therapy.html` in Google Chrome. If it opens in another app, right-click the file, choose **Open with**, and select **Google Chrome**.
3. Press **F** for fullscreen. Use **Right arrow** or **Space** to advance; **Left arrow** to go back.
4. Present slides **1–12**. They are paced for approximately **12 minutes 35 seconds** including short animation pauses. Slides **13–15** contain the full references; slide **16** is backup for questions.

You can also download the HTML file alone: it is the complete offline presentation. Keep the file on your computer rather than trying to present it from an email or cloud-storage preview. External DOI links require internet only when you choose to open them.

## Controls

| Key / control | Action |
|---|---|
| Right arrow / Space / Page Down | Next slide |
| Left arrow / Shift+Space / Page Up | Previous slide |
| Home / End | First / final slide |
| F | Fullscreen; press Esc to exit |
| O | Slide overview; select a slide to jump |
| R | Replay the current slide’s animations |
| A | Pause / resume motion |
| M | Toggle reduced motion |
| N | Show / hide original speaker notes |
| ? | Help |

Slide 3’s lytic sequence moves through attachment, genome entry, replication/assembly, and lysis. Click a numbered stage to hold it. Press **R** to restart the sequence. Slide navigation remains manual, so animations do not force you to rush your talk.

The deck respects the system’s reduced-motion preference. In that mode charts remain fully drawn, and the lytic stages can be selected manually. Screen reader labels and keyboard controls are included. A phone can display the deck, but a landscape laptop/projector is recommended for presenting.

## Speaker notes and timing

- `speaker-notes.html`: readable notes for a second device, printing, or rehearsal.
- `speaker-notes.md`: the same original notes in plain text, with pacing guidance.
- **N** opens notes on the same screen as the deck; do not open it while sharing the presentation screen if you want notes to stay private. This is not a dual-window presenter console.
- Speak the **Graduate presentation script** sections. The **Simple explanation** and **Sources and optional technical detail** sections are study aids and are not part of the timed talk.
- The 12 main scripts contain 1,481 words. At 125 words/minute, speech takes about 11:51; approximately 44 seconds of animation viewing and pauses brings the planned total to 12:35. Rehearse once and adjust your delivery.

## Scientific fidelity

This is a redesign of the supplied research, not a new literature review or independent re-verification of every cited source. The supplied bibliographic entries and clinical findings have been retained. All original speaker-note paragraphs are preserved verbatim, including qualifications about source access and study limitations.

- **PhagoBurn:** 27 randomized; 25 in the efficacy population; phage n=12 vs standard-care n=13. Bars show reported median times of 144 vs 47 hours to sustained bacterial-load reduction. HR 0.29 (95% CI 0.10–0.79), P=0.018. The chart does not portray clinical cure. Intended titre 10^6 PFU/mL vs approximately 10^2 delivered after decline; this does not prove that a higher dose would work. Median confidence intervals are retained in speaker notes, not drawn as invented symmetric error bars.
- **BX004-A Part 1:** nine adults, seven active vs two placebo. Primary safety/tolerability endpoints were met. Separate bars show the selected reported between-group contrasts: 1.9 log10 CFU/g lower at day 4 (P=0.035) and 2.7 at day 15 (P=0.029). They are not connected into a fabricated time course. These are exploratory microbiological findings, not established lung-function or exacerbation benefit. The 2026 author correction is included.
- **Dedrick:** single-patient compassionate use, not controlled efficacy evidence; clinical improvement occurred during combined care. The BPs modification is not depicted as tail-fiber redesign.
- All biological illustrations are original, conceptual SVG drawings. They are not microscopy, species-specific reconstructions, measured burst sizes, experimental plaque counts, or procedural laboratory instructions. Animated particles are illustrative and do not encode dosage, transport speed, or measured pharmacokinetics.
- The selected tailed-phage model is illustrative; it is not intended to represent every bacteriophage morphology or lifestyle.

## Included files

- `BIO706-Phage-Therapy.html` — complete animated, offline-ready presentation.
- `BIO706-Static-Handout.pdf` — static backup; animations are not preserved in PDF.
- `speaker-notes.html` and `speaker-notes.md` — full original notes with a 12:35 pacing plan.
- `source-content.md` and `source-content.json` — unmodified copies of the earlier extraction.
- `preview-contact-sheet.jpg` — overview of all slide designs.
- `validation-report.json` — automated browser and preservation checks.
- `FONT-LICENSE.txt` — license for bundled DejaVu fonts.

The original PowerPoint was not modified and is not overwritten by any of these files. This deck is independent of Codex Slides and does not use its authentication or generation endpoint.

## Technical details (optional)

The presentation uses an equivalent lightweight browser slide framework built from standard HTML, CSS, JavaScript and SVG. No Reveal.js or GSAP download is needed. It deliberately has no external runtime dependencies. The editable HTML template, CSS and JavaScript are supplied in `authoring/` in the ZIP; you do not need them to present. Build and test scripts remain in the cloud workspace. FontTools and Playwright were already installed in the cloud environment and were used to build and test the artifact; they are not required on your computer.

Cloud Chromium blocks `file://` navigation by administrator policy. Browser testing therefore loads the exact HTML over local HTTP, disables network access for navigation/animation tests, and also checks the embedded document in a fresh offline page. This cloud policy is separate from opening a downloaded local HTML file in your own Chrome. If your institution also blocks local HTML, ask its IT support about allowed presentation hosting; no paid hosting is necessary.

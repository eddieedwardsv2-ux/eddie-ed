# How I modeled my entire Airbnb with Opus 5.5

Author: [@SimbasJungles](https://x.com/SimbasJungles)  
Published: 2026-10-11T14:51:53.000Z  
[Original post](https://x.com/SimbasJungles/status/2109295930021208144) · [Original article](https://x.com/i/article/2109286119401492480)

## Article summary

The author describes converting apartment references into a walkable interior through Claude-driven Blender modeling and Unreal rendering. Inputs included a floor plan, room photographs, design references and purchasable furnishings. Several short feedback rounds corrected geometry, materials and lighting.

Cinematic illumination, shadows and atmospheric effects contributed heavily to the final appearance. The author reports diagnosing a fog-distance setting that hid sunbeams in the small apartment. GPU profiling then reduced unnecessary reflection and shadow work and introduced adaptive resolution.

The resulting experience reportedly supports different times of day, individual lamp controls, camera settings and furniture changes through a separate planner. The author describes a Python-based creation pipeline with repeated screenshot inspection and correction.

Reported stack: Claude Code/Opus 5.5, Blender 5.2, Unreal 5.8 and RTX 4090. Performance, time, usage and screenshot counts are the author's claims; this archive does not independently verify or reproduce the build.

## Archive coverage

- Nine original visual images are saved in `images/`.
- Three longer text screenshots are linked and summarized in [image-notes.md](image-notes.md).
- All 12 image source URLs and the embedded video's metadata are indexed in [source.json](source.json).
- The article is summarized, not reproduced verbatim. Full article and long screenshot transcription require user-supplied content or appropriate permission.
- Images inspected visually; small shopping-cart text and fine floor-plan labels were not fully transcribed.
- Video: source variants recorded; footage not downloaded or inspected.
- Capture date: 2026-10-12. Source retrieved through the FxTwitter API after direct X retrieval failed and Tavily required reauthentication.

Status: **PARTIAL INGESTION — linked summary, nine images, screenshot summaries; no full article or full OCR transcript.**

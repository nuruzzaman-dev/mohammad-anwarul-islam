# Hero Video Validation

The provided Pixabay page resolves to the official clip `Mind, Brain, Psychology. Free Stock Video` (video 290117). The direct medium download endpoint returned HTTP 403, so the official page HTML was inspected and the accessible Pixabay CDN source was used instead: `https://cdn.pixabay.com/video/2025/07/08/290117_large.mp4`.

The uploaded managed asset is `/manus-storage/hero-neurology_b77e9575.mp4`. The hero now renders it as a visual-only `<video>` with autoplay, muted playback, inline mobile playback, no controls, no pause handler and `pointer-events: none`. Each time the clip ends, the code selects a random start position and resumes playback, creating randomized loop cycles.

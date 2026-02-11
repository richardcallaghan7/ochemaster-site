# OcheIQ Landing Page Screenshots

Screenshots for the landing page at https://ocheiq.com

## Current Screenshots (Build #56)

| Filename | Description | Used In |
|----------|-------------|---------|
| `score.png` | Session detail — 90 Elite Mechanics, all 5 metric bars | Hero, Features |
| `results.png` | Insights tab — "Dart 1 was rushed", pattern detection, recent sessions | Hero, Features |
| `consistency.png` | Throw overlay paths view with coaching drill | Hero, Features |
| `coaching.png` | Wrist heatmap with release cluster zone | Features |
| `replay-overlay.png` | Skeleton overlay with trajectory path and phase nav | Features |
| `upload.png` | Record tab — OcheIQ logo, Today's Focus, Analyze Video | Solution section |

## Image Positioning (CSS Classes)

### Hero Section (Phone Mockups)
- `results.png` - `pos-results-hero` (top center) - Shows "Dart 1 was rushed"
- `score.png` - `pos-score-hero` (center 38%) - Shows 90 Elite score ring
- `consistency.png` - `pos-consistency-hero` (center 12%) - Shows throw overlay

### Solution Section (Phone Mockup)
- `upload.png` - `pos-upload` (top center) - Shows clean upload UI

### Features Section (Feature Cards)
- `replay-overlay.png` - `pos-replay` (center 45%) - Shows skeleton overlay
- `consistency.png` - `pos-consistency` (center 20%) - Shows throw paths
- `score.png` - `pos-score` (center 45%) - Shows score ring and metrics
- `coaching.png` - `pos-results` (top center) - Shows heatmap and coaching

## How to Update Screenshots

1. Take new screenshots from TestFlight or Simulator (iPhone 17 Pro)
2. Copy to this folder with appropriate name
3. Update `index.html` positioning classes if needed
4. Deploy: `vercel --prod`

## Screenshot Guidelines

- **Format**: PNG (used by index.html)
- **Resolution**: iPhone 17 Pro (1206x2622) for website, resize to 1320x2868 for App Store
- **Mode**: Dark mode (matches landing page theme)
- **Content**: Show real analysis data, not empty states
- **Scores**: Aim for good scores (85+) for impressive presentation

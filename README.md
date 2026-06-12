# Stop Loss · Genesis 2026

> How we taught a marketing engine to think like a trading desk — cut the losers in hours, compound the winners, learn from every trade.

**Team:** Sushant Sachan · Suyash Mishra
**Submission:** Genesis 2026 · Marketing · Growth

## View the deck

Live: `https://<username>.github.io/stop-loss-deck/`

## Run locally

Open `index.html` in **Chrome** or **Edge** (best Web Speech API support).
Click ▶ **Start Presentation**. Zivon walks through all 13 slides in ~3:30.

## Controls

| Action | Key |
|---|---|
| Next slide | → / Space |
| Previous slide | ← |
| Skip narration | Esc |
| Pause / Resume | HUD ⏸ |
| Stop | HUD ■ |

## Files

| File | Purpose |
|---|---|
| `index.html` | The 13-slide presentation (self-contained) |
| `stop_loss_mascot.png` | Zivon mascot · cover slide |
| `yes_do_it.mp4` | Closing video · slide 13 |
| `.nojekyll` | Disables Jekyll on GitHub Pages |

## Deploy to GitHub Pages

```bash
gh repo create stop-loss-deck --public --source=. --push
gh api -X POST /repos/{owner}/stop-loss-deck/pages \
  -f source[branch]=main -f source[path]=/
```

Wait ~30 seconds, then visit `https://<your-username>.github.io/stop-loss-deck/`.

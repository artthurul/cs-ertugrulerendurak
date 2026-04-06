<!--
  Author: Ertugrul Eren Durak
  Website: https://www.ertugrulerendurak.com/
  Project: Frame
  Built: 2026-04-06
  Live URL: https://cs.ertugrulerendurak.com/
-->

# Frame

An automated cinematic website pipeline that takes a single prompt from research to live deployment — nineteen AI agents, one continuous camera move, zero manual steps between.

**Live site:** https://cs.ertugrulerendurak.com/
**Portfolio:** https://cs.ertugrulerendurak.com/projects/
**GitHub:** https://github.com/artthurul/frame-studio

| Property | Detail |
|---|---|
| Subject | Automated cinematic website pipeline — flagship homepage |
| Built by | [Ertugrul Eren Durak](https://www.ertugrulerendurak.com/) |
| Built on | 2026-04-06 |
| Tech | HTML, CSS, JavaScript — single self-contained file, no frameworks |
| Libraries | GSAP 3.13, ScrollTrigger, SplitText, Lenis 1.2.3 |
| Deploy | Vercel — auto-deploy on push |

## What this site does

- Scroll-driven video scrubbing: the hero sequence runs at `video.currentTime` controlled by scroll progress
- CSS space descent simulation: canvas starfield, Earth arc gradient, cloud diffusion, laptop reveal in darkness, zero-gravity UI components
- Cursor dissolve effect on all headlines via GSAP SplitText
- Interconnected section transitions — no hard cuts between sections
- Portfolio grid reading `/projects/feed.json` — updated automatically after every new pipeline build
- Film grain + vignette overlay via CSS `body::before` / `body::after`

## How the pipeline built this

```
AGENT-01  Research & topic selection
AGENT-02  Creative planning & build-context.md
AGENT-03  Visual direction & cinematic prompts
AGENT-05  Brand naming
AGENT-06  Higgsfield image generation (2K start/end frames)
AGENT-07  Higgsfield video generation (kling-3.0, 6s)
AGENT-08  Backend configuration (vercel.json, robots.txt, sitemap)
AGENT-09  Frontend build (this file)
AGENT-10  SEO & article writing
AGENT-11  Security audit
AGENT-13  Signature & attribution
AGENT-12  GitHub repo creation & Vercel deploy
AGENT-14  Portfolio feed update
AGENT-15  Supervisor verification
```

## License
MIT © 2026 Ertugrul Eren Durak

# Thomas Mooney

**Scroll-driven 3D, generative geometry, and small tools that people actually use.**

I'm a front-end developer and English teacher. I build interactive pieces in Three.js (including the new WebGPU renderer), computational geometry studies, and the apps and site my students learn from. Most of it is TypeScript, and every project below is deployed and live, not just a repo.

**Open to freelance projects:** scrollytelling pages, interactive 3D for museums and cultural organisations, and generative pattern work. Email [thomasmmooney@yahoo.com](mailto:thomasmmooney@yahoo.com).

<p>
  <a href="https://jameel7007.github.io/fatihah-manuscript/"><img src="https://raw.githubusercontent.com/Jameel7007/fatihah-manuscript/main/docs/readme/hero-ending.jpg" alt="Al-Fātiḥah: seven verses standing in gold" width="32%" /></a>
  <a href="https://jameel7007.github.io/rosette/"><img src="https://raw.githubusercontent.com/Jameel7007/rosette/main/docs/readme/finished.jpg" alt="Rosette in Tesserae: a finished zellige panel" width="32%" /></a>
  <a href="https://jameel7007.github.io/muqarnas/"><img src="https://raw.githubusercontent.com/Jameel7007/muqarnas/main/docs/media/muqarnas-hero.gif" alt="A muqarnas vault rising from its plan" width="32%" /></a>
</p>

## 3D and geometry

| Project | What it is | Built with | |
| --- | --- | --- | --- |
| [Al-Fātiḥah](https://github.com/Jameel7007/fatihah-manuscript) | The opening sūrah as a manuscript being made: a parchment unrolls, a scribe writes the seven āyāt in ink, and the words rise into gold as you scroll. | TypeScript, Three.js WebGPU + TSL, HarfBuzz | [Live](https://jameel7007.github.io/fatihah-manuscript/) |
| [Muqarnas](https://github.com/Jameel7007/muqarnas) | A computational reconstruction of a thirteenth-century muqarnas vault from its two-dimensional plan. Exact ℚ(√2) geometry, a construction plan, a watertight mesh, and a real-time scroll-driven render. | TypeScript, Three.js, WebGPU | [Live](https://jameel7007.github.io/muqarnas/) |
| [Rosette in Tesserae](https://github.com/Jameel7007/rosette) | A Moroccan zellige panel laid piece by piece: Hankin-method strapwork, 10,209 cut tiles dropped by a vertex shader, and frame-exact MP4 export. | JavaScript, Three.js, GLSL, WebCodecs | [Live](https://jameel7007.github.io/rosette/) |
| [Order in Space](https://github.com/Jameel7007/order-in-space) | A geometry-first, scroll-driven study of polyhedral construction. A pure-TypeScript kernel generates the Platonic and Archimedean solids and FCC sphere packings, independent of any renderer. | TypeScript, Three.js | [Live](https://jameel7007.github.io/order-in-space/) |
| [Misbaḥa](https://github.com/Jameel7007/misbaha) | A 3D strand of prayer beads you count with. Ninety-nine beads simulated with hand-written position-based physics, a prayer rug in natural dyes, and a colour system checked on the rendered pixels. | JavaScript, Three.js, Vite | [Live](https://jameel7007.github.io/misbaha/) |
| [Endless Rose](https://github.com/Jameel7007/endless-rose) | An endless prayer hall for dhikr: walk a T-plan hypostyle one bay per count, lit by the real day where you are, with a new zellige rose laid in the dome every round. | JavaScript, Three.js, GLSL, Vite | [Live](https://jameel7007.github.io/endless-rose/) |
| [From the Point](https://github.com/Jameel7007/from-the-point-site) | A scroll-driven Islamic sacred geometry drawing, constructed from a single point. | Three.js | [Live](https://jameel7007.github.io/from-the-point-site/) |
| [Masters of the Design](https://github.com/Jameel7007/masters-of-design-geometry-study) | An interactive study of a mathematically generated Sufi Enneagram as a field for eleven Naqshbandi principles. | TypeScript | [Live](https://jameel7007.github.io/masters-of-design-geometry-study/) |

## Tools for teaching

| Project | What it is | Built with | |
| --- | --- | --- | --- |
| [Lesson Error Tracker](https://github.com/Jameel7007/error-tracker) | A local-first app for language tutors. Log what a student said and the correction, and it ranks each student's recurring errors as persistent, improving, or new. | React, TypeScript, Vite, Vitest | [Live](https://jameel7007.github.io/error-tracker/) |
| [Thomas's Classroom](https://github.com/Jameel7007/thomas-classroom) | The site my students learn from: a complete A0 to C1 English curriculum for adult learners, 114 lessons, with method and booking pages. | Astro | [Live](https://jameel7007.github.io/thomas-classroom/) |

## How I work

- Domain logic stays pure and separate from the UI, so it can be tested without a browser. That is where most of my tests live.
- Scroll-driven pieces are a pure function of scroll position, so they run backwards exactly and never drift.
- Everything deploys automatically from `main`. The application projects also run typecheck, tests, and build in CI before they ship.
- READMEs explain why a design decision was made, including the ones I got wrong first.

# Thomas Mooney

Software developer and English teacher. I build small, local-first web tools, computational geometry studies, and the site my students learn from. Most of it is TypeScript, and all of it is deployed and usable, not just a repo.


## Projects

| Project | What it is | Built with | |
| --- | --- | --- | --- |
| [Lesson Error Tracker](https://github.com/Jameel7007/error-tracker) | A local-first app for language tutors. Log what a student said and the correction, and it ranks each student's recurring errors as persistent, improving, or new. | React, TypeScript, Vite, Vitest | [Live](https://jameel7007.github.io/error-tracker/) |
| [Muqarnas](https://github.com/Jameel7007/muqarnas) | A computational reconstruction of a thirteenth-century muqarnas vault from its two-dimensional plan. Exact ℚ(√2) geometry, a construction plan, a watertight mesh, and a real-time scroll-driven render. | TypeScript, Three.js, WebGPU | [Live](https://jameel7007.github.io/muqarnas/) |
| [Order in Space](https://github.com/Jameel7007/order-in-space) | A geometry-first, scroll-driven study of polyhedral construction. A pure-TypeScript kernel generates the Platonic and Archimedean solids and FCC sphere packings, independent of any renderer. | TypeScript, Three.js | [Live](https://jameel7007.github.io/order-in-space/) |
| [Masters of the Design](https://github.com/Jameel7007/masters-of-design-geometry-study) | An interactive study of a mathematically generated Sufi Enneagram as a field for eleven Naqshbandi principles. | TypeScript | [Live](https://jameel7007.github.io/masters-of-design-geometry-study/) |
| [From the Point](https://github.com/Jameel7007/from-the-point-site) | A scroll-driven Islamic sacred geometry drawing, constructed from a single point. | Three.js | [Live](https://jameel7007.github.io/from-the-point-site/) |
| [Thomas's Classroom](https://github.com/Jameel7007/thomas-classroom) | The site my students learn from: a complete A0 to C1 English curriculum for adult learners, 114 lessons, with method and booking pages. | Astro | [Live](https://jameel7007.github.io/thomas-classroom/) |

## How I work

- Domain logic stays pure and separate from the UI, so it can be tested without a browser. That is where most of my tests live.
- Everything deploys automatically from `main`. The application projects also run typecheck, tests, and build in CI before they ship.
- READMEs explain why a design decision was made, including the ones I got wrong first.

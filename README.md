<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:111827,55:2563EB,100:14B8A6&text=Aswathy%20S&fontColor=FFFFFF&fontSize=44&fontAlignY=36&desc=Full-Stack%20Developer%20%7C%20Python%20%2B%20Django%20%7C%20Applied%20AI&descAlignY=58&animation=fadeIn" alt="Aswathy S profile banner" />

<a href="mailto:saswathy974@gmail.com">
  <img src="https://img.shields.io/badge/Available%20for-Software%20Developer%20Roles-14B8A6?style=for-the-badge" alt="Available for software roles" />
</a>
<a href="https://github.com/Axwathy">
  <img src="https://img.shields.io/badge/GitHub-Axwathy-111827?style=for-the-badge&logo=github" alt="GitHub Axwathy" />
</a>
<a href="https://www.linkedin.com/in/aswathy-s-dev">
  <img src="https://img.shields.io/badge/LinkedIn-Aswathy%20S-2563EB?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Aswathy S" />
</a>

</div>

---

```text
Developer profile
-----------------
I build full-stack applications where clean backend systems, useful interfaces,
and AI-assisted workflows meet. My projects are not just demos: they include
authentication, APIs, async jobs, search, ML pipelines, deployment notes, and tests.
```

## What I Build

| Product area | What I have built | Evidence |
| --- | --- | --- |
| AI-assisted SaaS | Recruitment platform with resume parsing, semantic search, ranking, analytics, notifications, and candidate/recruiter portals | `SkillScout` |
| Browser computer vision | Webcam hand-tracking game with fingertip slicing, Canvas rendering, physics, particles, scoring, and unit tests | `Zlice` |
| Applied deep learning | Video deepfake detection pipeline using frame sampling, face detection, U-Net enhancement, ResNet50 classification, and majority voting | `TruthSight` |
| Production backend patterns | JWT cookies, CSRF handling, DRF throttling, tenant-scoped APIs, Celery jobs, Redis, OpenAPI docs, Docker Compose | `SkillScout` |

---

## Project Case Studies

<details open>
<summary><strong>SkillScout - AI Recruitment SaaS</strong></summary>

<br />

**Repository:** [github.com/Axwathy/SkillScout](https://github.com/Axwathy/SkillScout)

SkillScout is my strongest full-stack project: an AI-assisted recruitment system with separate recruiter and candidate experiences. It covers job management, public applications, resume uploads, parsing, semantic matching, candidate ranking, interview preparation, analytics, notifications, and batch screening.

**What makes it strong**

- Django REST Framework backend organized into domain apps for accounts, organizations, jobs, candidates, AI engine, interviews, pipeline, batch jobs, analytics, notifications, and shared utilities.
- Resume intelligence pipeline with PDF/DOCX extraction, structured parsing, Pydantic validation, Gemini/Ollama fallback logic, sentence-transformer embeddings, and pgvector search.
- Transparent ranking model combining semantic similarity, skill match, and experience match instead of hiding decisions inside an LLM.
- Production-style backend decisions: HTTP-only JWT cookie auth, CSRF enforcement hooks, API throttling, OpenAPI docs, Redis, Celery, Docker Compose, Vercel/Railway deployment configuration.
- Next.js/React/TypeScript frontend with recruiter dashboards, candidate portal, semantic search, pipeline UI, analytics charts, batch upload, and application detail flows.
- 115 backend pytest functions covering auth, tenant isolation, resume parsing, ranking, search, analytics, batch processing, notifications, and pipeline behavior.

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-B00020?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-2563EB?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</details>

<details open>
<summary><strong>Zlice - Webcam Hand-Tracking Game</strong></summary>

<br />

**Repository:** [github.com/Axwathy/Zlice](https://github.com/Axwathy/Zlice)  
**Live:** [zlice.netlify.app](https://zlice.netlify.app/)

Zlice is a lightweight browser game controlled through webcam hand movement. It uses MediaPipe hand landmarks to track the index fingertip and translates fast swipe motion into fruit slicing.

**What makes it strong**

- Real-time hand tracking with MediaPipe Tasks Vision in the browser.
- Canvas 2D game loop with fruit spawning, bombs, particles, sliced halves, trails, score state, timer state, and responsive rendering.
- Fingertip smoothing, missed-frame handling, swipe velocity thresholds, and point-to-segment collision math.
- Gameplay polish with combo scoring, bomb penalties, localStorage high scores, start/game-over screens, and visual feedback.
- 30 Vitest tests for tracking math, slice detection, entity physics, spawn constraints, and state behavior.

**Stack**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Canvas](https://img.shields.io/badge/Canvas%202D-FF7A59?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-00AEEF?style=flat-square)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

</details>

<details open>
<summary><strong>TruthSight - Deepfake Video Detection</strong></summary>

<br />

**Repository:** [github.com/Axwathy/truthsight-deepfake-detection](https://github.com/Axwathy/truthsight-deepfake-detection)

TruthSight is a Flask web application that accepts uploaded videos and predicts whether they are real or fake through a frame-level deep learning pipeline.

**What makes it strong**

- Secure upload flow with file type validation for common video formats.
- OpenCV frame sampling, dlib face detection, optional U-Net frame enhancement, and ResNet50 classification.
- Majority-vote aggregation across analyzed frames with confidence reporting.
- Clear README documentation with model files, setup steps, performance notes, limitations, and future improvements.

**Stack**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ResNet50](https://img.shields.io/badge/ResNet50-DC2626?style=flat-square)
![U--Net](https://img.shields.io/badge/U--Net-7C3AED?style=flat-square)

</details>

---

## Stack Map

<div align="center">

<img src="https://skillicons.dev/icons?i=python,django,flask,js,ts,react,nextjs,tailwind,html,css,postgres,redis,docker,git,github,vercel&perline=8" alt="Skill icons" />

</div>

| Category | Tools |
| --- | --- |
| Backend | Python, Django, Django REST Framework, Flask, REST APIs, JWT auth |
| Frontend | Next.js, React, TypeScript, Tailwind CSS, HTML, CSS, Canvas 2D |
| AI / ML | TensorFlow, Keras, OpenCV, dlib, ResNet50, U-Net, sentence-transformers, Gemini API |
| Data | PostgreSQL, pgvector, SQLite, Redis |
| Infrastructure | Docker, Docker Compose, Celery, Vercel, Railway, GitHub Actions |
| Testing | pytest, pytest-django, Vitest, Ruff, ESLint |

---

## Engineering Signals

```text
SkillScout backend tests     115 pytest test functions
Zlice browser game tests      30 Vitest test cases
Main backend framework        Django REST Framework
Main frontend framework       Next.js / React / TypeScript
Most used project themes      SaaS, AI workflows, computer vision, search, ranking
```

---

## GitHub Snapshot

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Axwathy&show_icons=true&hide_border=true&theme=react&rank_icon=github&card_width=420" height="170" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Axwathy&layout=compact&hide_border=true&theme=react&langs_count=8&card_width=340" height="170" alt="Top languages" />

<br /><br />

<img src="https://github-readme-streak-stats.herokuapp.com?user=Axwathy&theme=react&hide_border=true&border_radius=8&card_width=760" alt="GitHub streak stats" />

</div>

---

## Current Direction

- Building stronger Django and DRF systems with clean domain boundaries.
- Improving AI product features that are explainable, testable, and useful.
- Sharpening frontend dashboard design with React, Next.js, and TypeScript.
- Learning better deployment, performance, and production-readiness patterns.

---

## Contact

<div align="center">

<a href="mailto:saswathy974@gmail.com">
  <img src="https://img.shields.io/badge/saswathy974%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://www.linkedin.com/in/aswathy-s-dev">
  <img src="https://img.shields.io/badge/aswathy--s--dev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://github.com/Axwathy">
  <img src="https://img.shields.io/badge/Axwathy-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

<br /><br />

<strong>Open to entry-level Software Developer, Python Developer, Full-Stack Developer, and AI application development roles.</strong>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=95&color=0:14B8A6,55:2563EB,100:111827&section=footer" alt="Footer wave" />

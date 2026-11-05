# AGENTS.md — Rules for working on this site

Personal site for Yuqi Meng, served via GitHub Pages (murphymeng0818.github.io). Static HTML/CSS only, no build step.

## What to publish
- Content comes from `Yuqi_Meng_Resume.pdf`, in the same section order: Education, Internship Experience, Research Experience, Others.
- Contact links: LinkedIn (https://www.linkedin.com/in/yuqimeng), GitHub (https://github.com/MurphyMeng0818), email (ym3119@columbia.edu).
- Never invent or embellish facts, numbers, titles, dates or links. If something is missing or unclear, ask first.
- Keep wording of resume bullets faithful; trim only for layout, never change meaning or figures.
- Do not publish anything not already in the CV, LinkedIn or GitHub profile (e.g. home address, transcripts, GPA beyond what the CV states, client names beyond what the CV states).
- The CV phone number is shown on the page at the owner's request ("include all information"); remove it if asked.
- Deal and client details come from internship work: do not add confidential detail beyond what the CV already says.

## When to publish
- Do NOT `git push`, deploy, or otherwise publish to GitHub (or anywhere else) unless the owner explicitly says so in that message. Approval for one push does not carry over to later ones.
- Local previews (opening `index.html` in a browser) are fine.
- Do not commit unless asked.

## When to ask me first
- Before pushing, deploying, or changing the repo's remote/settings.
- Before deleting, renaming or overwriting any existing file (including the PDF and photo).
- Before adding third-party scripts, trackers, analytics, fonts loaded from external CDNs, or forms.
- Before adding content that is not in the CV (new sections, blog, projects, testimonials).
- Before changing the visual identity (colors, tone) or the section order.

## Style
- Vibe: professional, restrained, readable. No gimmicks, animation only for subtle hover/scroll feedback.
- Palette: Columbia blue (`#B9D9EB` light, `#75AADB` mid) with deep navy (`#0B2545`) for text/headers on a white / very light blue background. Define colors as CSS variables.
- Typography: system font stack or a serif/sans pairing available locally; no external requests.
- Navigation: streamlined, a single sticky top bar with anchors to sections (Education, Experience, Research, Others, Contact). Same order as the CV.
- Layout: single page, max width ~1000px, responsive down to phone width, accessible contrast (WCAG AA), semantic HTML, visible focus states, `prefers-reduced-motion` respected.
- Keep it to plain `index.html` with inline CSS unless it grows; keep assets in the repo root.

## Before finishing any change
- Open the page in the browser and check it.
- List every file created or modified.

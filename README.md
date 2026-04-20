# Hertie DSL — Deep Learning (GRAD-E1394)

**Course website: [hertie-school-deep-learning-e1394.github.io](https://hertie-school-deep-learning-e1394.github.io)**

A Jekyll-based course website for the Deep Learning course at [Hertie Data Science Lab](https://github.com/hertie-data-science-lab). Built on the DSL course website template, forked from [kazemnejad/jekyll-course-website-template](https://github.com/kazemnejad/jekyll-course-website-template).

## Quick start (via `roster.py`)

```bash
python3 roster.py --new-semester f2025 \
  --org Hertie-School-Intro-Data-Science-E1339 \
  --instructors simonmunzert
```

This clones the template, fills in `_config.yml` and `hertie-semester.yml`, and pushes to `{org}.github.io`.

## Manual setup

1. Use this repo as a template (click "Use this template" on GitHub)
2. Name the new repo `{your-course}.github.io`
3. Edit `_config.yml` - fill in course name, semester, instructor info
4. Edit `_data/people.yml` - add instructors and TAs
5. Enable GitHub Pages: Settings → Pages → Source: GitHub Actions
6. Push — the site deploys automatically

## What to edit each semester

| File | What to change |
| --- | --- |
| `_config.yml` | Course name, semester, code, instructor |
| `_data/people.yml` | Instructors and TAs |
| `semesters/{code}/hertie-semester.yml` | Roster for that cohort (one file per semester — preserved historically) |
| `_lectures/*.md` | One file per lecture |
| `_assignments/*.md` | One file per assignment |
| `schedule.md` | Weekly schedule |
| `index.md` | Homepage welcome text |

## Branding

Hertie colours are set in `_sass/_user_vars.scss`.

## Part of

[Hertie Data Science Lab](https://github.com/hertie-data-science-lab)
# Waypoint course library

Courses and lessons for [Waypoint](https://github.com/sergio-27), the learning tool that lives in your IDE. Learners who
turn on **Use the shared course library** (`waypoint.library.share`) get these instead of spending their own AI tokens.

Everything here is written by Waypoint's library pipeline, never uploaded by learners: shared lessons contain code that
runs on other people's computers. Every coding exercise with tests was run in a throwaway container: its tests pass on the
reference solution and fail on the starter code. Lessons whose code does more than an exercise needs are left out.

| File | What |
|---|---|
| `index.json` | Courses (keywords, level, size, tokens it took to write them) and the keys of the lessons that exist |
| `courses/<id>.json` | A course, like Waypoint's "Export path" |
| `lessons/<key>.json` | One lesson per task content, shared by every course with the same task |

Served at `https://sergio-27.github.io/waypoint-library/`. Do not edit by hand: the pipeline rewrites it.

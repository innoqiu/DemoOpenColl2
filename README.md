# DemoOpenColl2

This is a lightweight OpenCollab target task repo.

It intentionally does not contain the OpenCollab app. The app, prompts, and
agent protocol live in [innoqiu/OpenCollab](https://github.com/innoqiu/OpenCollab).

This repo stores only:

- `TASK_BRIEF.md`: the human-readable task brief.
- `opencollab/TTask_Status.json`: tiny structured brief summary.
- `opencollab/Task_Status.json`: shared task interface state.
- `opencollab/Task_Status.schema.json`: schema for the shared status file.

To visualize this project, clone OpenCollab locally and configure it:

```bash
npm run ocb -- def --project-dir=../DemoOpenColl2 --repo=innoqiu/DemoOpenColl2 --brief=TASK_BRIEF.md --actor=mira --signature=MI --color=#65b8a6
npm run ocb -- init
```

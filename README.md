# DevOps Git Demo

Small project to practice Git workflows: branches (main/dev/feature), PRs, tags, and docs.

## Structure
- `scripts/hello.sh` – demo script
- `docs/TASK_LOG.md` – what I did, with screenshots/notes

## How to run
bash scripts/hello.sh

## Workflow used
- Branches: main (protected), dev (integration), feature/* (work)
- PRs: feature -> dev, then dev -> main
- Tags: v1.0.0 (annotated)

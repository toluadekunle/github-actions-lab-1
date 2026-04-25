# GitHub Actions Lab 1

My first GitHub Actions workflow — built as part of the Cloudboosta Cloud DevOps Training programme.

## 🎯 Try the Interactive Quiz

Test your understanding of GitHub Actions Lab 1:

**👉 [Take the Quiz](https://toluadekunle.github.io/github-actions-lab-1/)**

11 questions covering workflows, triggers, runners, YAML syntax, and more. Instant feedback on multiple choice questions and model answers for short-answer questions.

## What's in this Repository

- `.github/workflows/hello-workflow.yml` — A working GitHub Actions workflow with three triggers:
  - `push` to `main`
  - `pull_request` to `main`
  - Manual `workflow_dispatch` button
- `index.html` — Interactive quiz site (served via GitHub Pages)

## What the Workflow Does

When triggered, the workflow runs on a fresh Ubuntu runner and:

1. Prints a greeting
2. Shows who triggered the run (`github.actor`)
3. Displays system information about the runner
4. Reports which event fired the run (`github.event_name`)

Check the [Actions tab](../../actions) to see live runs and their logs.

## Lab Outcomes

By completing this lab, you can:

- Explain what GitHub Actions is and why teams use it
- Identify the five core building blocks: events, jobs, runners, steps, and actions
- Write a valid workflow YAML file from scratch
- Trigger a workflow using `push`, `pull_request`, and `workflow_dispatch`
- Read workflow logs and debug common YAML errors
- Use GitHub context variables inside a workflow

## What's Next

**Lab 2** introduces `actions/checkout` to pull repository code onto the runner, install dependencies, run tests, and use the `matrix` feature to run jobs in parallel across multiple language versions.

---

*Cloudboosta Cloud DevOps Training · GitHub Actions Module · Lab 1*

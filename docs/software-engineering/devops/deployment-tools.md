---
layout: page
title: Deployment Tools
parent: DevOps
grand_parent: Software Engineering
permalink: /docs/software-engineering/devops/deployment-tools
---

# Deployment Tools

This page contains a list of various software deployment tools.
The focus is currently on the "new crop" of deployment tools and companies that have popped up in the past 5 or so years.

Includes tools that focus on frontend website deployment (eg Vercel/Netlify) and full-stack/server deployments (eg Fly.io). Some things are focused around deploying container workloads, but that is not the only applicable technology.

Many of these companies offer more than just deployment tooling as well.

## Deploy To Other Platforms/Servers

- [Argo](https://argoproj.github.io/)
- [Capistrano](https://capistranorb.com/)
- [Dagger](https://dagger.io/)[^1]
- [MRSK](https://mrsk.dev/)
- [Spinnaker](https://spinnaker.io/)
- [Waypoint](https://www.waypointproject.io/)

## All-in-one Platforms (eg Heroku-like)

- [CapRover](https://caprover.com/)
- [Deno Deploy](https://deno.com/deploy)
- [fly.io](https://fly.io)
- [Harness](https://www.harness.io/)
- [Heroku](https://www.heroku.com/)
- [Netlify](https://www.netlify.com/)
- [Railway](https://railway.app/)
- [Render](https://render.com/)
- [Vercel](https://vercel.com/)

## Out of Scope

- General purpose CI, workflow automation, and script runners are currently excluded from this list.

For example, [GitHub Actions](https://github.com/features/actions), [GitLab CI/CD](https://docs.gitlab.com/ee/ci/), Jenkins, Travis, CircleCI, Drone CI, etc. These are all technically capable of being used to deploy software but they require external scipts or tools to do so.

[^1]: Dagger is not really a *deployment* tool but rather a complete engine for defining and running CI/CD pipelines in code.
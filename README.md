# Monorepo with Turbo

## Code Structure

`/apps` contains two seperate client side Next.js apps:

- Student
- Recruiter

`/packages` contains:

- UI Library
- TSConfig
- Config

Apps uses packages and is shared.

## Deployment Status

Student Deployed at: https://student-lemon.vercel.app/
Recruiter Deployed at: https://recruiter-three.vercel.app/

Changes in `/packages/ui` will lead to rebuilding the `apps/*`

In this way, we have shared UI lib and config; with two different apps hosted differently in a single mono-repo!

# Docker Learning Project

A hands-on, day-by-day Docker practice repository.

This project is organized as 16 markdown lessons. Each lesson has a clear objective and runnable commands so you can practice core Docker concepts from setup to a mini project.

## Learning Path

- Day 01: Verify Docker setup
- Day 02: Images and tags
- Day 03: Container lifecycle
- Day 04: Build first Docker image
- Day 05: Build cache and no-cache
- Day 06: Environment variables
- Day 07: Volumes and persistence
- Day 08: Bind mounts
- Day 09: Docker networks
- Day 10: Docker Compose basic stack
- Day 11: Multi-stage builds
- Day 12: Security and user hardening
- Day 13: Logs, exec, and troubleshooting
- Day 14: Registry push and pull
- Day 15: Cleanup and system reset
- Day 16: Mini project (dockerized notes app)

## Repository Structure

- `01-setup-check.md` to `16-mini-project.md`: Daily exercises

## How To Use

1. Open a lesson file in order, starting from `01-setup-check.md`.
2. Read the `What This File Does` section.
3. Run the commands under `Task` in your terminal.
4. Move to the next day only after completing the current task.

## Prerequisites

- Docker Desktop (or Docker Engine + CLI)
- A terminal with Docker available in PATH

## CI

This repository includes a GitHub Actions workflow that:

- verifies README exists
- checks all day files include required sections
- confirms each day file includes a bash code block

Workflow file: `.github/workflows/ci.yml`

# Super-resolving an Image (SISR)
Literature review and structured notes for Single Image Super-Resolution (SISR).

## Project Info
- **Degree / Module:** MSc Scientific Computing and Data Analysis (MiSCADA)
- **Track:** Computer Vision and Robotics
- **Institution:** Durham University
- **Candidate:** Chenyu Wei
- **Supervisor:** Prof. Paolo Remagnino
- **Academic Year:** 2025–2026

## Project Overview
This project investigates **Single Image Super-Resolution (SISR)**: learning a mapping from low-resolution (LR) images to high-resolution (HR) images.  
The focus is on:
1) building a clear taxonomy of modern SR approaches (CNNs, Transformers, GAN/perceptual, real-world/blind, efficient SR);
2) critically comparing methods under consistent evaluation settings;
3) preparing reproducible baselines and an evaluation protocol (PSNR/SSIM and, where relevant, efficiency metrics).

## Objectives
- **Background & Context:** summarise SR fundamentals and common experimental settings.
- **Literature Synthesis:** compare architectures and identify research gaps and practical trade-offs.
- **Evaluation Protocol:** define datasets, degradation models, metrics, and reporting standards.

## Milestones & Assessment Timeline
| Deadline | Assessment Item | Weight | Status |
|---|---:|---:|---|
| 2026-05-01 | Literature Review & Project Plan | 15% | In progress |
| 2026-09-04 | Final Dissertation Report | 75% | Pending |
| Ongoing | Supervisor Mark (Meetings / Logs) | 10% | In progress |

## Repository Map
- `0_admin/` — milestones, meeting logs, decisions, risks
- `1_literature/` — paper collection and reading queue (links/PDF index)
- `2_notes/` — structured paper notes and code-reading notes (**main deliverable**)
- `3_code/` — baselines and experiments (when implemented)
- `4_experiments/` — datasets, evaluation protocol, run logs, results tables
- `5_writing/` — dissertation outline and writing drafts

## How to use this repo
1) Add a paper to `1_literature/reading_queue.md`
2) Create a structured note in `2_notes/papers/` using `2_notes/_template_paper.md`
3) Record key decisions and meeting outcomes in `0_admin/`
4) Keep evaluation settings consistent using `4_experiments/eval_protocol.md`

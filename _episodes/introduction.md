---
title: "HPC from a user perspective"
teaching: 20
exercises: 0
questions:
- "Why do researchers use HPC systems?"
- "What are some typical research applications on HPC systems?"
objectives:
- "Understand why researchers use HPC."
- "Be able to identify some key research application areas on HPC systems."
keypoints:
- "TBC"
---

## Why HPC?

- More complex to use than standard computing
- Individual processors are not really any more powerful

## How do researchers use HPC?

- Key technologies (user perspective):
  + SSH
  + vi/emacs
  + Modules: TCL/Lmod
  + Compilers
  + Software libraries
  + Python

### "Traditional" HPC

- Batch use
- Capability use

### Other HPC workflows

- Capacity: task farm (HTC)
- Workflow engines
- ML/AI

### Portability

- Traditional HPC portability: source code
- Package management (is difficult) - binary distributions often do not work (cf. Linux OS repos, conda, pip)
- Containerisation - issues with Docker leads to use of different technologies

### Barriers to use

- Linux command line
- Data transfer

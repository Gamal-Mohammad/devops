# DevOps – Git & Linux Basics

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

> First DevOps practice repository: Git basics, a Bash script and a Kubernetes Pod manifest.

## Overview

Hands-on **Git & GitHub** practice repository from the DevOps training track. It is used to practise the everyday Git workflow: cloning, committing, pushing and pulling, and resolving changes made both locally and on GitHub.

## Tech Stack

- **Git**
- **Bash**
- **Kubernetes**

## Repository Structure

```text
file1.txt
hello.sh
pod.yml
README.md
```

## Getting Started

```bash
git clone https://github.com/Gamal-Mohammad/devops.git
cd devops
```

### Deploy to Kubernetes

| File | Kind | Name |
|---|---|---|
| `pod.yml` | Pod | `lab1` |

```bash
kubectl apply -f pod.yml
kubectl get pods,svc
```

### Scripts

```bash
bash hello.sh
```

## What You Practise

- `git clone`, `git status`, `git add`, `git commit`
- `git push` / `git pull` between local and GitHub
- Editing files from both GitHub's web editor and the local machine
- Keeping a clean, linear history

## Author

**Gamal Mohammad**

[![GitHub](https://img.shields.io/badge/GitHub-Gamal--Mohammad-181717?logo=github)](https://github.com/Gamal-Mohammad)

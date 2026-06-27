# DevPulse — Real-Time GitHub Activity Dashboard

> A full-stack developer productivity tool that tracks GitHub activity across multiple repositories in real time — built with React, Node.js, and the GitHub API.

## Overview

DevPulse gives engineering teams a unified view of their GitHub activity — commits, pull requests, issues, and code review cycles — all in one interactive dashboard. Built to reduce manual progress reporting and surface bottlenecks before they slow teams down.

## Features

- Real-time tracking of commits, PRs, and issues across 10+ repositories simultaneously
- Interactive Chart.js visualizations with filters by repo, contributor, and time range
- Team health score based on PR turnaround time and review cycle length
- Sub-2-second load times via optimized API batching and response caching
- Deployed with CI/CD pipeline using GitHub Actions, Vercel (frontend), and Render (backend)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React, Tailwind CSS, Chart.js |
| Backend | Node.js, REST APIs, WebSockets |
| Integration | GitHub REST API v3 |
| Deployment | Vercel, Render, GitHub Actions (CI/CD) |

## Impact

- Reduced manual progress reporting time by 60% for a 3-member team
- Improved PR turnaround time by 35% by surfacing review bottlenecks visually
- Handles concurrent API calls across 10+ repos with sub-2-second response times

## Getting Started

# Clone the repo
git clone https://github.com/Samvar-Jain/devpulse.git

# Install dependencies
cd devpulse && npm install

# Add your GitHub token to .env
GITHUB_TOKEN=your_token_here

# Run locally
npm run dev

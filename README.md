# 🚀 Vercel + GitHub Actions Experiments  

[![Testing just curious to Know](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/main.yml/badge.svg)](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/main.yml)
[![Vercel Preview Deployment](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/preview.yml/badge.svg)](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/preview.yml) 
[![Vercel Production Deployment](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/production.yml/badge.svg)](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/production.yml)

---

## 📖 About
This repository is my **playground** for testing how GitHub Actions and Vercel deployments behave when:  
- Workflows **pass** ✅  
- Workflows **fail** ❌  
- Different branches trigger **preview** vs **production** builds  

---

## 🧪 Experiment Log  

| #  | Status      | Description                                                   | Background |
|----|-------------|---------------------------------------------------------------|------------|
| 1  | ❌ Fail     | Wrong config in `production.yml` & `preview.yml`, but `main.yml` works fine | 🟥 Red |
| 2  | ❌ Fail     | Added intentional failing step in production & preview         | 🟦 Aqua |
| 3  | ❌ Fail     | Another failing test in production & preview                   | 🟪 Purple |
| 4  | ✔️ Pass    | Passing setup in production & preview                          | 🟨 Yellow |
| 5  | ❌ Fail     | Failing again in production & preview                          | 🤎 Beige |
| 6  | ✔️ Pass    | Passing setup again in production & preview                    | 💚 Chartreuse |
| 7  | ❌ Fail     | Another failing step (chaos continues)                         | 🧡 Coral |
| 8  | ✔️ Pass    | Passing workflow restored                                      | 🟦 DarkCyan |
| 9  | ❌ Fail     | Final failing test for fun                                     | 🟪 BlueViolet |
| 10 | ✔️ Pass    | Passing test for fun                                           | ❤️ Crimson |
| 11 | ❌ Fail     | Failed in both production & preview                            | 🔵 DarkBlue |
| 12 | ❌ Fail     | Both production & preview failed together                      | 🌫️ DarkSlateGrey |
| 13 | ❌ Fail     | Failed in production only                                      | 🌸 LightCoral |
| 14 | ❌ Fail     | Failed in preview and passed in production                     | 🟦 MediumTurquoise |

---


## 🛠 How It Works
- **main.yml** → Runs simple test scripts.  
- **preview.yml** → Deploys to **Vercel Preview** when pushing to `main` branches.  
- **production.yml** → Deploys to **Vercel Production** when pushing to `main` branch.  

> 🔑 If a workflow step fails, deployment is **blocked** (once Vercel auto-deploy integration is disabled).  

---



## 🎯 Takeaway
This repo is just for fun & learning.  
The main lessons so far:  
- GitHub Actions stop on error by default.  
- Vercel needs repo auto-deploy disabled if you want Actions to control everything.  
- Failing on purpose is a great way to test CI/CD pipelines.  

## 🚀 Deployment  

🔗 [View Live on Vercel](https://github-actions-survives-vercel-fail.vercel.app/)  



<!-- # Vercel here checking thigs [![Testing just curious to Know](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/main.yml/badge.svg)](https://github.com/Basudev-Pokharel/github-actions-survives-vercel-fails/actions/workflows/main.yml)
-->
## I have configured now in vercel in **preview.yml** & **production.yml** 

## 1.wrong in preduction and preview .yml but main.yml is okay let's see and bgc:red
## 2.Now I have added failing in production and preview .yml files, bgc:aqua; 
## 3.Now I have added failing in production and preview .yml files, bgc:**purple**; 
## 4.Now I have added passing things in production and preview .yml files, , bgc:yellow; 
## 5.Now I have added failing in production and preview .yml files, bgc:**Beige**; 
## 6.Now I have added passing things in production and preview .yml files, , bgc:Chartreuse; 
## 7.Now I have added failing in production and preview .yml files, bgc:**coral**; 
## 8.Now I have added passing things in production and preview .yml files, , bgc:DarkCyan; 
## 9.Now I have added failing in production and preview .yml files, bgc:**BlueViolet**;  
## 10.Now I have added passing in production and preview .yml files, bgc:**Crimson**;  


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

| # | Description | Background |
|---|-------------|------------|
| 1 | Wrong config in `production.yml` & `preview.yml`, but `main.yml` works fine | 🟥 Red |
| 2 | Added intentional failing step in production & preview | 🟦 Aqua |
| 3 | Another failing test in production & preview | 🟪 Purple |
| 4 | Passing setup in production & preview | 🟨 Yellow |
| 5 | Failing again in production & preview | 🤎 Beige |
| 6 | Passing setup again in production & preview | 💚 Chartreuse |
| 7 | Another failing step (chaos continues) | 🧡 Coral |
| 8 | Passing workflow restored | 🟦 DarkCyan |
| 9 | Final failing test for fun | 🟪 BlueViolet |
| 10| Passing test for fun | 🟪 Crimson |

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




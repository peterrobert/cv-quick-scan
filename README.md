# CV Quick Scan

A Chrome extension that helps recruiters instantly understand any CV or LinkedIn profile in under 5 seconds by extracting key skills, estimating experience, and generating a structured candidate summary.

---

## 🚀 Problem

Recruiters and hiring managers often deal with:

- Hundreds of CVs per job posting
- Time-consuming manual CV screening
- Important candidates being missed due to overload
- Cognitive fatigue during hiring decisions

Reading every CV in detail is not scalable.

---

## 💡 Solution

CV Quick Scan reduces CV review time by transforming unstructured CVs into a **clean, structured summary** instantly.

Instead of reading full CVs, recruiters get:

- Candidate summary in seconds
- Key skills extraction
- Experience estimation
- Job match score
- Missing skills detection

The goal is simple:

> Help recruiters decide faster whether to shortlist a candidate.

---

## 🧠 Core Idea

A Chrome extension that overlays a recruiter-friendly summary panel directly on:

- LinkedIn profiles
- CV PDFs
- Job board candidate pages

It turns long-form CVs into structured decision data.

---

## ✨ Features (MVP)

### 🔹 CV Quick Scan Sidebar

- Instant CV analysis panel
- Appears on supported pages

### 🔹 Skill Extraction

- Extracts key technical and soft skills
- Normalizes variations (e.g., JS → JavaScript)

### 🔹 Seniority Detection

- Estimates level:
  - Junior
  - Mid-level
  - Senior

### 🔹 Experience Estimation

- Based on CV content patterns
- Years of experience approximation

### 🔹 Job Match Score (Optional Input)

- Compare CV against job description
- Outputs percentage match score (0–100%)

### 🔹 Missing Skills Detection

- Highlights gaps between candidate and job requirements

---

## 🧱 Product Structure

This project consists of 3 main parts:

---

## 🖥️ Tech Stack

### Landing Page (Web)

- Next.js (App Router)
- Tailwind CSS
- Framer Motion (optional)

### Chrome Extension

- Plasmo (or WXT)
- React
- TypeScript
- Chrome Extension Manifest V3

### Backend (Future)

- Ruby on Rails API.

---

## ⚙️ How It Works

1. User opens a CV or LinkedIn profile
2. User clicks “Scan CV” button
3. Extension extracts page content
4. System analyzes:
   - skills
   - experience
   - role type
5. Sidebar displays structured summary instantly

---

## 📊 Output Example

---

## 🎯 Target Users

- Recruiters
- HR professionals
- Hiring managers
- Staffing agencies

---

## 💰 Monetization Plan

### Free Tier

- Limited scans per day
- Basic CV summary

### Pro Tier ($5–10/month)

- Unlimited scans
- Job match scoring
- Saved candidates
- Export features

---

## 📦 MVP Scope

The MVP focuses ONLY on:

- Chrome extension sidebar
- Text extraction from CV/LinkedIn pages
- Basic skill matching logic
- Simple UI summary output

No backend required initially.

---

## 🚧 Roadmap

### Phase 1 (MVP)

- Chrome extension UI
- CV text extraction
- Basic skill detection
- Sidebar summary

### Phase 2

- Job description matching
- Improved scoring logic
- Save candidate feature

### Phase 3

- AI-powered summaries
- Multi-candidate comparison
- Recruiter notes system

### Phase 4

- Team collaboration features
- ATS integrations
- Analytics dashboard

---

## 🧠 Key Design Principle

> “Reduce recruiter decision time from minutes to seconds.”

Every feature must improve:

- speed of understanding
- clarity of decision
- reduction of cognitive load

---

## 🧪 Development Setup (Planned)

### Web (Next.js)

```bash
cd web
npm install
npm run dev
```

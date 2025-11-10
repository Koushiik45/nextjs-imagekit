# Next.js Cloud Image Manager (ImageKit)

**Cloud image manager built with Next.js + ImageKit**.  
Secure client uploads, on-the-fly responsive image transforms, CDN delivery, and a small admin gallery.

**Live demo:** https://<your-vercel-url>.vercel.app  
(If not deployed yet, remove this line.)

---

## Tech stack
- Next.js (App Router) + TypeScript
- ImageKit.io for upload tokens, transformations, CDN
- Tailwind CSS for UI
- Node.js API routes for secure token generation
- Vercel for deployment

---

## Features
- Secure client-side uploads using ImageKit upload tokens
- On-the-fly image resizing, cropping and quality transforms via ImageKit URLs
- Drag-and-drop upload UI with live preview
- Auth-ready structure (placeholder for NextAuth)
- Server-side API route that generates short-lived upload tokens (no secret exposure)
- Responsive gallery with pagination and basic metadata (filename, size, createdAt)

---



---

## Getting started — run locally

### Prerequisites
- Node 18+
- npm or pnpm
- ImageKit account (free tier available)

### Install
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
npm install

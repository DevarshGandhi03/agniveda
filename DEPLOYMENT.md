# Agniveda Deployment Guide

This app is built with TanStack Start and configured for **Cloudflare Pages**.

## ✅ Recommended: Cloudflare Pages

Your app is pre-configured for Cloudflare. Deploy in minutes:

1. Visit [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Go to **Workers & Pages** → **Create application** → **Pages** → **Connect to Git**
3. Select your `agniveda` repository
4. Build settings:
   - **Framework preset**: None (or TanStack Start if available)
   - **Build command**: `npm run build`
   - **Build output directory**: `.output/public`
5. Click **Save and Deploy**

## Alternative: Vercel/Netlify (Requires Configuration)

To deploy on Vercel or Netlify, you would need to:
- Remove Cloudflare-specific plugins
- Configure for their serverless platforms
- Update vite.config.ts

**Current setup is optimized for Cloudflare.**

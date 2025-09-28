# Prostate Health Bridge Page - ProstaVive

A high-converting bridge page for the ProstaVive product, designed to drive traffic from SixtyPlusUSA to the main product site.

## Overview

This is a specialized Next.js application that serves as a bridge page for the ProstaVive prostate health product. It's designed to convert visitors into customers by providing compelling product information and strong calls-to-action.

## Features

- **High-Converting Design**: Optimized for conversions with multiple CTAs
- **UTM Tracking**: Complete campaign tracking system for attribution
- **Responsive Design**: Mobile-first approach for all devices
- **ProstaVive Focus**: Dedicated to prostate health product promotion
- **Senior-Friendly**: Large fonts and easy-to-read design for men over 60

## Technology Stack

- **Next.js 15** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS v4** - Utility-first CSS framework
- **Framer Motion** - Smooth animations and transitions
- **Lucide React** - Beautiful, customizable icons

## UTM Tracking System

The site includes comprehensive UTM tracking for:
- Campaign attribution (`utm_source`, `utm_medium`, `utm_campaign`)
- Conversion tracking with Google Analytics and Facebook Pixel
- Real-time analytics dashboard
- Campaign performance monitoring

## Product Information

### ProstaVive Benefits
- Natural prostate health support
- Clinically researched ingredients
- Doctor-recommended formula
- Money-back guarantee

### Target Audience
- Men over 60
- Prostate health concerns
- Natural supplement seekers
- Health-conscious seniors

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

This site is configured for static export and can be deployed to:
- **Netlify** (recommended)
- **Vercel**
- **AWS Amplify**
- Any static hosting service

### Build Commands

```bash
npm run build
```

The build will create an `out` directory with static files ready for deployment.

### Subdomain Configuration

This site is designed to be deployed to a subdomain like:
- `prostate.sixtyplususa.com`
- `prostavive.sixtyplususa.com`

## Product Links

All CTAs link to: **https://prostavive.org/**

## Project Structure

```
prostate-health/
├── src/
│   ├── app/
│   │   ├── globals.css      # Global styles with CTA styling
│   │   ├── layout.tsx       # Root layout with UTM tracking
│   │   └── page.tsx         # Main ProstaVive bridge page
│   ├── components/
│   │   ├── UTMAnalytics.tsx # Real-time analytics dashboard
│   │   ├── UTMLink.tsx      # UTM-aware link component
│   │   └── UTMTracker.tsx   # UTM tracking context
│   └── lib/
│       └── utm-tracking.ts  # UTM tracking utilities
├── netlify.toml             # Netlify deployment config
└── package.json
```

## Conversion Optimization

- **Multiple CTAs**: Strategic placement throughout the page
- **Social Proof**: Customer testimonials and reviews
- **Urgency**: Limited-time offers and scarcity messaging
- **Trust Signals**: Money-back guarantee and doctor recommendations
- **Mobile Optimization**: Touch-friendly buttons and forms

## Analytics Integration

- Google Analytics (gtag) integration
- Facebook Pixel (fbq) integration
- Custom conversion tracking
- Real-time campaign monitoring
- Export functionality for data analysis

## License

© 2024 SixtyPlusUSA. All rights reserved.
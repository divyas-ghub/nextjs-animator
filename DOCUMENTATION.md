# Project Documentation

## Project Overview

**Next.js Animated Slider** is a reusable slider component built with **Next.js**, **React**, **Framer Motion**, and **Tailwind CSS**. It provides a smooth animated carousel experience with responsive layout, modern styling, and an easy integration path for Next.js applications.

## Key Features

- Smooth animations using `framer-motion`
- Responsive slider layout for desktop and mobile
- Tailwind CSS styling for utility-first customization
- Modular React component structure
- Next.js routing and static page support
- Easy setup and local development using npm scripts

## Repository Structure

- `components/`
  - `BackgroundImage.tsx` - background and visual styling layer
  - `Controls.tsx` - previous/next slider controls
  - `Header.tsx` - page header component
  - `OtherInfo.tsx` - additional site or slider information
  - `Progress.tsx` - animation progress indicators
  - `SlideInfo.tsx` - slide text, title, and button content
  - `SliderCard.tsx` - individual slide card implementation
  - `Slides.tsx` - slide container and animation logic
- `pages/`
  - `_app.tsx` - app wrapper and global styles import
  - `_document.tsx` - custom document markup
  - `index.tsx` - main landing page with slider
- `public/` - static assets and images
- `styles/` - Tailwind/global CSS styles
- `package.json` - project metadata, scripts, and dependencies
- `README.md` - quick start guide and overview

## Setup Instructions

### Prerequisites

- Node.js 18+ recommended
- npm, Yarn, or pnpm package manager

### Install Dependencies

```bash
npm install
# or
# yarn
# pnpm install
```

### Run Locally

```bash
npm run dev
```

Visit `http://localhost:3000` to preview the slider.

## Build and Production

```bash
npm run build
npm run start
```

## Development Scripts

- `npm run dev` - start development server
- `npm run build` - create production build
- `npm run start` - run built production server
- `npm run lint` - run lint checks

## Customization Guide

### Styling

The project uses Tailwind CSS. Customize utility classes in `components/` and `styles/globals.css`.

### Slide Content

Edit the slide data and content within `components/Slides.tsx` or update `SlideInfo.tsx` to match your project’s copy and layout.

### Component Layout

Use the modular components to extend the slider, add new controls, or embed it inside other pages.

## Notes

- The current package structure uses Next.js 13 and TypeScript.
- `framer-motion` handles the core animation behavior.
- `react-icons` provides iconography for controls and UI elements.

## Contribution

To contribute, follow the existing component conventions and keep styles consistent with Tailwind CSS. Submit improvements through pull requests, and update this documentation if you add new functionality.

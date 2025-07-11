# Astro Offline Page Starter

A lightweight, customizable offline page template built with Astro for robust web experiences.

---

This repository provides a modern and efficient starter template for implementing a customizable offline page for your web projects. Built with Astro, it ensures a fast, resilient, and user-friendly experience even when the internet connection is unavailable.

![offline-page-ui](offline-page-ui.png)

## Why an Offline Page?
A well-designed offline page prevents frustrating blank screens or browser errors when users lose connectivity. It informs them about the situation, maintains brand consistency, and can offer helpful suggestions or access to cached content, significantly improving the overall user experience.

## Key Features
- Astro Powered: Leverages Astro's performance benefits for a lightweight and fast-loading offline experience.

- Customizable UI: Easily adapt the look and feel (text, icons, colors) to match your brand's aesthetic.

- Service Worker Integration (Planned/Example): Designed to integrate seamlessly with Service Workers to cache the page and deliver it reliably when offline.

- Responsive Design: Ensures a consistent experience across various devices and screen sizes.

- Clear User Guidance: Provides helpful messages and actions for users encountering connectivity issues.

- Developer-Friendly: Clean code structure, easy to understand and extend.

## Technologies Used
- Astro: For building a fast, content-focused website.

- HTML/CSS: Core structure and styling.

- JavaScript: For any dynamic client-side interactions (e.g., Service Worker registration).

## Getting Started
To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js (v18.14.1 or higher) and npm (v9.5.0 or higher) installed.

### Installation

1. Clone the repository:
```sh
git clone https://github.com/web3senior/offline.git
cd offline
```

2. Install dependencies:
```sh
npm install # or yarn install / pnpm install
```

3. Start the development server:
```sh
npm run dev
```

## Why Astro for this?
Astro's focus on shipping minimal JavaScript by default makes it an ideal choice for an offline page. You want this page to load instantly and reliably, without heavy client-side dependencies. Astro's architecture ensures that only the necessary HTML and CSS are delivered, making it incredibly performant even in constrained network environments.

## Contribution
Feel free to fork this repository, open issues, or submit pull requests to suggest improvements or add new features! Your contributions are always welcome.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
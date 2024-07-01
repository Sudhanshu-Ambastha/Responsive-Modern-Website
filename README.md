# Responsive Modern Website
This project is a responsive modern website built with Next.js, TypeScript, and Tailwind CSS.

## Preview

<picture><img src="" width="100%"></picture>
## Getting Started
To create a new Next.js project, use the following command:

```bash
npx create-next-app@latest landingpage
```

## Project Setup
When prompted, configure the project as follows:
- TypeScript: Yes
- ESLint: No
- Tailwind CSS: Yes
- `src/` directory: No
- App Router: Yes
- import alias: No

Installation
Navigate to the project folder and install the dependencies:
```
cd landingpage
```
```
npm install
```

## Running the Development Server
Start the development server with:
```
npm run dev
```
Open http://localhost:3000 with your browser to see the result.

## Project Structure
The project structure is as follows:
```
landingpage/
├── components/
│   ├── buttons/
│   │   └── Button.tsx
│   ├── Camp.tsx
│   ├── Features.tsx
│   ├── Footer.tsx
│   ├── GetApp.tsx
│   ├── Guide.tsx
│   ├── Hero.tsx
│   ├── Navbar.tsx
├── constants/
│   └── index.ts
├── pages/
│   └── index.tsx
├── public/
│   ├── apple.svg
│   ├── android.svg
│   ├── camp.svg
│   ├── close.svg
│   ├── facebook.svg
│   ├── hilink-logo.svg
│   ├── instagram.svg
│   ├── location.svg
│   ├── map.svg
│   ├── menu.svg
│   ├── meter.svg
│   ├── phone.png
│   ├── play.svg
│   ├── star.svg
│   ├── tech.svg
│   ├── twitter.svg
│   ├── user.svg
│   └── youtube.svg
├── styles/
│   └── globals.css
├── tailwind.config.js
└── tsconfig.json
```

## Components
The project includes several reusable components:
- Button: A reusable button component with optional icons and variants.
- Camp: A component to display camping site information.
- Features: A component to list the features of the application.
- Footer: The footer of the website containing links and contact information.
- GetApp: A section to promote downloading the app.
- Guide: A component to guide users.
- Hero: The hero section of the homepage.
- Navbar: The navigation bar of the website.

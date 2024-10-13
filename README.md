## My personal portfolio CV website

![Astro Badge](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=fff&style=flat)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-0F172A?&logo=tailwindcss)
![GitHub stars](https://img.shields.io/github/stars/carlos-arriagadaCL/carlos-arriagadaCL.github.io)
![GitHub PRs](https://img.shields.io/github/issues-pr/carlos-arriagadaCL/carlos-arriagadaCL.github.io)
![GitHub forks](https://img.shields.io/github/forks/carlos-arriagadaCL/carlos-arriagadaCL.github.io)
![GitHub issues](https://img.shields.io/github/issues/carlos-arriagadaCL/carlos-arriagadaCL.github.io)

## 🛠️ Stack

- [**Astro**](https://astro.build/) - The next-gen web framework.
- [**Typescript**](https://www.typescriptlang.org/) - JavaScript with type syntax.

## 📖 Summary

### About this Repository:

This repository contains the source code for my personal website, built with Astro. The website is designed to showcase my professional profile, experience, projects, and education.

- I use [bun](https://bun.sh/) as my package manager.

### Project Structure:

```
project-root/
├── src/                   # Main source folder for the website
│   ├── components/        # Reusable UI components
│   ├── icons/             # Collection of icons used across the site
│   ├── layouts/           # Layout templates for different page structures
│   └── pages/             # Individual pages for the website
├── public/                # Static assets accessible in the root URL
│   └── themes/            # Theme files for styling
├── astro.config.mjs       # Astro configuration file
├── tailwind.config.mjs    # Tailwind CSS configuration for styling
├── tsconfig.json          # TypeScript configuration file
├── cv.json                # JSON file containing data for a printable CV
├── package.json           # Project metadata and dependencies
└── README.md              # Project documentation and instructions
```
Edit the `cv.json` file to personalize and generate a printable Portfolio/CV.

### Launch the Development Server:

```bash {"id":"01JA1ZPVQ054XX5HSXC7XC81B1"}
# Install the dependencies
bun install
```

```bash {"id":"01JA1RYR7FC004EQABVBBHG99M"}
# Run the app
bun run dev
```

Open [**http://localhost:4321**](http://localhost:4321/) in your browser to view the result 🚀

### Customisable colours:

Change the data-theme of `cv.json` and choose one of the colour themes defined in theme.css, red, blue, green, cyber and default, with its variants in dark mode, or create your own.

## 🧞 Commands

|     | Command         | Action                                                         |
| :-- | :-------------- | :------------------------------------------------------------- |
| ⚙️  | `dev` o `start` | Launches a local development server at `localhost:4321`.       |
| ⚙️  | `build`         | Checks for errors and creates a production build in `./dist/`. |
| ⚙️  | `preview`       | Local preview at `localhost:4321`                              |

CV JSON schema from [**jsonresume.org**](https://jsonresume.org/schema/)

Based on [**Bartosz Jarocki - Print-friendly, minimalist CV page**](https://github.com/BartoszJarocki/cv) and [**Miguel Ángel Durán - minimalist-portfolio-json**](https://github.com/midudev/minimalist-portfolio-json)

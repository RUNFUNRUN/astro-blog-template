# 🛸 Astro Blog Template

template by [OnWritingCode/simple-blog-template](https://github.com/OnWritingCode/simple-blog-template)

**Features**

- Full Markdown support.
- Separation between Markdown files and Astro pages
- Drafts directory for posts that aren't published yet
- Syntax Highlighting with Shiki
- Global styles directory
- RSS 2.0 generation

**Languages**

- TypeScript
- Sass (scss)

## 🚀 Quick Start

1. **Clone the repository**

```bash
git clone https://github.com/RUNFUNRUN/astro-blog-template.git
```

2. **Install dependencies**

```bash
bun install
```

3. **Set .env file**

```bash
cp .env.example .env
# then edit .env file
```

4. **Run the development server**

```bash
bun dev
```

## 💡 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public
└── src
    ├── components
    │   ├── layouts
    │   └── utilities
    ├── content
    ├── pages
    └── style
```

- _pages_ - This directory is significant for Astro. Files here become URLs.
- _components_ - Template parts, layouts, utilities, all go here.
- _content_ - Keep the content separate from the system for clearer separation.
- _style_ - Global SCSS styles.
- _public_ - A directory where to place any static files that need to be used on the site.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command            | Action                                       |
| :----------------- | :------------------------------------------- |
| `bun install`      | Installs dependencies                        |
| `bun dev`          | Starts local dev server at `localhost:3000`  |
| `bun run build`    | Build your production site to `./dist/`      |
| `bun run preview`  | Preview your build locally, before deploying |
| `bun run format`   | Format your code with Prettier               |
| `bun run lint`     | Lint your code with ESLint                   |
| `bun run lint:fix` | Lint your code with ESLint and fix issues    |

## 👀 Want to learn more?

Feel free to check out [Astro documentation](https://github.com/withastro/astro) or jump into [Astro's Discord server](https://astro.build/chat).

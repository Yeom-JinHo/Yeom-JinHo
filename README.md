# 👋 Hi, I'm Jinho Yeom

**Frontend Developer** focused on **Interactive UI** & **Performance**
- I’m passionate about visual presentation and currently focusing on interactive UI.
- With DJing as my hobby, I also have a deep interest in music. [Listen here](https://soundcloud.com/ye0m2)

---

## 🛠 Tech Focus
- **Core:** TypeScript, Vue, React, Next.js
- **UI & Motion:** Framer Motion, CSS Architecture
- **DX & Build:** Vite/Rollup, Storybook, Design System, Tree-shaking & bundle analysis

---

### 📫  Career

- [Hyundai Capital](https://about.hyundaicapital.com/main.hc?lang=ko) | Frontend Developer (2023.01 ~ )

---

### ⚡ Activity

- [ssafy](https://www.ssafy.com/ksp/jsp/swp/swpMain.jsp) (2022.01~2022.12)

---

### 📚 Projects

- [v-f-labs](https://v-f-labs-website-web.vercel.app?utm_source=github&utm_content=readme)  v-f-labs(wip)
- [@ui-layouts/mcp](https://www.npmjs.com/package/@ui-layouts/mcp) `@ui-layouts/mcp` provides AI assistants with several valuable tools to help them search, understand, and retrieve UI components from ui-layouts.com
---

### ⭐️ Open Source Contributions

I actively contribute to the tools I use in production — especially UI libraries, build tools, and DX utilities.

I enjoy turning real-world UI/UX issues (especially around responsiveness, Safari/iOS quirks, and DX) into reusable fixes in the open-source ecosystem.

![Jinho's GitHub Repository Contribution stats](https://github-contributor-stats.vercel.app/api?username=Yeom-JinHo&combine_all_yearly_contributions=true&hide=B)

#### UI Libraries & Design Systems

<a href="https://github.com/saadeghi/daisyui">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/saadeghi/daisyui?style=social&label=daisyui" style="height:25px;">
</a>

- [fix(mockup-phone): make layout responsive with aspect-ratio #4108](https://github.com/saadeghi/daisyui/pull/4108)  
  → Improved `mockup-phone` responsiveness using `aspect-ratio`, fixing layout issues across screen sizes.

<a href="https://github.com/magicuidesign/magicui">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/magicuidesign/magicui?style=social&label=magicui" style="height:25px;">
</a>

- [fix(safari): resolve iOS device video masking issue with DOM overlay (breaking change) #782](https://github.com/magicuidesign/magicui/pull/782)  
- [fix(iphone-15-pro): resolve iOS device video masking issue with DOM overlay (breaking change) #780](https://github.com/magicuidesign/magicui/pull/780)  
  → Refactored video rendering to a DOM overlay to fix Safari/iOS masking issues.
- [Chore: Fix build:docs&build:registry script loop & add engines field for consistency #806](https://github.com/magicuidesign/magicui/pull/806)  
  → Stabilized docs/registry build scripts and aligned Node.js engine constraints.
- [fix: AnimatedGridPattern hydration + effect loop + invalid DOM prop #858](https://github.com/magicuidesign/magicui/pull/858)  
  → Fixed hydration mismatch + React warning, and prevented an effect-induced render loop.

<a href="https://github.com/magicuidesign/mcp">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/magicuidesign/mcp?style=social&label=magicui/mcp" style="height:25px;">
</a>

- [docs: use CLI-safe MCP alias in README example  #6](https://github.com/magicuidesign/mcp/pull/6))  

<a href="https://github.com/ui-layouts/uilayouts">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/ui-layouts/uilayouts?style=social&label=ui-layouts" style="height:25px;">
</a>

- [refactor: migrate docs config from JSON to TypeScript with type safety #56](https://github.com/ui-layouts/uilayouts/pull/56)  
- [refactor: migrate from docsJson.dataArray to AllComponents and simplify component code #58](https://github.com/ui-layouts/uilayouts/pull/58)  
- [refactor:Docs Structure and Navigation System #61](https://github.com/ui-layouts/uilayouts/pull/61)  
- [refactor: reorganize component categories and simplify navigation groups #65](https://github.com/ui-layouts/uilayouts/pull/65)  
- [fix: remove duplicate components and fix malformed URLs in labs section #66](https://github.com/ui-layouts/uilayouts/pull/66)  
- [fix: add missing sparkles components and filter invalid recent pages #67](https://github.com/ui-layouts/uilayouts/pull/67)  
- [fix: revalidate confirmPassword field on password change #69](https://github.com/ui-layouts/uilayouts/pull/69)  
- [fix: resolve media modal component name inconsistency #71](https://github.com/ui-layouts/uilayouts/pull/71)  
- [refactor: implement global color token system for centralized theming #75](https://github.com/ui-layouts/uilayouts/pull/75)  
- [fix: resolve hydration mismatch in ThemeSwitch component #76](https://github.com/ui-layouts/uilayouts/pull/76)  
- [refactor: implement group-based pagination in DocsNavigation #77](https://github.com/ui-layouts/uilayouts/pull/77)  
- [fix: prevent drag icon scale from persisting during reordering #79](https://github.com/ui-layouts/uilayouts/pull/79)  
- [fix: improve reorder icon scale reset and add aria/touch optimizations #81](https://github.com/ui-layouts/uilayouts/pull/81)  
- [fix: restore marquee animation after Tailwind v4 migration #82](https://github.com/ui-layouts/uilayouts/pull/82)  
- [fix: restore Marquee animation and Tailwind v4 compatibility #83](https://github.com/ui-layouts/uilayouts/pull/83)  
- [fix: move @property declaration to top-level for gradient-border comp… #84](https://github.com/ui-layouts/uilayouts/pull/84)  
  → Long-term contributor to the `ui-layouts` design system: docs architecture, navigation, animation fixes, and theming via global color tokens.

<a href="https://github.com/karthikmudunuri/eldoraui">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/karthikmudunuri/eldoraui?style=social&label=eldoraui" style="height:25px;">
</a>

- [fix: misaligned layout in PricingSection by adjusting description height (minor issue) #39](https://github.com/karthikmudunuri/eldoraui/pull/39)  
  → Polished card layout alignment for a cleaner pricing section.

---

#### DX, Tooling & Type Utilities

<a href="https://github.com/vercel/turborepo">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/vercel/turborepo?style=social&label=turborepo" style="height:25px;">
</a>

- [examples: Remove redundant border declaration #11042](https://github.com/vercel/turborepo/pull/11042)  
  → Simplified example styles by removing redundant border declarations.

<a href="https://github.com/toss/es-toolkit">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/toss/es-toolkit?style=social&label=es-toolkit" style="height:25px;">
</a>

- [fix(isFinite): implement type predicate to narrow type to number #1511](https://github.com/toss/es-toolkit/pull/1511)  
- [fix(isSafeInteger): implement type predicate to narrow type to number #1510](https://github.com/toss/es-toolkit/pull/1510)
- [fix(toCamelCaseKeys): improve toCamelCaseKeys type inference for uppercase keys #1538](https://github.com/toss/es-toolkit/pull/1538)
  → Improved type safety by turning utility functions into proper type guards, enabling better inference in TypeScript codebases.

<a href="https://github.com/style-dictionary/style-dictionary">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/style-dictionary/style-dictionary?style=social&label=style-dictionary" style="height:25px;">
</a>

- [fix(example): format-helpers import path #1309](https://github.com/style-dictionary/style-dictionary/pull/1309)  
  → Fixed example import paths to prevent confusion for new users.


<a href="https://github.com/release-it/release-it">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/release-it/release-it?style=social&label=release-it" style="height:25px;">
</a>

- [chore: update dependencies to resolve security vulnerabilities #1273](https://github.com/release-it/release-it/pull/1273)  

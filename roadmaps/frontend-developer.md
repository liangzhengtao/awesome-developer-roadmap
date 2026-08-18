# Frontend Developer Roadmap

> A complete roadmap from Junior to Staff Frontend Engineer

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    FRONTEND DEVELOPER                        │
                           │                    Junior → Staff                            │
                           └─────────────────────────────────────────────────────────────┘
                                                    │
          ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
          │                                         │                                         │
          ▼                                         ▼                                         ▼
   ┌──────────────┐                        ┌──────────────┐                        ┌──────────────┐
   │   INTERN /   │                        │    JUNIOR     │                        │    INTERN     │
   │  BEGINNER    │                        │   DEVELOPER   │                        │   (0-6 mo)    │
   └──────┬───────┘                        └──────┬───────┘                        └──────────────┘
          │                                         │
          ▼                                         ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              FOUNDATIONS (6-12 months)                                       │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  HTML5  │  CSS3  │  JavaScript (ES6+)  │  Git  │  Responsive Design  │  Dev Tools           │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              FRAMEWORKS (12-18 months)                                       │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐                        │
   │    │     REACT       │    │      VUE        │    │    ANGULAR      │                        │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │                        │
   │    │  • React 18+    │    │  • Vue 3        │    │  • Angular 17+  │                        │
   │    │  • Hooks        │    │  • Composition  │    │  • Signals      │                        │
   │    │  • Redux/Zustand│    │  • Pinia        │    │  • RxJS         │                        │
   │    │  • Next.js      │    │  • Nuxt 3       │    │  • NgRx         │                        │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘                        │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              ADVANCED (18-36 months)                                         │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  TypeScript  │  Testing  │  State Management  │  Build Tools  │  Performance  │  SSR/SSG     │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SENIOR (3-5 years)                                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Architecture  │  Design Systems  │  Micro Frontends  │  Web Security  │  Accessibility     │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              STAFF+ (5+ years)                                               │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Technical Strategy  │  Cross-team Leadership  │  Innovation  │  Mentoring  │  RFC Design    │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Stage 1: Foundations (0-12 months)

### Skills Checklist

- [ ] **HTML5**
  - [ ] Semantic elements (header, nav, main, article, section)
  - [ ] Forms and validation
  - [ ] Accessibility (ARIA attributes, screen reader compatibility)
  - [ ] SEO fundamentals (meta tags, structured data)
  - [ ] Canvas and SVG basics

- [ ] **CSS3**
  - [ ] Box model, Flexbox, CSS Grid
  - [ ] Responsive design (media queries, fluid typography)
  - [ ] CSS Variables (custom properties)
  - [ ] Animations and transitions
  - [ ] CSS preprocessors (Sass/SCSS)
  - [ ] Tailwind CSS / CSS-in-JS basics

- [ ] **JavaScript (ES6+)**
  - [ ] Variables, data types, operators
  - [ ] Functions (arrow, higher-order, closures)
  - [ ] DOM manipulation
  - [ ] Event handling and delegation
  - [ ] Promises, async/await
  - [ ] ES modules (import/export)
  - [ ] Array methods (map, filter, reduce)
  - [ ] Destructuring, spread/rest operators
  - [ ] Error handling
  - [ ] Local Storage / Session Storage

- [ ] **Developer Tools**
  - [ ] Chrome DevTools (Elements, Console, Network, Performance)
  - [ ] VS Code setup and extensions
  - [ ] Git basics (clone, commit, push, pull, branch)

- [ ] **Package Managers**
  - [ ] npm / yarn / pnpm
  - [ ] package.json understanding
  - [ ] Semantic versioning

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| MDN Web Docs | Documentation | Free | https://developer.mozilla.org |
| freeCodeCamp | Course | Free | https://www.freecodecamp.org |
| JavaScript.info | Tutorial | Free | https://javascript.info |
| CSS-Tricks | Articles | Free | https://css-tricks.com |
| The Odin Project | Course | Free | https://www.theodinproject.com |
| Eloquent JavaScript | Book | Free | https://eloquentjavascript.net |

### Project Ideas

1. **Personal Portfolio Website** - Responsive portfolio with CSS Grid/Flexbox
2. **Todo App** - Vanilla JS with localStorage persistence
3. **Weather Dashboard** - Fetch API, async/await, DOM manipulation
4. **Landing Page Clone** - Pixel-perfect recreation of a popular site
5. **Interactive Quiz App** - Event handling, state management without framework

---

## Stage 2: Frameworks & Libraries (12-18 months)

### React Path

- [ ] **React Fundamentals**
  - [ ] JSX and component structure
  - [ ] Props and state
  - [ ] Event handling in React
  - [ ] Conditional rendering and lists
  - [ ] Forms in React (controlled components)

- [ ] **React Hooks**
  - [ ] useState, useEffect, useContext
  - [ ] useRef, useMemo, useCallback
  - [ ] Custom hooks
  - [ ] Rules of hooks

- [ ] **React Ecosystem**
  - [ ] React Router v6
  - [ ] State management (Redux Toolkit / Zustand / Jotai)
  - [ ] Data fetching (React Query / SWR)
  - [ ] Form handling (React Hook Form / Formik)
  - [ ] UI libraries (Material UI, Shadcn/ui, Ant Design)

- [ ] **Next.js**
  - [ ] App Router
  - [ ] Server Components vs Client Components
  - [ ] Server Actions
  - [ ] API Routes
  - [ ] Static and Dynamic rendering
  - [ ] Image optimization
  - [ ] Middleware

### Vue Path

- [ ] **Vue 3 Fundamentals**
  - [ ] Template syntax and directives
  - [ ] Composition API (setup, ref, reactive)
  - [ ] Props, emits, slots
  - [ ] Computed properties and watchers
  - [ ] Lifecycle hooks

- [ ] **Vue Ecosystem**
  - [ ] Vue Router
  - [ ] Pinia (state management)
  - [ ] VueUse (composable utilities)
  - [ ] Vuetify / PrimeVue / Element Plus

- [ ] **Nuxt 3**
  - [ ] File-based routing
  - [ ] Server-side rendering
  - [ ] Auto-imports
  - [ ] Server API routes

### Angular Path

- [ ] **Angular Fundamentals**
  - [ ] Components and templates
  - [ ] Data binding (interpolation, property, event, two-way)
  - [ ] Directives (structural, attribute)
  - [ ] Services and dependency injection
  - [ ] Observables and RxJS

- [ ] **Angular Ecosystem**
  - [ ] Angular Router
  - [ ] NgRx (state management)
  - [ ] Angular Material
  - [ ] Reactive Forms
  - [ ] HTTP Client and interceptors

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| React Official Docs | Documentation | Free | https://react.dev |
| Vue.js Official Docs | Documentation | Free | https://vuejs.org |
| Angular Official Docs | Documentation | Free | https://angular.dev |
| Frontend Masters | Courses | Paid | https://frontendmasters.com |
| Epic React by Kent C. Dodds | Course | Paid | https://epicreact.dev |
| Vue Mastery | Course | Free/Paid | https://vuemastery.com |

### Project Ideas

1. **E-commerce Store** - Product listing, cart, checkout (React/Vue/Angular)
2. **Social Media Dashboard** - Real-time data, infinite scroll, optimistic updates
3. **Project Management Tool** - Kanban board with drag-and-drop
4. **Recipe Finder App** - API integration, search, filters, favorites
5. **Chat Application** - WebSocket, real-time messaging, user authentication

---

## Stage 3: Advanced Frontend (18-36 months)

### Skills Checklist

- [ ] **TypeScript**
  - [ ] Basic types and interfaces
  - [ ] Generics
  - [ ] Utility types (Partial, Pick, Omit, Record)
  - [ ] Type guards and assertions
  - [ ] Declaration files (.d.ts)
  - [ ] Advanced patterns (mapped types, conditional types)

- [ ] **Testing**
  - [ ] Unit testing (Jest / Vitest)
  - [ ] Component testing (React Testing Library / Vue Test Utils)
  - [ ] Integration testing
  - [ ] E2E testing (Playwright / Cypress)
  - [ ] Test coverage and strategies
  - [ ] Mocking and stubbing

- [ ] **Build Tools**
  - [ ] Vite configuration
  - [ ] Webpack fundamentals
  - [ ] Babel and transpilation
  - [ ] Code splitting and lazy loading
  - [ ] Tree shaking
  - [ ] Environment variables

- [ ] **Performance Optimization**
  - [ ] Core Web Vitals (LCP, FID, CLS)
  - [ ] Lighthouse auditing
  - [ ] Bundle size optimization
  - [ ] Image optimization (WebP, AVIF, lazy loading)
  - [ ] Caching strategies
  - [ ] Rendering optimization (virtualization, memoization)
  - [ ] Performance monitoring (RUM, synthetic)

- [ ] **SSR/SSG**
  - [ ] Server-side rendering concepts
  - [ ] Static site generation
  - [ ] Incremental Static Regeneration
  - [ ] Streaming SSR
  - [ ] Hydration strategies

### Project Ideas

1. **Performance-Optimized E-commerce** - Lighthouse score 95+, SSR, code splitting
2. **Design System / Component Library** - Published to npm with Storybook
3. **Real-time Collaboration Tool** - CRDT/OT, WebSocket, optimistic updates
4. **Progressive Web App** - Offline support, push notifications, installable

---

## Stage 4: Senior Frontend (3-5 years)

### Skills Checklist

- [ ] **Architecture & Design Patterns**
  - [ ] Component architecture patterns
  - [ ] State management architecture
  - [ ] Feature-based folder structure
  - [ ] Monorepo tools (Nx, Turborepo)
  - [ ] API layer design (BFF pattern)

- [ ] **Design Systems**
  - [ ] Design token systems
  - [ ] Component documentation (Storybook)
  - [ ] Theming and customization
  - [ ] Versioning strategy
  - [ ] Cross-framework design systems

- [ ] **Micro Frontends**
  - [ ] Module Federation
  - [ ] Single-SPA
  - [ ] Web Components
  - [ ] iframe integration
  - [ ] Shared dependencies management

- [ ] **Web Security**
  - [ ] XSS prevention
  - [ ] CSRF protection
  - [ ] Content Security Policy
  - [ ] CORS understanding
  - [ ] Authentication flows (JWT, OAuth, SSO)
  - [ ] Dependency vulnerability scanning

- [ ] **Accessibility (a11y)**
  - [ ] WCAG 2.1 AA compliance
  - [ ] Screen reader testing
  - [ ] Keyboard navigation
  - [ ] ARIA patterns
  - [ ] Accessibility testing tools

- [ ] **Leadership Skills**
  - [ ] Code review proven patterns
  - [ ] Technical documentation
  - [ ] Mentoring junior developers
  - [ ] Cross-team collaboration
  - [ ] Technical decision-making

### Project Ideas

1. **Micro Frontend Platform** - Multiple teams, independent deployments
2. **Accessibility-First Component Library** - WCAG 2.1 AA certified
3. **Real-time Dashboard** - Complex data visualization, WebSocket, performance-optimized

---

## Stage 5: Staff+ Frontend Engineer (5+ years)

### Skills Checklist

- [ ] **Technical Strategy**
  - [ ] Technology evaluation and adoption
  - [ ] Migration strategies (incremental adoption)
  - [ ] Technical debt management
  - [ ] Build vs buy decisions
  - [ ] Platform thinking

- [ ] **Cross-team Leadership**
  - [ ] RFC and ADR authoring
  - [ ] Architecture review boards
  - [ ] Cross-team dependency management
  - [ ] Technical roadmap planning
  - [ ] Stakeholder communication

- [ ] **Innovation**
  - [ ] Emerging web standards (WebAssembly, WebGPU)
  - [ ] AI-powered frontend tools
  - [ ] Edge computing and edge rendering
  - [ ] Web3 and decentralized apps
  - [ ] Developer experience (DX) improvements

- [ ] **Organizational Impact**
  - [ ] Engineering culture building
  - [ ] Hiring and interview design
  - [ ] Knowledge sharing programs
  - [ ] Open source contributions
  - [ ] Conference speaking / technical writing

---

## Interview Preparation

### Common Interview Topics

1. **JavaScript Fundamentals**
   - Closures, prototypal inheritance, event loop
   - Promise implementation and async patterns
   - Debouncing and throttling

2. **Framework Deep Dives**
   - Virtual DOM / Reactivity systems
   - Component lifecycle and hooks
   - State management patterns

3. **System Design (Frontend)**
   - Design a component library
   - Design a real-time dashboard
   - Design a micro frontend architecture

4. **Coding Challenges**
   - Implement debounce/throttle
   - Build a infinite scroll component
   - Create a state management library
   - Build a virtual list component

5. **Behavioral Questions**
   - Technical decision-making examples
   - Conflict resolution
   - Cross-team collaboration

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Junior | 0-2 | $75,000 | $55K - $95K | $60K - $85K |
| Mid | 2-4 | $105,000 | $80K - $130K | $85K - $120K |
| Senior | 4-7 | $145,000 | $120K - $180K | $120K - $165K |
| Staff | 7-10 | $190,000 | $160K - $240K | $155K - $210K |
| Principal | 10+ | $240,000 | $200K - $320K | $190K - $270K |

*Note: Salaries vary significantly by location, company size, and industry. FAANG/top tech companies often pay 30-50% above median.*

---

## 中文版本 - 前端开发路线图

### 概述

这是一份从前端初级工程师到高级技术专家的完整成长路线图。

### 阶段一：基础入门（0-12个月）

**必学技能：**
- [ ] HTML5 语义化标签、表单验证、SEO基础
- [ ] CSS3 布局（Flexbox、Grid）、响应式设计、CSS变量
- [ ] JavaScript ES6+（变量、函数、DOM操作、异步编程）
- [ ] Git 版本控制基础
- [ ] npm/yarn 包管理

**推荐学习资源：**
- MDN Web 文档（免费）
- 现代 JavaScript 教程（javascript.info）
- freeCodeCamp 中文社区

**练手项目：**
1. 个人作品集网站
2. Todo 待办应用（纯 JS + localStorage）
3. 天气查询应用（调用公开 API）

### 阶段二：框架学习（12-18个月）

**React 路线：**
- [ ] React 18+ 核心概念（JSX、组件、Props、State）
- [ ] Hooks 深入（useState、useEffect、useContext、自定义 Hooks）
- [ ] React 生态（Redux Toolkit、React Query、React Router）
- [ ] Next.js 框架（App Router、Server Components、SSR）

**Vue 路线：**
- [ ] Vue 3 Composition API
- [ ] Pinia 状态管理
- [ ] Vue Router
- [ ] Nuxt 3 框架

**Angular 路线：**
- [ ] Angular 组件和模板
- [ ] RxJS 和依赖注入
- [ ] Angular Material
- [ ] NgRx 状态管理

### 阶段三：进阶提升（18-36个月）

- [ ] TypeScript 类型系统（泛型、工具类型、高级模式）
- [ ] 测试（Jest/Vitest、React Testing Library、Playwright）
- [ ] 构建工具（Vite、Webpack、代码分割）
- [ ] 性能优化（Core Web Vitals、Lighthouse、懒加载）
- [ ] SSR/SSG 服务端渲染

### 阶段四：高级前端（3-5年）

- [ ] 前端架构设计（组件模式、状态管理架构）
- [ ] 设计系统搭建（Design Tokens、Storybook、主题系统）
- [ ] 微前端架构（Module Federation、Single-SPA）
- [ ] Web 安全（XSS、CSRF、CSP、CORS）
- [ ] 无障碍访问（WCAG 2.1、屏幕阅读器、键盘导航）

### 阶段五：技术专家（5年以上）

- [ ] 技术战略规划（技术选型、迁移策略、技术债务管理）
- [ ] 跨团队领导力（RFC 编写、架构评审、技术路线图）
- [ ] 前沿技术探索（WebAssembly、WebGPU、AI 驱动工具）
- [ ] 组织影响力（工程文化建设、招聘设计、开源贡献）

### 薪资参考（人民币/年）

| 级别 | 经验 | 一线城市 | 二线城市 | 远程 |
|------|------|----------|----------|------|
| 初级 | 0-2年 | 15-25万 | 10-18万 | 12-20万 |
| 中级 | 2-4年 | 25-40万 | 18-30万 | 20-35万 |
| 高级 | 4-7年 | 40-65万 | 30-50万 | 35-55万 |
| 资深 | 7-10年 | 65-100万 | 45-70万 | 50-80万 |
| 专家 | 10年+ | 100-150万 | 60-100万 | 70-120万 |

---

*Last updated: 2024*
*Contributions welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md)*

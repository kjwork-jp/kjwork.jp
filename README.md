# kjwork.jp

`kjwork.jp` public top site — Phase 1 MVP.

Built with [Astro](https://astro.build). Deploys to Cloudflare Pages (TBD in P1-02).

## Project structure

```text
/
├── public/
├── src/
│   ├── components/
│   ├── layouts/
│   ├── pages/
│   │   └── index.astro
│   ├── styles/
│   └── consts.ts
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── secret-scan.yml
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Commands

| Command           | Action                                     |
| :---------------- | :----------------------------------------- |
| `npm install`     | Install dependencies                       |
| `npm run dev`     | Start dev server at `localhost:4321`       |
| `npm run build`   | Build production site to `./dist/`         |
| `npm run preview` | Preview production build locally           |

## Phases

| Phase  | Scope                                | Status    |
| :----- | :----------------------------------- | :-------- |
| P1-01  | Repository scaffold                  | Active    |
| P1-02  | Cloudflare Pages connection + www redirect | Pending |
| P1-03  | Initial public page content          | Pending   |

## Public content policy

- Permitted: public profile, work/portfolio links, contact info (email, SNS), general tech stack
- Prohibited: internal URLs, IPs, family info, passwords, API keys, tokens, management links

---

Planning repo: [kjwork-jp/kjwork_project](https://github.com/kjwork-jp/kjwork_project)

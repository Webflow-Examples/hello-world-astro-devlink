# Astro + Webflow Cloud

Example Astro app configured for [Webflow Cloud](https://webflow.com/cloud).

<p>
  <a href="https://webflow.com/dashboard/cloud/deploy?repo=https://github.com/Webflow-Examples/hello-world-astro">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="docs/readme/deploy-webflow-dark.svg" />
      <img src="docs/readme/deploy-webflow-light.svg" alt="Deploy to Webflow" width="172" height="32" />
    </picture>
  </a>
</p>

## Project structure

```text
/
├── docs/
│   └── readme/
├── public/
├── src/
│   ├── layouts/
│   ├── pages/
│   └── styles/
├── astro.config.mjs
├── wrangler.json
└── package.json
```

## Commands

| Command           | Action                                      |
| :---------------- | :------------------------------------------ |
| `npm install`     | Install dependencies                        |
| `npm run dev`     | Start dev server at `http://localhost:4321` |
| `npm run build`   | Production build to `./dist/`               |
| `npm run preview` | Build and preview with Wrangler locally     |
| `npm run deploy`  | Deploy with Webflow Cloud CLI               |

## Learn more

- [Astro documentation](https://docs.astro.build)
- [Webflow Cloud](https://webflow.com/feature/cloud)

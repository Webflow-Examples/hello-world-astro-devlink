# Astro + Webflow Cloud

Example Astro app configured for [Webflow Cloud](https://webflow.com/cloud).

[![Deploy to Webflow](https://webflow.com/img/deploy-dark.svg)](https://webflow.com/dashboard/cloud/deploy?repo=https://github.com/Webflow-Examples/hello-world-astro-devlink)

## Project structure

```text
/
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

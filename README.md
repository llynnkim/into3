# into3.studio — redesign concept

A student redesign concept for [into3.studio](https://into3.studio/) by Lynn Kim.
Not affiliated with into3.studio or Polygom Inc.

Plain static site: no build step, no dependencies.

```
index.html      The whole site: one page, no images, no dependencies
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy

1. Push this folder to a GitHub repository.
2. In Vercel: **Add New → Project → Import** the repository.
3. Framework preset: **Other**. Leave the build command and output directory empty.
4. Deploy. Every later push to `main` redeploys automatically.

The pages carry `<meta name="robots" content="noindex">` so the concept stays out of search results.

# Estra
> An operating system in your browser.

Welcome to Estra! Estra is a new project that started recently due to [the ArcOS shutdown](./public/arcos-shutdown.png). Estra is written using Svelte & Typescript, making it efficient and performant.

## Getting Started

As of writing this, there is no pre-compiled build for Estra, so you have to follow the usual vite app build/setup:

1. Install dependencies
```bash
yarn
```

2. Build or Run
```bash
yarn build
#or
yarn dev
```

3. (if built) Host built version

You can use any good old http file server, such as the builtin python one:
```bash
cd dist
python3 -m http.server
```
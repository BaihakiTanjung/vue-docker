# vue-docker

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```


## Docker Command

### Dev
```sh
docker build -t dev-vue-docker .
```

## Create and Run Container
```sh
docker run -it -p 8080:8080 --rm --name dev-vue-docker dev-vue-docker
```

## Prod
```sh
docker build -t prod-vue-docker -f Dockerfile.prod .
```

## Create and Run Container
```sh
docker run -it -p 8080:8080 --rm --name prod-vue-docker prod-vue-docker
```

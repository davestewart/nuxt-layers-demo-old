# Nuxt Layers Demo

> Demo repo for Nuxt Layers article

## Intro

This repo accompanies my article on using Nuxt Layers to modularise sites by domain:

- [Modular site architecture with Nuxt layers](https://davestewart.co.uk/blog/nuxt-layers/)

The repo is built off the Nuxt [Alpine Theme](https://github.com/nuxt-themes/alpine), as:

1. it's a good all-round, production-ready repo
2. it has enough sections that could be migrated to layers 
3. it demonstrates good before and after cases

It's designed to show how an existing site can be fairly easily refactored to Nuxt layers, gaining the benefits of a site architected by domain, rather than concern.

The article introduces the reader to layers and covers various techniques to build and get the most out of a layered site. All the techniques discussed there are employed in this demo. 

## Instructions

The repo has two branches:

1. [main](https://github.com/davestewart/nuxt-layers-demo)<br>
  Alpine blog, but with the theme dependency factored-out as top-level folders
2. [layers](https://github.com/davestewart/nuxt-layers-demo/tree/layers)<br>
  The top-level folders refactored as Nuxt Layers 

Check out the repo, install and run the dev build: 

```bash
git clone https://github.com/davestewart/nuxt-layers-demo.git
cd nuxt-layers-demo
npm install
npm run dev
```

To compare to layers, halt the terminal, switch branches then re-run the fun:

```
git checkout layers
npm run dev
```

You shouldn't see any difference between the sites, but the folder structure is refactored around domains.

## Feedback

If you have any comments or questions, feel free to create an issue, or drop a [comment](http://davestwart.co.uk/blog/nuxt-layers/#hyvor-talk-view) on the original article.

Cheers,<br>
Dave

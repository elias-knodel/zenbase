Features:

- ✅ Minimal styling (make it your own!)
- ✅ 100/100 Lighthouse performance
- ✅ SEO-friendly with canonical URLs and OpenGraph data
- ✅ Sitemap support
- ✅ RSS Feed support
- ✅ Markdown & MDX support

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
├── public/
├── src/
│   ├── components/
│   ├── content/
│   ├── layouts/
│   └── pages/
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

The `src/content/` directory contains "collections" of related Markdown and MDX documents. Use `getCollection()` to retrieve posts from `src/content/blog/`, and type-check your frontmatter using an optional schema. See [Astro's Content Collections docs](https://docs.astro.build/en/guides/content-collections/) to learn more.

Any static assets, like images, can be placed in the `public/` directory.

## 👀 Want to learn more?

Check out [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

# AAAAAAAAAAAAAAA

# The ZenJS Framework

[![gh-commit-badge][gh-commit-badge]][gh-commit]
[![gh-contributors-badge][gh-contributors-badge]][gh-contributors]
[![gh-stars-badge][gh-stars-badge]][gh-stars]

## Roadmap / Core features

* [x] Astro 
* [ ] Svelte
* [x] Tailwind 
* [x] Less 
* [ ] Storybook (if it works with astro) 
* [ ] Apitable 
* [ ] Weblate

With focus on:
* [ ] SEO
* [ ] (DSGVO) Privacy
* [ ] Analytics
* [ ] Multiple Storefronts

Optional:  
* [x] tailwind-config-viewer

## Description

This "Framework" is in reality just a collection of the best tools and tech i found over the years.  
However, everything has been carefully selected so that in the end you can "easily" create a medium to large website.

## Getting started

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `yarn`                 | Installs dependencies                            |
| `yarn dev`             | Starts local dev server at `localhost:3000`      |
| `yarn build`           | Build your production site to `./dist/`          |
| `yarn preview`         | Preview your build locally, before deploying     |
| `yarn astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `yarn astro --help`    | Get help using the Astro CLI                     |

## Contributing Guidelines

### Commit messages

Construct of a commit message:

```bash
prefix(scope): commit subject with max 50 chars
```

Example commit message:

```bash
feat(comp): add ping slash command
```

#### Scopes

Project specific scopes and what to use them for.

```bash
'deps', // Changes done on anything dependency related
'devops', // Changes done on technical processes
```

#### Prefixes:

```bash
'feat', // Some new feature that has been added
'fix', // Some fixes to an existing feature
'build', // Some change on how the project is built
'chore', // Some change that just has to be done (like updating dependencies)
'ci', // Some changes to the continues integration workflows
'docs', // Some changes to documentation located in the repo (either markdown files or code DocBlocks)
'perf', // Some performance improvements
'refactor', // Some code changes, that neither adds functionality or fixes a bug
'revert', // Some changes that revert already done changes
'style', // Some fixes regarding code style
'test', // Some automated tests that have been added
```

#### Branches:

| Branch     | Usage                                  |
|------------|----------------------------------------|
| main       | The default branch                     |
| feature/*  | For developing features                |
| fix/*      | For fixing bugs                        |

## Useful links

[License][gh-license] -
[Contributing][gh-contribute] -
[Code of conduct][gh-codeofconduct] -
[Issues][gh-issues] -
[Pull requests][gh-pulls]

<hr>  

###### Copyright (c) [elias-knodel][gh-team]. All rights reserved | Licensed under the MIT license.

<!-- Variables -->

[gh-commit-badge]: https://img.shields.io/github/last-commit/elias-knodel/the-zenjs-framework?style=for-the-badge&colorA=302D41&colorB=cba6f7

[gh-commit]: https://github.com/elias-knodel/the-zenjs-framework/commits/main

[gh-contributors-badge]: https://img.shields.io/github/contributors/elias-knodel/the-zenjs-framework?style=for-the-badge&colorA=302D41&colorB=89dceb

[gh-contributors]: https://github.com/elias-knodel/the-zenjs-framework/graphs/contributors

[gh-stars-badge]: https://img.shields.io/github/stars/elias-knodel/the-zenjs-framework?style=for-the-badge&colorA=302D41&colorB=f9e2af

[gh-stars]: https://github.com/elias-knodel/the-zenjs-framework/stargazers

[gh-contribute]: https://github.com/elias-knodel/.github/blob/main/docs/CONTRIBUTING.md

[gh-license]: https://github.com/elias-knodel/the-zenjs-framework/blob/main/LICENSE

[gh-codeofconduct]: https://github.com/elias-knodel/.github/blob/main/docs/CODE_OF_CONDUCT.md

[gh-issues]: https://github.com/elias-knodel/the-zenjs-framework/issues

[gh-pulls]: https://github.com/elias-knodel/the-zenjs-framework/pulls

[gh-team]: https://github.com/elias-knodel

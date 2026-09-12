---
title: 'Getting Started'
description: 'Install Atlas and publish your first page.'
---
## Installation

Pull the package in with Composer:

```shell
composer require atlas/atlas
```

## Your first page

Create a markdown file in your docs directory and Atlas will pick it up on
the next sync. Front matter is optional — a file with nothing but a body
still gets a title derived from its filename. Cool 

```markdown
---
title: Hello World
---

Everything below the front matter is the page body.
```
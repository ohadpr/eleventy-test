# Eleventy Stackbit Boilerplate

## What is it?

A simple template for building a fast, static website using the [Eleventy](https://www.11ty.io/) static site generator, with your headless CMS of choice, on [Stackbit](https://www.stackbit.com) in a couple of clicks.

Use it as a starter for your own projects or as an easy way to get started building websites with Eleventy.

Based on the [Eleventy Netlify Boilerplate](https://github.com/danurbanowicz/eleventy-netlify-boilerplate) by [Dan Urbanowicz](https://www.danurbanowicz.com/).

## Features

* Sample pages and blog with tag support
* CSS 2kb minified, inlined for fastest page render
* Pre-builds and minifies your HTML
* Responsive CSS Grid layout, with fallbacks (see [Browser Support](#browser-support))
* Uses Markdown files for content
* Uses Liquid and/or Nunjucks templates for layout
* 100% Javascript framework free
* Optional pipeline for minified inline JS

## Want to try it out now?

[![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/stackbithq/eleventy-stackbit-boilerplate)

Clicking the button above will start the Stackbit project creation wizard with this theme and Eleventy pre-selected as your chosen site generator. Simple pick your preferred CMS. This is powered by a single config file, [stackbit.yaml](https://docs.stackbit.com/uniform/stackbit-yaml/), which defines a [Uniform theme model](https://docs.stackbit.com/uniform/) and enables integration with CMS like Contentful, DatoCMS, Forestry, NetlifyCMS, etc.

## Local development

### 1. Clone this repository:

```
git clone https://github.com/stackbithq/eleventy-stackbit-boilerplate.git my-blog-name
```

### 2. Navigate to the directory

```
cd my-blog-name
```

Specifically have a look at `.eleventy.js` to see if you want to configure any Eleventy options differently.

### 3. Install dependencies

```
npm install
```

### 4. Edit _data/metadata.json

This file contains your site title and author details.

### 5. Run Eleventy (builds the site)

```
npx eleventy
```

Or build automatically when a template changes:
```
npx eleventy --watch
```

Or in debug mode:
```
DEBUG=* npx eleventy
```

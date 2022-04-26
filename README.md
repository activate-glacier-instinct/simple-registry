# Simple Registry - Hashmask clone

## Intro 

Hashmask clone in order to fullfil the [brief](./docs/BRIEF.md).

## Designs 

Designs found [here](./docs/DESIGNS.md)

## User stories

Full list of user stories found [here](./docs/STORIES.md)

## Tech stack

* Next.js
* Typescript
* fuze.js
* Chakra
* ethers.js


## Problems 

1. Performance

Clearly the existing Hashmask site has a data problem. 

We see a loader before we open the `/names` page. 

My proposal here is to use a virtualised (and memoized) list in order to render quicker and bypass the need for that loader.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

## Authors

* activate-glacier-instinct

## Credits
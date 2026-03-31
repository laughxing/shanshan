# GitHub Pages Export

This directory is ready to be pushed to a dedicated GitHub repository for static hosting.

## Story

- story id: `小马宝莉友谊生日派对-今天是珊珊的生日-紫悦-碧琪-苹果嘉儿-云宝黛西-珍奇和柔柔想悄悄给她准备-20260329-151129`
- image format: `webp`
- width: `1600px`
- quality: `82`

## Publish Steps

1. Create a new GitHub repository, for example `storybook-pages`.
2. Copy the contents of this directory into that repository root, keeping the `docs/` folder intact.
3. Push to the `main` branch.
4. In GitHub, open `Settings -> Pages`.
5. Set Source to `Deploy from a branch`.
6. Select branch `main` and folder `/docs`.
7. Wait for deployment, then open the generated `github.io` URL.

## Local Source

- generated from: `G:/projects/story_book/mvp/github-pages/小马宝莉友谊生日派对-今天是珊珊的生日-紫悦-碧琪-苹果嘉儿-云宝黛西-珍奇和柔柔想悄悄给她准备-20260329-151129`

## Regenerate

```bash
cd mvp
npx tsx scripts/export-story-github-pages.ts "story-jobs/小马宝莉友谊生日派对-今天是珊珊的生日-紫悦-碧琪-苹果嘉儿-云宝黛西-珍奇和柔柔想悄悄给她准备-20260329-151129" --clean
```

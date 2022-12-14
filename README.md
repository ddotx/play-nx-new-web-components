# NX Web Component Application

[@nrwl/web](https://nx.dev/packages/web#nrwlweb)

### Create a new workspace
```
npx create-nx-workspace@latest --preset=web-components
```

### Storybook
Add
```
yarn add --dev @nrwl/storybook

nx g @nrwl/storybook:configuration nnwc --tsConfiguration=true
```
Run
```
nx storybook
```

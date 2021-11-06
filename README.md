# RugZombie Toolkit

This repository is a monorepo manage with [yarn workspaces](https://classic.yarnpkg.com/en/docs/workspaces/) and [Lerna](https://lerna.js.org/). 

## Packages

- [rug-zombie-uikit](https://github.com/Rug-Zombie/rug-zombie-uikit/tree/master) : React components used to build the RugZombie UI
- [catacombs-uikit](https://github.com/Rug-Zombie/catacombs-uikit/tree/master) : React components used to build the Catacombs UI

## Making Changes

- Clone the repository 
- Make change to component in [packages/rug-zombie-uikit](https://github.com/Rug-Zombie/rug-zombie-uikit/tree/master) or [packages/catacombs-uikit](https://github.com/Rug-Zombie/catacombs-uikit/tree/master) repo.
- Run `yarn build`
- Commit and push changes
- Update dependencies in `rug-zombie-frontend` for changes to take effect.
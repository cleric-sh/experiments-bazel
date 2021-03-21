# State of Bazel and frontend

This is a workbench for a bazel-driven monorepo, trying to find the correct way to build and run common front-end frameworks, tools and patterns.

The repository focuses on DX. Goals that all implementations should achieve include:

 - typescript support
 - shared typescript libraries
 - shared component libraries
 - fast incremental rebuilds and HMR (incl. stateful HMR like react's fast refresh)
 - fast incremental test execution
 - plays nice with wallaby
 - plays nice with eslint, prettier, sortier
 - storybook support for component libraries
 - cypress support for e2e tests of front-end apps (incl. HMR and re-running cypress on changes)

## webpack // create-react-app

Builds: yes
Typescript Support: yes
Incremental Rebuild: No
Live Reloads: No
HMR: No
Stateful HMR: No

Notes:
HMR problems with bazel's `create-react-app` example are tracked here:
https://github.com/bazelbuild/rules_nodejs/issues/2521


## vite // create-react-app

Builds: No
Typescript Support: yes
Incremental Rebuild: No
Live Reloads: No
HMR: No
Stateful HMR: No

Notes:
HMR problems with bazel's `create-react-app` example are tracked here:
https://github.com/bazelbuild/rules_nodejs/issues/2521
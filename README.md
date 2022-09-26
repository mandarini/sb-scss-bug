# React + Storybook + SCSS issue

1. `yarn` to install dependencies
2. `npm run storybook` to run Storybook
3. Observe error:

```
ModuleBuildError: Module build failed (from ./node_modules/react-scripts/node_modules/sass-loader/dist/cjs.js):
SassError: expected "{".
  ╷
2 │       import API from "!../../node_modules/style-loader/dist/runtime/injectStylesIntoStyleTag.js";
  │                                                                                                  ^
  ╵
  src/stories/button.module.scss 2:98  root stylesheet
    at processResult (/Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/webpack/lib/NormalModule.js:758:19)
    at /Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/webpack/lib/NormalModule.js:860:5
    at /Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/loader-runner/lib/LoaderRunner.js:400:11
    at /Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/loader-runner/lib/LoaderRunner.js:252:18
    at context.callback (/Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/loader-runner/lib/LoaderRunner.js:124:13)
    at Object.loader (/Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/react-scripts/node_modules/sass-loader/dist/index.js:69:5)
    at runNextTicks (node:internal/process/task_queues:61:5)
    at processImmediate (node:internal/timers:437:9)
SassError: SassError: expected "{".
  ╷
2 │       import API from "!../../node_modules/style-loader/dist/runtime/injectStylesIntoStyleTag.js";
  │                                                                                                  ^
  ╵
  src/stories/button.module.scss 2:98  root stylesheet
    at Object.loader (/Users/katerina/Projects/nrwl/test_nx_workspaces/vanileact/node_modules/react-scripts/node_modules/sass-loader/dist/index.js:69:14)
    at runNextTicks (node:internal/process/task_queues:61:5)
    at processImmediate (node:internal/timers:437:9)

WARN Broken build, fix the error above.
WARN You may need to refresh the browser.
```

[full log here](https://app.warp.dev/block/gRVukUXfut0MyLzaTCbFVK)
<p align="center">
    <img src="https://user-images.githubusercontent.com/6702424/80216211-00ef5280-863e-11ea-81de-59f3a3d4b8e4.png">  
</p>
<p align="center">
    <i></i>
    <br>
    <br>
    <img src="https://github.com/garronej/powerhooks/workflows/ci/badge.svg?branch=master">
    <img src="https://img.shields.io/bundlephobia/minzip/powerhooks">
    <img src="https://img.shields.io/npm/dw/powerhooks">
    <img src="https://img.shields.io/npm/l/powerhooks">
</p>
<p align="center">
  <a href="https://www.powerhooks.dev">Home</a>
  -
  <a href="https://docs.powerhooks.dev">Documentation</a>
</p>

# Install / Import

https://github.com/testing-library/react-hooks-testing-library

https://github.com/InseeFrLab/onyxia-ui/tree/structure_rework/src/app/tools/hooks

https://github.com/facebook/react/blob/9198a5cec0936a21a5ba194a22fcbac03eba5d1d/packages/eslint-plugin-react-hooks/src/ExhaustiveDeps.js



```typescript
import { createUseGlobalState } from "powerhooks/useGlobalState";

export const { useIsDarkModeEnabled } = createUseGlobalState(
    "isDarkModeEnabled",
    () => (
        window.matchMedia &&
        window.matchMedia("(prefers-color-scheme: dark)").matches
    )
);
```

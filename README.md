# vscode ornikar extension

## Installation

1.  Open the extensions sidebar on Visual Studio Code
2.  Search for **Ornikar**
3.  Click **Install** to install it.
4.  Click **Reload** to reload the your editor
5.  Enjoy

## Snippets

### Generic

| prefix | snippet                         |
| ------ | ------------------------------- |
| imt    | `import $2 from '$1';`          |
| imtn   | `import { $2 } from '$1';`      |
| imtt   | `import type { $2 } from '$1';` |
| exp    | `export { $1 };`                |
| expf   | `export $2 from '$1';`          |
| expft  | `export type { $2 } from '$1';` |

### React

| prefix | snippet                               |
| ------ | ------------------------------------- |
| rimt   | `import React from 'react';`          |
| rimtt  | `import type { $1 } from 'react';`    |
| rfc    | React Function Component              |
| rfcs   | React Function Component, with styles |

### Kitt

| prefix | snippet |
| ------ | ------- |

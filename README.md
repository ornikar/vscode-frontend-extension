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

| prefix | snippet                            |
| ------ | ---------------------------------- |
| rimt   | `import { $1 } from 'react';`      |
| rimtt  | `import type { $1 } from 'react';` |
| rfc    | React Function Component           |

### Kitt

| prefix   | snippet                                                            |
| -------- | ------------------------------------------------------------------ |
| kimt     | Imports Kitt npm package                                           |
| kuimt    | Imports Kitt universal npm package                                 |
| kbutton  | Creates a kitt `<Button />` component                              |
| kicon    | Creates a kitt `<Icon />` component                                |
| kmodal   | Creates a kitt `<Modal />` component, with a header, body & footer |
| kmessage | Creates a kitt `<Message />` component                             |

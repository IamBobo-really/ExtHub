# Adding Your Extension to This Custom Gallery
---

## Step 1: Extension Format

### Requirements
- Extensions must use the traditional PenguinMod extension format (no Turbobuilder or auto‑generated formats).
- Use clean, readable code and cast inputs with `Scratch.Cast` where appropriate.
- Your extension ID should include your username.
- Include a commented header at the top of your file with:
  - Name
  - ID
  - Author
  - Description
  - License
  - Version

### Example Structure
```js
// header metadata

(function (Scratch) {
  "use strict";

  class Extension {
    // ...
  }

  Scratch.extensions.register(Extension);
})(Scratch);

# polymer-primer
Polymer primer, notes, and hints

## Existing Components

TODO: flesh this out

- Polymer elements
- webcomponents.io

## Custom Components

### Boilerplates and scaffolding

- [Polymer Boilerplace](https://github.com/webcomponents/polymer-boilerplate) - __Easy__ - "A bare minimum custom element starter-kit using Polymer."
- ~~[Yeoman Generator](https://github.com/webcomponents/generator-element)~~ - Deprecated in favor of Polymer CLI (below)?
- [Polymer CLI](https://github.com/Polymer/polymer-cli) - __Best__ - CLI Toolbelt for all things Polymer


### Naming

> The custom elements specification requires the element name to contain a dash.

The first part should be a namespace designator. Polymer uses "iron", "paper", "platinum", etc. (avoid these).

- __Easy__ - Use company name or abbreviation. Eg. CuseDigital = "cd", so I may have `cd-card`
- __Best__ - If you plan on using a lot, further break them down into general categories.

### Creating your own component

https://www.polymer-project.org/1.0/docs/tools/polymer-cli#element

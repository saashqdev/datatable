# Saashq Datatable

## Introduction

Saashq DataTable is a simple, modern and interactive datatable library for displaying tabular data. It can be used to render large amounts of rows without sacrificing performance and has the basic data grid features like inline editing and keyboard navigation. It does not require jQuery, unlike most data grids out there.

## Features

### Cell Features

* Custom Formatters
* Inline Editing
* Mouse Selection
* Copy Cells
* Keyboard Navigation
* Custom Cell Editor

### Column Features

* Reorder Columns
* Sort by Column
* Remove / Hide Column
* Custom Actions
* Resize Column
* Flexible Layout

### Row Features

* Row Selection
* Tree Structured Rows
* Inline Filters
* Large Number of Rows
* Dynamic Row Height

## Install

```bash
yarn add @saashq/datatable
# or
npm install @saashq/datatable
```

> Note: [`sortablejs`](https://github.com/RubaXa/Sortable) is required to be installed as well.

## Usage

```js
const datatable = new DataTable('#datatable', {
  columns: [ 'First Name', 'Last Name', 'Position' ],
  data: [
    [ 'Don', 'Joe', 'Designer' ],
    [ 'Mary', 'Jane', 'Software Developer' ]
  ]
});
```

## Contribution

* `yarn start` - Start dev server
* Open `index.html` located in the root folder, and start development.
* Run `yarn lint` before committing changes
* This project uses [commitizen](https://github.com/commitizen/cz-cli) for conventional commit messages, use `yarn commit` command instead of `git commit`

## License

[MIT](http://opensource.org/licenses/MIT)

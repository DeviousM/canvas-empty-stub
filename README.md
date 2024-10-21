# canvas-empty-stub

A lightweight, empty stub package designed to replace the `canvas` dependency when it's not needed in your project.

## Purpose

The `canvas-empty-stub` package serves as a drop-in replacement for the `canvas` library in environments where canvas functionality is not used, but it 's required as a peer dependency.

By using this stub, you can avoid problems with building the `canvas` package and also issues with canvas being required as a peer dependency.

## Installation

You can install `canvas-empty-stub` using npm:
```bash
npm install canvas@npm:canvas-empty-stub@^1.0.0
```
or yarn
```bash
yarn add canvas@npm:canvas-empty-stub@^1.0.0
```

## Usage

You can replace the usage in the package.json with the following manually:

```json
"dependencies": {
  "canvas": "npm:canvas-empty-stub@^1.0.0"
}
```

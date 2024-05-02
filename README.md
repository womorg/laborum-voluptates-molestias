# @womorg/laborum-voluptates-molestias

[![build status](https://img.shields.io/github/actions/workflow/status/rdf-ext/@womorg/laborum-voluptates-molestias/test.yaml?branch=master)](https://github.com/womorg/laborum-voluptates-molestias/actions/workflows/test.yaml)
[![npm version](https://img.shields.io/npm/v/@womorg/laborum-voluptates-molestias.svg)](https://www.npmjs.com/package/@womorg/laborum-voluptates-molestias)

File system utils for RDF/JS.

## Usage

Each util function can be loaded as property from the main module or by loading only the file with the same name.

### Example

Loading the function from the main module:

```javascript
import { fromFile } from '@womorg/laborum-voluptates-molestias'
import { toFile } from '@womorg/laborum-voluptates-molestias'
```
 
Loading the function from the file with the function name:

```javascript
import fromFile from '@womorg/laborum-voluptates-molestias/fromFile.js'
import toFile from '@womorg/laborum-voluptates-molestias/toFile.js'
```
 
## Functions

### fromFile(filename, options)

Returns a quad stream for the given `filename`.

### async toFile(stream, filename, options)

Writes the given quad stream to `filename`. 

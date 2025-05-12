> [!WARNING]  
> I no longer use or maintain this library. I don't really code in JavaScript anymore (I switched to Rust). If you want to maintain or fork it let me know and I can put the link here.

# release-preview
Get PR tags based on the type of release a mono repo PR will trigger

![Created with ](https://img.shields.io/badge/Created%20with-@programmerraj/create-3cb371?style=flat)
[![TS-Standard - Typescript Standard Style Guide](https://badgen.net/badge/code%20style/ts-standard/blue?icon=typescript)](https://github.com/standard/ts-standard)
      

## Inputs

### `packages`
List of all packages in the mono repo

### `increments`
Increments gotten from [detect-increment](https://github.com/ChocolateLoverRaj/detect-increment)

### `new_packages`
Packages which need to be published without a version bump

## Outputs

### `manage`
JSON array of labels to be managed

### `set`
JSON array of labels to be set

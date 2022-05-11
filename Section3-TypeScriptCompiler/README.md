# Section 3

## Compiling the entire project / multiple files

Allows you to watch all ts files in folder. Creates tsconfig.json, watches all files and subfolders.

```bash
tsc --init
```

Compiles ts to js files

```bash
tsc
```

Watches the files for changes

```bash
tsc -w
```

## Including and excluding files

Inside `tsconfig.json` you can exclude files by adding the "exclude" prop.

```js
{ ... },
"exclude": [
    "node_modules"
]

```

Inside `tsconfig.json` you can include files by adding the "include" prop. Means you have to manually add all things you want.

```js
{ ... },
"include": [
    "node_modules"
]

```

It compiles include then excludes after.

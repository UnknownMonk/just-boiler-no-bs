# just-boiler-no-bs

`just-boiler-no-bs` is an npm package that allows you to quickly create an Express.js API with TypeScript or a boilerplate set up for tailwind and Next.js with TypeScript. This package uses the `args`, `degit`, and `chalk` npm packages to create the API.

## Installation

To use `just-boiler-no-bs`, you must have Node.js and npm installed on your system. To install `just-boiler-no-bs`, run the following command in your terminal:

```bash
npm install -g just-boiler-no-bs
```

## Usage

To use `express-api-starter`, run the following command in your terminal:

```bash
create-express-api -t -d my-api
```

This will create an Express.js API with TypeScript in a directory called `my-api`. Alternatively, you can use the following command to create a boilerplate set up for tailwind and Next.js with TypeScript in a directory called `my-api`:

```bash
create-next-typeScript-tailwind-boiler -d my-api
```

## Options

`express-api-starter` supports the following options:

- `-t, --typescript`: Use the TypeScript template.
- `-d, --directory`: The name of the directory to create.

## Examples

`express-api-starter` supports the following examples:

```bash
create-express-api -t -d my-api
```

This will create an Express.js API with TypeScript in a directory called `my-api`.

```bash
create-next-typeScript-tailwind-boiler -d my-api
```

This will create a boilerplate set up for tailwind and Next.js with TypeScript in a directory called `my-api`.

## License

This package is licensed under the MIT License.

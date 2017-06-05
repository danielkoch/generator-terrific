# Terrific hybris Module Generator

Generates all the files necessary for a new terrificJS component in hybris. Also includes generators for Skins, Decorators and Preview Pages.

## Usage

Install the latest [nodejs](http://nodejs.org) and go to the location of your hybris project's Frontend

```
npm install generator-terrific
```

After installing the package you can generate new modules with

```
./node_modules/yo/lib/cli.js ./node_modules/generator-terrific
```

It's advised to create a shortcut in your `package.json`

```
{
    "scripts": {
        "add": "./node_modules/yo/lib/cli.js ./node_modules/generator-terrific"
    }
}
```

and then running `npm run add` will suffice.
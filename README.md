
<p align="center">
  <a href="http://www.exictos.com/">
    <img src="/uploads/dbedbb2131dc8eb09b2a5bf6027e0ae9/symbol-exictos.png" width="100" alt="Exictos"/>
  </a>
</p>
<h1 align="center">
  Exictos - Distribution Channel Solutions
</h1>
## Synopsis

**dcs-incon-font**
Is a font generator that enables you to generate fonts for SVG icons.

So you be able to use vectorial icons as a text font and manipulate them very easily.

It aims to make all the icons management easier and provide all the SVG features in a really flexible way.
So you can write nice and clean CSS and HTML without polluting your code with SVG codes or *src* paths.

## Installation

You can install it through NPM, simply run:

```
npm install dcs-icon-font -g
```

Or you can clone it and install all its dependencies:
```
git clone git@172.25.1.187:canais-n-presenciais/dcs-icon-font.git
npm install -g
```

## Usage

When installing from NPM globally, you can simply run:

```
dcs-icon-font --icons './my-svg-icons'
```

(see the "src/config/wf-config.js") for more customization

## Code Example

```
<i class="dcs-icon dcs-icon-aeroplane4" style="color: #B33B3B; background-color: #F7FFE5; font-size: 30px;"/>
```
Will produce the following in your web browser:

![dcs-icon-aeroplane4](/uploads/ff4a74f99614bdbc7042a52df25315eb/dcs-icon-aeroplane4.PNG)

## API Reference

These are all the flags that you can use with the *dcs-icon-font* generator:

| Flag                    | Description
| ----------------------- |:-------------
| --help                  | Presents all the available arguments that the dcs-icon-font cli is ready to handle
| --out [path]            | specifies where the generated code is stored into. Default will be the *"build"* directory
| --icons [path]          | specifies the directory that contains the SVG icons for which you want to generate the font
| --baseclass [string]    | specifies the base css class name (ex. *dcs-icon*)
| --classprefix [string]  | specifies the css class prefix for all your icons (ex. *dcs-icon-circle*)
| --fontname [string]     | the name for your brand new font
| --html                  | Because it would be nice to have a preview of all the fonts and CSS generated, you can pass this flag and have a html file with a html preview


## Tests

Describe and show how to run the tests with code examples.

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
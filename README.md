[![Install directly with Stylus](https://img.shields.io/badge/Install%20directly%20with-Stylus-00adad.svg)](https://raw.githubusercontent.com/CharlieEtienne/material-github/master/material-github.user.css)

# Material Theme for GitHub
A Material Dark Theme for GitHub

3 themes available : Oceanic, Darker, Palenight

Based on awesome **[VSCode Material Theme](https://github.com/equinusocio/vsc-material-theme)** by **Mattia Astorino**

![Material Theme GitHub](https://github.com/CharlieEtienne/github-material/blob/master/screenshot.png)

## How to use it

1. Install **Stylus Extension** [for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [for Firefox](https://addons.mozilla.org/fr/firefox/addon/styl-us/) or [for Opera](https://addons.opera.com/en-gb/extensions/details/stylus/)

2. Install [https://userstyles.org/styles/174317/material-dark-github](https://userstyles.org/styles/174317/material-dark-github) 

## Using the theme without userstyles.org

This theme is dynamic. It means you can choose between three different variations when you install it from userstyles.org.

In order to make the theme work in standalone, you will need to replace the following string `/*[[theme]]*/` located on the top of `style.css` file with one of these theme variations. Each one contains 6 different colors.

### Oceanic theme

```css
--bg1: hsl(200, 19%, 13%);
--bg2: hsl(200, 19%, 15%);
--bg3: hsl(200, 19%, 18%);
--bg4: hsl(200, 19%, 20%);
--bg5: hsl(200, 19%, 24%);
--bg6: hsl(200, 19%, 27%);
```

### Darker theme

```css
--bg1: hsl(0, 0%, 13%);
--bg2: hsl(0, 0%, 15%);
--bg3: hsl(0, 0%, 18%);
--bg4: hsl(0, 0%, 20%);
--bg5: hsl(0, 0%, 24%);
--bg6: hsl(0, 0%, 27%);
```

### Palenight theme

```css
--bg1: hsl(229, 20%, 13%);
--bg2: hsl(229, 20%, 15%);
--bg3: hsl(229, 20%, 18%);
--bg4: hsl(229, 20%, 20%);
--bg5: hsl(229, 20%, 24%);
--bg6: hsl(229, 20%, 27%);
```

As you can see all colors are based on hue, saturation, and luminosity variations.
It means that you can replace it with your own colors very easily. Just play with the two first values (hue and saturation) and you might obtain something cool.

For example, for a "aubergine" theme:

```css
--bg1: hsl(300, 20%, 13%);
--bg2: hsl(300, 20%, 15%);
--bg3: hsl(300, 20%, 18%);
--bg4: hsl(300, 20%, 20%);
--bg5: hsl(300, 20%, 24%);
--bg6: hsl(300, 20%, 27%);
```

## Disclaimer

Keeping the theme up to date is very difficult because of changes github could bring to css at any moment. 
If the theme is broken, don't hesitate to fill an issue here.

## Contributions

Contributions are very welcome! Feel free to suggest changes in a new issue or make a PR.

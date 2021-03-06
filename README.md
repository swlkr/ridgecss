# ridge.css

> The clearest way into the Universe is through a forest wilderness. - John Muir

ridge.css is a set of classless css themes, layout helpers via [pylon.css](https://github.com/almonk/pylon) and optional [alpine.js](https://github.com/alpinejs/alpine) code to help you write _fast web apps fast_

## Usage
Try before you buy! Here's how your html could look after applying ridge.css (with the default dark theme)

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>ridge.css</title>
    <link rel="stylesheet" href="ridge-dark.css" />
    <link rel="stylesheet" href="ridge.css" />
  </head>
  <body>
    <vstack spacing="xl">
      <hstack>
        <a href="/">Cool logo</a>
        <spacer></spacer>
        <hstack spacing=s>
          <a href="/pricing">Pricing</a>
          <a href="/join">
            <button>Sign up</button>
          </a>
        </hstack>
      </hstack>

      <vstack align-x="center">
        <h1>Welcome to ridge.css!</h1>
      </vstack>
    </vstack>
  </body>
</html>
```

Here's a screenshot of how that looks:

![screenshot of default dark theme](demo.png)

## Install

Download a theme, and add it to your html:

```html
<head>
  <link rel="stylesheet" media="(prefers-color-scheme: light), (prefers-color-scheme: none)" href="ridge-light.css" />
  <link rel="stylesheet" media="(prefers-color-scheme: dark)" href="ridge-dark.css" />
  <link rel="stylesheet" href="ridge.css" />
</head>
```

The example above adds both light and dark default themes and switches depending on the OS's dark mode setting.

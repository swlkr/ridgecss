# ridge.css

> The clearest way into the Universe is through a forest wilderness. - John Muir

ridge.css is a set of classless css themes, layout helpers via [pylon.css](https://github.com/almonk/pylon) and optional [alpine.js](https://github.com/alpinejs/alpine) code to help you write _fast web apps fast_

## Usage
Try before you buy! Here's how your html will look after applying ridge.css (with the default [water.css](https://kognise.github.io/water.css) theme)

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>ridge.css</title>
    <link rel="stylesheet" href="/ridge.css" />
  </head>
  <body>
    <vstack spacing="xl">
      <hstack>
        <a href="/">Cool logo</a>
        <spacer></spacer>
        <hstack>
          <a href="/pricing">Pricing</a>
          <spacer></spacer>
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

![]()

## Install

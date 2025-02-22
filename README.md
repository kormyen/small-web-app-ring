<a href="https://ring.0data.app"><img alt="Project logo" src="https://rosano.s3.amazonaws.com/public/swar/identity.svg" width="64" /></a>

# Small Web App Ring

_A webring for web apps_

This <a href="https://ring.0data.app">appring</a> is to support independent developers by sharing traffic between personal projects. It is not necessary for the app to be [0data](https://0data.app) or a [Progressive web app](https://en.wikipedia.org/wiki/Progressive_web_application), but these would be ideal. The app must be functional without signing into an account.

Inspired by [XXIIVV/webring](https://github.com/XXIIVV/webring) and [indiewebring](https://indieweb.org/indiewebring).

## Join the ring

1. Link to the appring from your app homepage or inside the app itself (see below for example code that you can copy and modify).
2. Add your project URL to [index.html](https://github.com/0dataapp/lap/edit/master/index.html)
3. Submit a Pull Request with the location of the appring link in your project.

### Link via text

```html
<a href="https://ring.0data.app/#random" target="_blank">Part of the Appring</a>
```

### Link via image

```html
<a href="https://ring.0data.app/#random" target="_blank" title="Part of the Appring"><img src="https://ring.0data.app/identity.svg" width="24" /></a>
```

### Link via image and text

```html
<a href="https://ring.0data.app/#random" target="_blank"><img src="https://ring.0data.app/identity.svg" width="24" align="left" hspace="4" role="presentation" /> Part of the Appring</a>
```

## Questions

Feel free to reach out on [Mastodon](https://merveilles.town/@rosano) or [Twitter](https://twitter.com/rosano).

[release-badge]: https://img.shields.io/github/release-pre/ClearVision/v6.svg?style=flat-square
[release-link]: https://github.com/ClearVision/v6/releases
[license-badge]: https://img.shields.io/github/license/ClearVision/v6.svg?style=flat-square
[license-link]: https://github.com/ClearVision/v6/blob/master/LICENSE
[discord-badge]: https://img.shields.io/discord/212324635356692500.svg?style=flat-square
[discord-link]: https://clearvision.gitlab.io/join
[issues-badge]: https://img.shields.io/github/issues/ClearVision/v6.svg?style=flat-square
[issues-link]: https://github.com/ClearVision/v6/issues
[prs-badge]: https://img.shields.io/github/issues-pr/ClearVision/v6.svg?style=flat-square
[prs-link]: https://github.com/ClearVision/v6/pulls

<div align="center">

# ClearVision v6

[![Releases][release-badge]][release-link]
[![License][license-badge]][license-link]
[![Discord Server][discord-badge]][discord-link]
[![Issues][issues-badge]][issues-link]
[![Pull Requests][prs-badge]][prs-link]

![v6 Sapphire](https://github.com/ClearVision/ClearVision-v6/raw/master/screenshots/6-stable.4.7.9.png)

</div>

## Installing
Download the theme file and move it into your [BetterDiscord](https://betterdiscord.net) themes folder:

>[ClearVision_v6.theme.css](https://clearvision.gitlab.io/download/v6/latest)

## Building from source
In order build the theme from source you will need [Sass](https://sass-lang.com) & [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer).  
With [npm](https://npmjs.org/get-npm) installed you can simply run `npm install` to install all missing dependencies and compile the theme into the `/public` folder via `npm run build`.

**Dependencies:**
- [node-sass](https://github.com/sass/node-sass)
- [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer)
- [PostCSS CLI](https://github.com/postcss/postcss-cli)
- *[DiscordSelectors](https://github.com/zerthox/discordselectors) (included in the `/lib` folder)*
- *[rimraf](https://github.com/isaacs/rimraf) (for cleanup)*

## Contributing
In order to contribute you need to be able to compile [Sass](https://sass-lang.com).

If you use [Node Sass](https://github.com/sass/node-sass) via CLI, you can run:
```
node-sass main.scss public/main.css --watch
```

If you use [Dart Sass](https://github.com/sass/dart-sass) via CLI, you can run:
```
sass main.scss:public/main.css --watch
```

This will compile the theme into the `/public` folder and watch changes.

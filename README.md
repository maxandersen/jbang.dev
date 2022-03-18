## jbang.dev website
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-8-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Source code for https://jbang.dev

### Build and run with bundle

Install ruby with bundler and then do:

```
bundle install
bundle exec jekyll serve --livereload
```

### Build and run with docker

First choose your jekyll version tag from [Docker Hub](https://hub.docker.com/r/jekyll/jekyll/tags?page=1&ordering=last_updated).

Example, when building with Jekyll 4.2.0 -

```
docker run --rm -p 4000:4000 \
  --volume="$PWD:/srv/jekyll" \
  -it jekyll/jekyll:4.2.0 \
  jekyll serve --livereload
```
Navigate to http://localhost:4000 for local site.
## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/markolo25"><img src="https://avatars.githubusercontent.com/u/1953943?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mark Mendoza</b></sub></a><br /><a href="https://github.com/jbangdev/jbang.dev/commits?author=markolo25" title="Code">💻</a></td>
    <td align="center"><a href="https://xam.dk/"><img src="https://avatars.githubusercontent.com/u/54129?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Max Rydahl Andersen</b></sub></a><br /><a href="#content-maxandersen" title="Content">🖋</a></td>
    <td align="center"><a href="https://manik.magar.me/"><img src="https://avatars.githubusercontent.com/u/877286?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Manik Magar</b></sub></a><br /><a href="#content-manikmagar" title="Content">🖋</a></td>
    <td align="center"><a href="http://gastaldi.wordpress.com/"><img src="https://avatars.githubusercontent.com/u/54133?v=4?s=100" width="100px;" alt=""/><br /><sub><b>George Gastaldi</b></sub></a><br /><a href="#content-gastaldi" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/pxkbt"><img src="https://avatars.githubusercontent.com/u/89919408?v=4?s=100" width="100px;" alt=""/><br /><sub><b>pxkbt</b></sub></a><br /><a href="#content-pxkbt" title="Content">🖋</a></td>
    <td align="center"><a href="https://nipafx.dev/"><img src="https://avatars.githubusercontent.com/u/6537432?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nicolai Parlog</b></sub></a><br /><a href="#content-nipafx" title="Content">🖋</a></td>
    <td align="center"><a href="http://about.me/tadayosi"><img src="https://avatars.githubusercontent.com/u/156692?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Tadayoshi Sato</b></sub></a><br /><a href="#content-tadayosi" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="http://www.balachandran.org/"><img src="https://avatars.githubusercontent.com/u/600098?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Balachandran S</b></sub></a><br /><a href="#content-benignbala" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
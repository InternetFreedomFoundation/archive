# IFF Archive project

A static website built to serve as an Archive of `internetfreedom.in`

> Note: Changes on `internetfreedom.in` are not automatically mirrored to this website.

## Installation

Pre-requisites:

- Hugo
- go
- Export Ghost content (and settings) from the "Labs" section(JSON format)

## Usage/Examples

Convert ghost data to .md files which will be consumed by hugo:

```bash
  git clone https://github.com/anoop-b/ghostToHugo.git
  cd ghostToHugo
  go run main.go export.json
  cd newhugosite
```

### Feeding data to hugo

Transfer the contents of `newhugosite/content` and `newhugosite/layouts` to [content](https://github.com/InternetFreedomFoundation/archive/content) and [layouts](https://github.com/InternetFreedomFoundation/archive/layouts) folder respectively.

> Github workflow build and deploys automatically to github pages on push.
> To build manually run `hugo` from the root of the directory.

This generates the static website to the `public/` directory by default

## Roadmap

- [ ] create webhook from ghost posts
- [ ] consume webhook, build and deploy new posts using hugo

## License

Everything inside `content` directory is [CC-BY](https://choosealicense.com/licenses/cc-by-4.0/), everything else is [MIT](https://choosealicense.com/licenses/mit/).
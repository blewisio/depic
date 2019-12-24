# hqm

[Curated list](#directory) of **188** high-quality modules

## About

hqm is a hierarchical list of high-quality npm modules. Criteria for inclusion includes:
* does one thing well
* has great documentation and examples
* is well-tested
* follows semver
* has a short, descriptive name
* has as few dependencies as possible
* is based on modern code
* is cross-platform
* has type definitions

### How is this different than awesome-nodejs?

[awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) is great! However, hqm seeks to make improvements in several areas:
* **Less redundancy** - not all modules can be equally awesome, so any redundancy likely means there are inferior options on the list. This leads to analysis paralysis when choosing an npm package to fulfill a particular need.
* **More organization** - hqm is organized into a logical tree, which means finding a module for a certain purpose is easier (i.e. no Miscellaneous or "Mad Science" sections).
* **Custom descriptions** - instead of using each module's own description, I've distilled the descriptions down to the parts that matter - no marketing or fluff.
* **Greater breadth** - hqm is broken down into more sections than awesome-nodejs, covering more use cases *(coming soon)*

## Directory

View directory readmes to see the module full list, descriptions, and related modules.

* [algorithms](algorithms)
  * [caching](algorithms/caching)
    * [mem](https://github.com/sindresorhus/mem)
  * [cryptography](algorithms/cryptography)
    * [bcrypt](https://github.com/dcodeIO/bcrypt.js)
  * [linguistics](algorithms/linguistics)
    * [levenshtein-distance](https://github.com/hiddentao/fast-levenshtein)
  * [sorting](algorithms/sorting)
    * [alpha-sort](https://github.com/sindresorhus/alpha-sort)
* [data-structures](data-structures)
  * [bloomf](https://github.com/khalilw1/bloomf), [dinero](https://github.com/sarahdayan/dinero.js), [and 1 other](data-structures)
* [desktop](desktop)
  * [electron](https://github.com/electron/electron), [electron-react-boilerplate](https://github.com/chentsulin/electron-react-boilerplate)
* [development](development)
  * [build-tools](development/build-tools)
    * [webpack](https://github.com/webpack/webpack), [babel-loader](https://github.com/babel/babel-loader), [and 8 others](development/build-tools)
  * [cli](development/cli)
    * [chalk](https://github.com/chalk/chalk), [commander](https://github.com/tj/commander.js), [and 5 others](development/cli)
  * [documentation](development/documentation)
    * [documentation.js](https://github.com/documentationjs/documentation)
  * [linting](development/linting)
    * [eslint](https://github.com/eslint/eslint), [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint), [and 6 others](development/linting)
  * [logging](development/logging)
  * [parsing](development/meta/parsing)
  * [testing](development/testing)
* [domains](domains)
  * [blogs](domains/blogs)
  * [finance](domains/finance)
  * [food](domains/food)
  * [gaming](domains/gaming)
  * [geography](domains/geography)
  * [machine-learning](domains/machine-learning)
  * [natural-language](domains/natural-language)
  * [networking](domains/networking)
  * [science](domains/science)
    * [chemistry](domains/science/chemistry)
    * [physics](domains/science/physics)
  * [sports](domains/sports)
  * [statistics](domains/statistics)
* [frontend](frontend)
  * [state-management](frontend/state-management)
  * [ui](frontend/ui)
    * [components](frontend/ui/components)
      * [graphs](frontend/ui/components/graphs)
      * [text-editors](frontend/ui/components/text-editors)
    * [react](frontend/ui/react)
    * [react-alternatives](frontend/ui/react-alternatives)
    * [styling](frontend/ui/styling)
  * [utils](frontend/utils)
  * [validation](frontend/validation)
* [graphql](graphql)
* [http](http)
  * [data](http/data)
  * [scraping](http/scraping)
  * [sockets](http/sockets)
* [media](media)
  * [audio](media/audio)
  * [email](media/email)
  * [files](media/files)
  * [images](media/images)
  * [video](media/video)
* [mobile](mobile)
* [serverless](serverless)
* [servers](servers)
  * [authentication](servers/authentication)
  * [databases](servers/databases)
    * [mongodb](servers/databases/mongodb)
    * [postgres](servers/databases/postgres)
  * [middleware](servers/middleware)
  * [parsers](servers/parsers)
  * [scheduling](servers/scheduling)
* [utils](utils)
  * [arrays](utils/arrays)
  * [colors](utils/colors)
  * [currency](utils/currency)
  * [time](utils/date-time)
  * [files](utils/files)
  * [html](utils/html)
  * [ip-address](utils/ip-address)
  * [language](utils/language)
  * [numbers](utils/numbers)
  * [regex](utils/regex)
  * [temperature](utils/temperature)
  * [text](utils/text)
  * [urls](utils/urls)

## Contributions

Know of a great emodule that isn't on the list? Submit a pull request!

## License

MIT

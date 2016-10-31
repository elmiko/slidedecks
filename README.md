# Slidedeck for conference <insert name here>

This repository is based on the
[reveal.js](https://github.com/hakimel/reveal.js) project, it is forked from
the upstream with local modifications for this specific talk.

The documentation from the upstream is contained here in an abbreviated
format, please the [main documentation](https://github.com/hakimel/reveal.js)
for more information.

*Link to presentation or summary goes here*

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

1. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (4.0.0 or later)

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port=8001`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **deck/** The specific information for this presentation's content
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)
<<<<<<< HEAD


## License

MIT licensed

Copyright (C) 2017 Hakim El Hattab, http://hakim.se
=======
>>>>>>> e1ade1e... update license and readme

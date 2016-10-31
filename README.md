# Slidedeck for conference Apache Big Data EU 2016

This repository is based on the
[reveal.js](https://github.com/hakimel/reveal.js) project, it is forked from
the upstream with local modifications for this specific talk.

The documentation from the upstream is contained here in an abbreviated
format, please the [main documentation](https://github.com/hakimel/reveal.js)
for more information.

## Original presentation information

**Building Apache Spark application pipelines for the Kubernetes ecosystem**

[schedule link](https://apachebigdataeu2016.sched.org/event/8U0C)

Apache Spark based applications are often comprised of many separate,
interconnected components that are a good match for an orchestrated
containerized platform like Kubernetes. But with the increased flexibility
afforded by these technologies comes a new set challenges for building rich
data-centric applications.

In this presentation we will discuss techniques for building multi-component
Apache Spark based applications that can be easily deployed and managed on a
Kubernetes infrastructure. Building on experiences learned while developing
and deploying cloud native applications on an OpenShift platform, we will
explore common issues that arise during the engineering process and
demonstrate workflows for easing the maintenance factors associated with
complex installations.

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

1. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **deck/** The specific information for this presentation's content
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)

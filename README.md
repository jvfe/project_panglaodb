# Manuscript - PanglaoDB and Wikidata

<!-- usage note: edit the H1 title above to personalize the manuscript -->

[![HTML Manuscript](https://img.shields.io/badge/manuscript-HTML-blue.svg)](https://jvfe.github.io/manuscript_panglaodb/)
[![PDF Manuscript](https://img.shields.io/badge/manuscript-PDF-blue.svg)](https://jvfe.github.io/manuscript_panglaodb/manuscript.pdf)
[![GitHub Actions Status](https://github.com/jvfe/manuscript_panglaodb/workflows/Manubot/badge.svg)](https://github.com/jvfe/manuscript_panglaodb/actions)
<!-- usage note: delete CI badges above for services not used by your manuscript -->

### Repository directories & files

The directories are as follows:

+ [`content`](content) contains the manuscript source, which includes markdown files as well as inputs for citations and references.
  See [`USAGE.md`](USAGE.md) for more information.
+ [`output`](output) contains the outputs (generated files) from Manubot including the resulting manuscripts.
  You should not edit these files manually, because they will get overwritten.
+ [`webpage`](webpage) is a directory meant to be rendered as a static webpage for viewing the HTML manuscript.
+ [`build`](build) contains commands and tools for building the manuscript.
+ [`ci`](ci) contains files necessary for deployment via continuous integration.

### Local execution

The easiest way to run Manubot is to use [continuous integration](#continuous-integration) to rebuild the manuscript when the content changes.
If you want to build a Manubot manuscript locally, install the [conda](https://conda.io) environment as described in [`build`](build).
Then, you can build the manuscript on POSIX systems by running the following commands from this root directory.

```sh
# Activate the manubot conda environment (assumes conda version >= 4.4)
conda activate manubot

# Build the manuscript, saving outputs to the output directory
bash build/build.sh

# At this point, the HTML & PDF outputs will have been created. The remaining
# commands are for serving the webpage to view the HTML manuscript locally.
# This is required to view local images in the HTML output.

# Configure the webpage directory
manubot webpage

# You can now open the manuscript webpage/index.html in a web browser.
# Alternatively, open a local webserver at http://localhost:8000/ with the
# following commands.
cd webpage
python -m http.server
```

Sometimes it's helpful to monitor the content directory and automatically rebuild the manuscript when a change is detected.
The following command, while running, will trigger both the `build.sh` script and `manubot webpage` command upon content changes:

```sh
bash build/autobuild.sh
```

### Continuous Integration

Whenever a pull request is opened, CI (continuous integration) will test whether the changes break the build process to generate a formatted manuscript.
The build process aims to detect common errors, such as invalid citations.
If your pull request build fails, see the CI logs for the cause of failure and revise your pull request accordingly.

When a commit to the `master` branch occurs (for example, when a pull request is merged), CI builds the manuscript and writes the results to the [`gh-pages`](https://github.com/jvfe/manuscript_panglaodb/tree/gh-pages) and [`output`](https://github.com/jvfe/manuscript_panglaodb/tree/output) branches.
The `gh-pages` branch uses [GitHub Pages](https://pages.github.com/) to host the following URLs:

+ **HTML manuscript** at https://jvfe.github.io/manuscript_panglaodb/
+ **PDF manuscript** at https://jvfe.github.io/manuscript_panglaodb/manuscript.pdf

For continuous integration configuration details, see [`.github/workflows/manubot.yaml`](.github/workflows/manubot.yaml).

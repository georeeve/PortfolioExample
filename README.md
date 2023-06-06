# PortfolioExample
An example portfolio document, built using [Bikeshed](https://github.com/speced/bikeshed).

View the built [HTML version](https://portfolioexample.georeeve.dev/) and [PDF version](https://portfolioexample.georeeve.dev/index.pdf) of the document.

## Setup
First create a venv within this repo, and switch to it.
```shell
python -m venv venv
source venv/bin/activate
```

Then install bikeshed and update its datafiles.
```shell
pip install bikeshed
bikeshed update
```

To build the spec to HTML run `bikeshed spec`.

To convert the HTML document to a PDF document, install weasyprint by following the [instructions for your operating system](https://doc.courtbouillon.org/weasyprint/stable/first_steps.html#installation).
You can then run `weasyprint index.html index.pdf`.

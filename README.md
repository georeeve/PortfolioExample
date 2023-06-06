# PortfolioExample
An example portfolio document, built using [Bikeshed](https://github.com/speced/bikeshed).

[View the built version of the document](https://portfolioexample.georeeve.dev/)

## Setup
First create a venv within this repo, and switch to it.
```shell
python -m venv venv
source venv/bin/activate
```

Then install the dependencies (bikeshed to build to HTML, weasyprint to convert from HTML to PDF)
```shell
pip install bikeshed weasyprint
bikeshed update
```

To build the spec to HTML run `bikeshed spec`.
To convert the HTML document to a PDF document run `weasyprint index.html index.pdf`.

This repository generates [the Profilerpedia
website](https://profilerpedia.markhansen.co.nz/), from the data in the
[Profilerpedia
spreadsheet](https://docs.google.com/spreadsheets/d/1cVcHofphkQqk1yGeuBPVTit8HQ0oa5SlRM6gkHIagtw/edit#gid=1337108655)

See [announcement blog post](https://www.markhansen.co.nz/profilerpedia/).

A Python Jupyter notebook queries the spreadsheet, generating HTML pages, which
are then compiled into a beautiful Docsy site using Hugo static site generator,
and deployed on Netlify.

I wrote a [blog post about Profilerpedia's architecture: Run a website off a Google Sheets Database, with Hugo](https://www.markhansen.co.nz/build-a-website-off-a-google-sheets-database-using-hugo-netlify/).

[![Netlify Status](https://api.netlify.com/api/v1/badges/9539973f-b40d-4a8f-adfa-9ff1e68eba5a/deploy-status)](https://app.netlify.com/sites/profilerpedia/deploys)

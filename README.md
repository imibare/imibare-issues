# imibare-issues

Public issue tracker for [imibare](https://imibare.org), an open data
infrastructure project making African government statistical data
programmatically accessible. Rwanda and Kenya are the pilots.

**This repository holds issues only.** There is no code here, and the pipeline
that produces the data is not public.

## What to open an issue for

**A number looks wrong.** The most useful thing you can report. Include the
dataset ID (for example `ke.knbs.fuel-sales.annual`), the value you believe is
wrong, what you think it should be, and the original source if you have it.
Every dataset page links to the publication its figures came from, so the
comparison is usually quick to make.

**A dataset is missing.** Say which institution publishes it and where it lives.
Requests are the fastest way to find out which numbers people actually want,
which is not always the ones that are easy to get.

**Something on the site is broken.** A chart that will not load, a download that
fails, a page that returns a 404.

**A question about the data.** How a column was derived, why two datasets that
look related do not add up, what a unit means. If two datasets seem like they
should reconcile and do not, that is worth asking about: sometimes it is a bug,
and sometimes the source measures two different things under similar names.

## What imibare does not claim

imibare does not own the data. It extracts, cleans and republishes what
government statistical offices publish, with provenance attached: where each
figure came from, when it was retrieved, and what changed in cleaning.

Each dataset page records what imibare understands its publisher's terms to be,
and links to the original, which is the authority. Where a publisher states no
terms, the page says so rather than assuming a grant. Where a publisher
affirmatively reserves rights, imibare does not republish. The full position is
at <https://imibare.org/terms>.

If you have a rights question about a particular dataset, the publishing
institution is the right place to ask.

## Elsewhere

- Catalog and documentation: <https://imibare.org>
- Python client: `pip install imibare`
- API: <https://api.imibare.org>

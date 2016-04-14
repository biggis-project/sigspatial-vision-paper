# BigGIS paper for SIGSPATIAL 2016
[SIGSPATIAL'16 Conference](http://sigspatial2016.sigspatial.org/)

- **Abstract Submission:** Jun 14, 2016 (midnight PT)
- **Full Paper Submission:** Jun 21, 2016 (midnight PT)
- **Notification of Acceptance:** Aug 23, 2016
- **Conference:** Oct 31 - Nov 3, 2016, San Francisco Bay Area, California, USA

## Guidelines
General:
- use the [issue tracker](https://github.com/biggis-project/sigspatial16-paper/issues) when possible
- use LaTeX for authoring the paper
- the template is 2-column ACM format as described here: http://www.acm.org/publications/proceedings-template
- generated PDF should not be versioned (already listed in [`.gitignore`](.gitignore))
- [github releases (git tags)](https://github.com/biggis-project/sigspatial16-paper/releases) will be used for making a particular PDF version available for download (e.g. when the paper has been submitted)

Figures:
- there should be **one person** responsible for all figures (using input from others)
- all figures are stored in a single directory: [`figures`](figures)
- from LaTeX-point-of-view, all figures are either vectors (PDF) or rasters (JPEG at 300 dpi)
- both source and generated figures are under version control
- open-source authoring tools are preferred (for interop and automating reasons):
  - inkscape, dia, open/libreoffice, gimp, R, ...
- suggested input formats:
  - photos, screenshots: **PNG** or **JPEG** (90% compression) at **300 dpi**
  - workflows, activity diagrams or simialr: **ODG, DIA. SVG**
  - deployment-, component- or similar diagrams: **SVG, ODG, DIA**
  - box plots, bar charts, scatter plots, correlation plots or similar: **R**
- automated conversion possible:
  - on Linux, you can use [figconv](https://github.com/vsimko/figconv) to automatically convert multiple input vector formats to PDF. It is, however, not required.

## Type of the paper

### Vision Papers
Authors are invited to submit vision papers describing visionary
ideas to be presented at the conference. Submissions are limited
to **4 pages** — append “(Vision Paper)” to the title.

### Demonstration Papers
Authors are invited to submit demo papers describing original
demonstrations to be presented at the conference. Submissions
are limited to **4 pages** — append “(Demo Paper)” to the title.
Accepted demo papers will appear in the conference proceedings.

### Industrial Experience and Systems Papers
Industrial experience and systems papers are invited that describe
original industrial experiences, challenges, and applications,
as well as systems to be presented during the conference. Industrial
Experience and Systems paper submissions are limited to **10 pages**
— append “(Industrial Paper)” or “(Systems Paper)” to the title as is
appropriate. Accepted Industrial Experience and Systems papers will
appear in the conference proceedings.

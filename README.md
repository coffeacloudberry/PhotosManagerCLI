# Photos Manager

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) [![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/) [![Checked with mypy](https://camo.githubusercontent.com/34b3a249cd6502d0a521ab2f42c8830b7cfd03fa/687474703a2f2f7777772e6d7970792d6c616e672e6f72672f7374617469632f6d7970795f62616467652e737667)](https://mypy.readthedocs.io/en/stable/introduction.html "Mypy is an optional static type checker for Python") [![CodeQL](https://github.com/coffeacloudberry/PhotosManagerCLI/workflows/CodeQL/badge.svg)](https://github.com/coffeacloudberry/PhotosManagerCLI/actions/workflows/codeql-analysis.yml) [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=coffeacloudberry_PhotosManagerCLI&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=coffeacloudberry_PhotosManagerCLI)

ONLY AVAILABLE FOR LINUX.

Two files are required to add a new photo:

* NEF ([raw Nikon file](https://www.nikonusa.com/en/learn-and-explore/a/products-and-innovation/nikon-electronic-format-nef.html)),
* pp3 ([RawTherapee sidecar file](https://rawpedia.rawtherapee.com/Getting_Started)).

If not available, then JPG or PNG can also be used.

The [Google webp command line encoder](https://developers.google.com/speed/webp/docs/using) is required. This project includes a downloader. Any internet connection (specifically to Google servers) will be prompted. The downloaded archive is the official library, which is PGP-signed by the WebM team and verified before opening the archive.

Notice that the WebP converted does not read the Exif orientation metadata, so the image has to be rotated if needed.

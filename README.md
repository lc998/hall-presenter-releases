# Hall Presenter releases

The packages of Hall Presenter, and `manifest.json`, which the program reads to
find out whether a new version exists. Nothing about the person or the computer
is sent; the program only downloads this file.

The releases and the manifest are published by the release workflow. News
can be added to `manifest.json` by hand; check it first with
`python publish_manifest.py --check manifest.json`.

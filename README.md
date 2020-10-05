# DIAG Website content

This repository stores all the content and source code for the DIAG websites. From this repository multiple Pelican-powered websites are built, based on a central content database.

[![Build Status](https://travis-ci.org/DIAGNijmegen/website-content.svg?branch=master)](https://travis-ci.org/DIAGNijmegen/website-content)

## Websites

Live websites:

- Pathology: https://www.computationalpathologygroup.eu
- Retina: https://www.a-eyeresearch.nl
- RSE: https://rse.diagnijmegen.nl
- AI for Health: https://www.ai-for-health.nl
- RTC: https://rtc.diagnijmegen.nl
- DIAG (main website): https://www.diagnijmegen.nl

## Updating the content

Please see the [documentation](https://github.com/DIAGNijmegen/website-content/tree/master/docs) for guides on updating the sites.

## Building the website locally

To build a website:

1. Run `./parse_publications.sh` to parse the .bib file.
3. Run `WEBSITE=website-pathology ./copy_content.sh` to copy files for any website (pathology in this example).
2. Run pelican in `website-pathology` (or any other website): `pelican --autoreload`
3. Start the development server: `pelican --listen`

(On Non-windows you can combine step 2 and 3 with `pelican --autoreload --listen`)

To build the css:

4. Run css build in `radboudumc-theme`: `npm run deploy-watch`

### Building with Docker

Run the following scripts in your bash:

```
docker build –tag website-content-docker .
docker run -it -p 8000:8000 -v <path-to-website-content>:/website-content/ website-content-docker bash
cd website-content
```

We will use the dummy bib files here with the following command:

`python ./bibliography/bibparser.py`

If you want to work with the full bib files, setup your GitHub token and set `GH_BIB_TOKEN` in your environment before you run the following command:

`./parse_publications.sh`

Then resume with setting up your website of choice. 
If it is `website-diag`, then run the following:

```
WEBSITE=website-diag ./copy_content.sh
cp -r assets/* website-diag/output/
cd website-diag
pelican --autoreload --listen
```
The website should be running at `http://localhost:8000/` on your browser.

To work on CSS:
```
curl -sL install-node.now.sh/lts | bash
cd radboudumc-theme
npm install
npm run deploy-watch
```

## Design resources

If you design an image/poster or similar for the website, please store the
design files (if not too big) in the directoy `content/src/` in the apropriate
subtree. This allows others to update media more easily should they ever become
outdated.

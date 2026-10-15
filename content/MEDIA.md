# Portfolio media in Decap

## Project and homepage folders

Each project now has its own entry in `content/projects/<project-id>/index.json` and a media folder at `assets/projects/<project-id>/`. Cover and gallery pickers open that project's folder. Use **Upload files together** in Project gallery to stage a batch, add captions, arrange it, and publish the project to commit the files together.

Homepage settings are in `content/homepage.json` and homepage media is in `assets/homepage/`. The Photo strip supports the same batch upload controls.

The original `content/portfolio.json` and general library below remain available for compatibility.

## General Media library

The site's existing images, videos, and PDFs are stored in `assets/uploads`, which is the folder the live Decap media library reads.

Open **Media** in Decap, or choose an image/file from a project field. Search by project name:

- `tonys-table--`
- `telemidi--`
- `jim-thompson--`
- `ecopinet--`
- `ev-charging-hub--`
- `buzztile--`
- `sandbox--`
- `bloom--`
- `homepage--`

The prefixes preserve the association with each project while keeping the files directly visible in Decap's media folder. Existing project content continues to use its original site asset paths. Selecting a file from Decap inserts its GitHub media URL.

`content/site-media.json` records each original site path, its corresponding Decap media path, and a checksum. New uploads can be added directly through Decap.

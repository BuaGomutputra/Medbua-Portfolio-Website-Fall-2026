# Portfolio media in Decap

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

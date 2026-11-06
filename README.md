# email-assets

Hosted image files for DigX email signatures.

| File | What it is |
|---|---|
| `emblem.png` | DigX emblem, PNG |
| `emblem.svg` | DigX emblem, SVG |

## Do not rename or move these files

Email signatures load these images from this repository by URL, for example:

`https://raw.githubusercontent.com/nikitazhylkin/email-assets/main/emblem.png`

An email that is already sent keeps that URL forever. If a file is renamed, moved or deleted, the image breaks in every email that used it. To change the artwork, replace the file content and keep the same name and path. To add a new image, add a new file.

## Who to ask

Nikita Zhylkin, nikita@digx.agency

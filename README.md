# Site content

Content for gudrunsteenandersen.com. Edited through the CMS and published with the
studio menu of the engine repository – there is normally no need to touch git here.

Every entity is one YAML file. Danish values are at the top of the file, German and
English ones under `de:` and `en:`; an empty translation shows the Danish text.

- `data/sections/` – menu entries (home, about, free_works, …)
- `data/collections/` – groups of items, shown under one or more sections
- `data/items/` – works: name, description, images, collections, tags
- `data/images/` – one entry per image file: photographer, caption
- `data/documents/` – texts shown on section pages
- `data/slideshows/` – sequences of images and videos
- `data/tags/` – keywords for items and documents
- `assets/images/` – the image files; `static/files/` – PDFs

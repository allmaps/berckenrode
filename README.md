# Van Berckenrodekaart

This repository contains static level 0 [IIIF Image API](https://iiif.io/api/image/2.0/) tiles of the 17th century Van Berckenrodekaart of the city of Amsterdam (Collection [Allard Pierson](https://allardpierson.nl/)). The map was digitized by photographer [Henni van Beek](https://www.hennivanbeek.nl/) on February 7, 2025.

Links to view and annotate the map:

- [IIIF Presentation Manifest](https://amsterdamtimemachine.github.io/berckenrode-iiif/manifest.json)
- [Open in Allmaps Editor](https://editor.allmaps.org/#/collection?url=https://amsterdamtimemachine.github.io/berckenrode-iiif/manifest.json)
- [Open in Allmaps Viewer](https://viewer.allmaps.org/?url=https://amsterdamtimemachine.github.io/berckenrode-iiif/manifest.json)
- [Open in Theseus Viewer](https://theseus-viewer.netlify.app/?iiif-content=https://amsterdamtimemachine.github.io/berckenrode-iiif/manifest.json)

Technical information about the map:

| Property            | Value                |
| ------------------- | -------------------- |
| Physical dimensions | 156.5 x 139 cm       |
| Image dimensions    | 39125 x 34708 pixels |
| DPI                 | > 600                |
| Scale               | Approx. 1:1950       |

This image will replace the existing digitized version of the map in the digital collections of the Allard Pierson, as part of a larger project funded by [Stichting PICA](https://www.stichtingpica.nl/). The project–a collaboration between the [University Library](uba.uva.nl) of the University of Amsterdam, the [Amsterdam Time Machine](https://www.amsterdamtimemachine.nl/) and [Allmaps](https://allmaps.org/)–also includes the improvement of the map collection's metadata and the further development of [Allmaps Here](https://here.allmaps.org/).

More information:

- [Allard Pierson verwerft unieke 17de-eeuwse wandkaart van Amsterdam](https://allardpierson.nl/nieuws/allard-pierson-verwerft-unieke-17de-eeuwse-wandkaart-van-amsterdam/)
- [Amstelredamum emporium Hollandiæ primarium totiusque Europæ celeberrimum](https://hdl.handle.net/11245/3.39844)

---

The tiles were made with [Sharp](https://sharp.pixelplumbing.com/) using [these scripts](https://github.com/sammeltassen/iiif-tiler). For compatibility the `iiif` layout was used (v2) and the tile height was added to the `info.json`. The IIIF Presentation Manifest was made using [this Notebook](https://observablehq.com/d/46eb57ecfeded102).

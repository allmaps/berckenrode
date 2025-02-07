# Van Berckenrodekaart

This repository contains static level 0 [IIIF Image API](https://iiif.io/api/image/2.0/) tiles of the digitised Van Berckenrodekaart of the city of Amsterdam (Collection [Allard Pierson](https://allardpierson.nl/)). Endpoint:

`https://allmaps.org/berckenrode/KZL_W_X_020/info.json`

Links:

- [Open in Allmaps Editor](https://editor.allmaps.org/#/collection?url=https%3A%2F%2Fallmaps.org%2Fberckenrode%2FKZL_W_X_020%2Finfo.json)
- [Open in Allmaps Viewer](https://viewer.allmaps.org/?url=https%3A%2F%2Fannotations.allmaps.org%2Fimages%2F7762a9646a2516ca)

| Property            | Value                |
| ------------------- | -------------------- |
| Physical dimensions | 156.5 x 139 cm       |
| Image dimensions    | 39125 x 34708 pixels |
| DPI                 | > 600                |
| Scale               | Approx. 1:1,950      |
| Date                | 1630s                |

<!-- 39125 / 61.61417 = 635.00003327
34708 / 54.72441 = 634.2325116 -->

_This image will replace the existing digitised version of the map in the digital collections of the Allard Pierson, as part of a project funded by [Stichting PICA](https://www.stichtingpica.nl/). The project–a collaboration between the [University Library](uba.uva.nl) of the University of Amsterdam, the [Amsterdam Time Machine](https://www.amsterdamtimemachine.nl/) and [Allmaps](https://allmaps.org/)–also includes the improvement of the map collections's metadata and the further development of [Allmaps Here](https://here.allmaps.org/)._

More information:

- [Allard Pierson verwerft unieke 17de-eeuwse wandkaart van Amsterdam](https://allardpierson.nl/nieuws/allard-pierson-verwerft-unieke-17de-eeuwse-wandkaart-van-amsterdam/)
- [Amstelredamum emporium Hollandiæ primarium totiusque Europæ celeberrimum](https://hdl.handle.net/11245/3.39844)

---

The tiles were made with [Sharp](https://sharp.pixelplumbing.com/) using [these scripts](https://github.com/sammeltassen/iiif-tiler). For compatibility the `iiif` layout was used (v2) and the tile height was added to the `info.json`.

# geo-data

Map data for the **World geography** section of [Make Me Smarter](https://makemesmarter.in), served by GitHub Pages at `https://makemesmarter.in/geo-data/`. The app and the website download a country's detailed map from `packs/` the first time it is opened.

- `packs/<ADM0_A3>.<sha12>.mmgeo`: one file per country in the MMGEO format (specified in the app's `geo_engine/FORMAT.md`). Names carry the file's hash, so a file never changes once published, and files are never deleted (except to remove a map that must be corrected).
- `releases/<release>.json`: what each data release added.
- `ATTRIBUTION.md`: the sources of the data, their licences and the required credit lines (added with the first data release).

The files are made from open data (Natural Earth, USGS, NASA, GEBCO, the World Bank, Wikidata and others; see `ATTRIBUTION.md`). India's boundaries are drawn according to India's official position, simplified for small-scale maps. These maps are for learning, not navigation, and they are not an authoritative statement on any boundary.

# Miniproject: Topographic Tarot

The project aims to explore terrain pattern detection (or at least a small demonstration of it). By applying CLIP to LIDAR-derived elevation patches from Iceland, it matches landforms to symbolic prompts based on visual-textual similarity.

Although presented through a game, the method serves as a prototype for unsupervised landform classification. It demonstrates how elevation data can be interpreted using pretrained vision models without labeled training sets, offering a lightweight alternative for exploratory geospatial analysis. The project combines raster data handling, patch extraction, and CLIP-based semantic analysis into an interactive interface.

#Data and setup:
Data was obtained from https://atlas.lmi.is/mapview/?application=DEM, tile 47 was used in the project.

Setup is recreatable through the uploaded conda environment file.



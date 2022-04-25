rolling-cubes-jackson
=============

Puzzle game implemented in [JavaFX](https://openjfx.io/) based on the Model-View-Controller (MVC) architectural pattern.

Game results are stored in JSON documents, using Jackson. Reusable classes `FileSystemRepository` and `ResourcesRepository` added to support both read-only and modifiable documents. Users can select the files with the use of JavaFX's `FileChooser` class.

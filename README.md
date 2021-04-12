# biketag-editor
The editor interface for a given BikeTag game.

## Do you want to create this project?
The BikeTag Team is seeking a developer to create and run with this project to aid the existing, manual, inadequate process that the BikeTag Team currently has for editing BikeTag Images. Since BikeTag uses Imgur, exclusively at the moment, for it's images and data, this editor would allow the BikeTag Team to make corrections to games and address issues that arise in a timely manner.

### Project Requirements
This project should provide the following featureset:

1. Uses the [`node-imgur`][node-imgur] npm package, or a browser compatible Imgur API that is similarly feature-rich.
2. Provides a login strategy using an imgur account, to obtain access to the Imgur API credentials needed to use the imgur package.
3. Provides a way to view all images within an Imgur album, paginated, and sortable by tagnumber.
4. Provides a way to edit the title and description of a given image within a given Imgur album.
5. Provides a way to move an image from one Imgur album to another Imgur album.
6. Provides a way to delete a given image from a given Imgur album.
7. Provides a way to search for an image based on values in the title or description.

Ideally, this project would be written in Vue but React is an acceptable alternative. Scaffolding can be provided for setting up a development server and build process for any desired Javascript frontend stack. To make such requests, add issues to this project and they will be recieved by the BikeTag Team.

[node-imgur]: https://www.npmjs.com/package/imgur

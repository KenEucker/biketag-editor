# biketag-editor
The "editor" interface for BikeTag game administration, supporting admin roles and BikeTag Ambassador logins for managing BikeTag data from the Queue to Settings to Players and Tags. 

## Do you want to create this project?
The BikeTag Team is seeking a developer to create and run with this project to aid the existing, manual, inadequate process that the BikeTag Team currently has for editing BikeTag Images. Completion of this project would mean that the BikeTag Team can finally scale to meet the demand of new games each month without manual code deployments and developer intervention. 

## Project Requirements
This project should provide the following featureset:

1. Uses the [`biketag`][biketag-api] npm package, or a browser compatible Imgur API that is similarly feature-rich.
2. Provides a login strategy using social login with Google accounts.
3. Provides a way to view all images within an Imgur album, paginated, and sortable by tagnumber.
4. Provides a way to edit the fields of a given tag of a selected game.
5. Provides a way to verify tags, moving them from the queue album the main game album and updates the new mystery Tag data.
6. Provides a way to delete a given tag from a selected game, which moves it to the archive album.
7. Provides a way to search for tags based on the Tag fields.
8. Provides a way to view and edit all of a selected game's settings in a table.
9. Provides a way to edit players of a selected game.
10. Provides a way for new ambassadors to be invited to a selected game by an admin role.
11. Provies a way for new game data to be created for a new game by an admin role.
12. Provides the sanity studio editor, a React app, on a special page used by the admin role only.

This project is to be written in TypeScript using Vue, and interacts with the BikeTag game server(s) purely using the biketag client API.

[biketag-api]: https://www.npmjs.com/package/biketag

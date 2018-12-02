Sumo logic Hiring Hackathon problem statement.

Create a pseudo web app file browser. Should let users create and display nested project structures and provide file handling functionality.

Minimum Requirements:

-Show the file browser with proper indentation based on nesting. 
---Default state for every folder is closed.
---View can have multiple folders.
---Use data in the file provided for rendering the view.

-Add the file/folder inside any folder. 
---A way to show the file, No need to create an actual file, Just create a dummy file item, Show that file as an item in the folder.

-Delete any file/folder, implement TrashBin.

-View and see the detial of of the content.
---Created at/Updated at, Owner etc
---Search view for searching files/folders/


Intermediate!

-Update any file and folder(name of file/folder)
-Restore/empty operation from trash.
-Drag and drop moving of file. 
-Recently viewed.	


Advanced!

-Update/Delete/add/get it O(1)
-Infinite Scroll
-Keyboard Handling
-Use local storage for persisting data.


Expectations
-Implement using Json.
-CRUD folder and files.
-Drag and Drop.
-Long/Short in local storage and load them on demand.
-All Crud operations mentioned above should happen update shortjson in local storage.
-Infinite scroll on long json.

Long Json
http://hck.re/jimM8z
Short Json
http://hck.re/yNa9a3
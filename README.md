# FileBrowser


A simple PHP file manager. The code is a single php file.

1.Just copy index.php to a folder on your webserver.
You can raise:
1) Music files mp3.
2) Video mp4 files up to 8MB.
3) Slides.
4) Photos.
5) Zip files and more.
You can create a repository, a folder as well and delete it without touching any important file.

Why it is good:
 Single file, there are no images, or css folders. Ajax based so it is fast, but doesn't break the back button.
 Allows drag and drop file uploads if the folder is writable by the webserver  more like Dropbox, and less like Windows Explorer.
 Works with Unicode file names.


# Warning!!!
1. Do not allow uploads on the public web.
2. If you allow uploads on the public web, it is only a matter of time before your server is hosting and serving very illegal content.
3. Any of the following options will prevent this:
Don't make the folder writable by the webserver.

# LOGIN LATER -->
No file browser login created. 
The login will be added to the project later. 
The login username and password in the README.md file will also be added.


# Attention!
Edit feature. 
An extension of the initial project which lets you edit files and save them from the main php file.
Works asynchronously with ajax requests.

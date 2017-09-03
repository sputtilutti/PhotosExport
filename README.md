# PhotosExport
Apple (mac) Photos export script. AppleScript that exports photos

I wanted a solution to automate export of images in Photos. The photos are organized in albums within folders:
```
  <Folder>
    <Album>
      <photos>
```
Photos are exported to a given location on your disk and maintains the folder-album structure through directories.

# Dependencies

Requires [Photos Utilitities library](https://photosautomation.com/scripting/script-library-01.html)

# Usage

1. Open the script in Mac Script Editor
2. Modify the destination (`dest`) path to where you want your images to be exported
3. Click "run"

Directories will be created if they do not exist. 
Before exporting the image, it will check that the image is not already in the directory.


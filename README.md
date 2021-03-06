# custom_bookmarks

These images are 16x16 pixel icons of identical design, with different fill colors. Their primary purpose is to be used with the [bookmark extension](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) in VScode to replace the default bookmark icon.

These icons are designed to model the bookmark icon found in Visual Studio 2017.

# Customize the bookmark icon in VScode

1. Install the [bookmarks extension](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) for VScode

2. Create local folder to put bookmark images into and clone the repo
    ```bash
    git clone https://github.com/techCarpenter/custom_bookmarks.git
    ```
    (or you can just download the repo zip file)
3. Add setting to the settings.json file:
   ```json
   "bookmark.gutterIconPath": "c:\\path_to_icon\\icon.png"
   ```
4. **(Optional)** Update the keybinding for 'Bookmark Toggle' to 'Ctrl+K Ctrl+K' (if you wish to mimic Visual Studio)
5. Enjoy your customized bookmarks!
   ![red bookmark](./bookmark_images/bookmark_red.png)
   ![goldenrod bookmark](./bookmark_images/bookmark_orange.png)
   ![yellow bookmark](./bookmark_images/bookmark_yellow.png)
   ![green bookmark](./bookmark_images/bookmark_green.png)
   ![blue bookmark](./bookmark_images/bookmark_blue.png)
   ![lightskyblue bookmark](./bookmark_images/bookmark_lightskyblue.png)
   ![violet bookmark](./bookmark_images/bookmark_mediumslateblue.png)
   ![white bookmark](./bookmark_images/bookmark_white.png)

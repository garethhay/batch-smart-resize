batch-smart-resize
==========
[GIMP](http://gimp.org) script-fu for batch resizing images.
- Maximum height and width can be specified.
- Crops to layer mask.
- Optional padding in any color to the full maximum dimensions.

At this time the script probably only works on Windows. I am hoping to add support for all operating systems soon.


#### Installation
- Download https://github.com/per1234/batch-smart-resize/archive/master.zip
- Unzip and move the file batch-smart-resize.scm to your GIMP scripts folder. You can find the location of the scripts folder by going to **Edit > Preferences > Folders > Scripts**.
- If GIMP is running click **Filters > Script-Fu > Refresh Scripts**.


<a id="usage"></a>
#### Usage
The script dialog can be accessed at: **File > Create > batch-smart-resize**.
- **Source Folder** - The folder that contains the source images.
- **Destination Folder** - The folder where the processed images will be saved to.
- **Output Type** - File type to use for the processed images.
- **Output Quality** - Determines the compression level for JPEG Output Type. A higher value will produce better image quality and larger file size.
- **Max Height** - The maximum height of the processed image.
- **Max Width** - The maximum width of the processed image.
- **Pad** - If this box is checked then the script will add background to size the image to the full maximum dimensions. This can be useful to avoid having sites such as Etsy and Handmade at Amazon crop your image thumbnails to an arbitrary aspect ratio.
- **Padding Color** - Color used for padding if enabled.

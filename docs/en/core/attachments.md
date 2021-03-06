# The Sidebar

The sidebar is a context-sensitive element that displays relevant additional information regarding your current directory and current file. You can open it by using either the paperclip icon in the toolbar or by pressing `Cmd/Ctrl+?`.

![The sidebar with one file and a list of references](../img/attachment_sidebar.png)

Inside the sidebar, there are two areas. The first is titled "Attachments" and contains a list of all additional, non-Markdown files that reside inside your currently selected directory. These can be images, Word documents, PDF files, and literally any other file type. You can choose what files will be displayed there by adding the extension of the file type in the respective [preferences](../reference/settings.md) option, which you can find in the "Advanced" tab. The extensions are case-insensitive, so adding `.jpeg` will show `.jpeg` files as well as `.JPEG` and `.JpEg`.

![In the advanced settings, you can choose all extensions that you would like to see in the sidebar.](../img/settings_advanced.png)

The second area, titled "References," contains a list of all your bibliographical entries that you've used in your current Markdown file. It resembles the list of references that will be generated by `pandoc-citeproc` once you export your Markdown file. Thereby, you can check whether or not you've used the right citekeys to reference your sources. [Learn more about citing with Zettlr](../academic/citations.md)

## Attachments

Think of the files displayed in the attachment sidebar as an alternative to having a file browser window open at all times. This way you can see files you might need to work with additionally from within Zettlr, keeping the friction of your workflow manageable.

![With a folder selected that contains images, you can easily add them to your document by dragging them into the editor.](../img/attachment_sidebar_images.png)

In case you need to view all files within the currently selected directory, you can open the directory by clicking the pop-out icon next to the title. This will open the folder with your default file browser.

Clicking on a file in the sidebar will open it with the default system application. This is the same as double-clicking a file in your file browser. Additionally, you can drag and drop the files onto your Markdown document. This will create a link to the file so that you can reference files from within your document. Mostly, you will use this feature for dealing with images, as Zettlr detects common image extensions and wrap the image not within a link-tag, but an image-tag. This way you can easily add images from a folder by dragging them on your opened file. To reference images from a sub-folder, simply make sure to select the subfolder in your tree view or in the file list. Then, the attachment sidebar will refresh with all the images from your newly selected folder.

## References

The references are a list of sources from your Markdown file. The list doesn't do a lot, except simply displaying the correct citations for these sources using the built-in CSL-style. It is meant as a way to give you a list of everything you've cited at a glance to check if you've referenced the correct sources, and whether or not you've missed one.

The attachment sidebar will stay open even in distraction free, giving you the possibility to have the references list side-by-side with your document as you write.

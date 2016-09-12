---
layout: post	
title: Import Assets
excerpt_separator: <!--more-->
summary: How to import different files to AE.
categories:
tags:
date_edited: Sep 2, 2016
---



You can create graphics within After Effects (with some limitations) but if you have any photographic images or videos, etc., then you will need to import files into After Effects for further adjustments and animation.

One thing very important to remember is that After Effects project file (.aep) *does not* contain the source files you import. In other words, you cannot embed the source files into aep files. So, it is crucial that you come up with a good project file/folder structure and keep everything within the same folder. Otherwise, every time you move the files around, the linkage will be broken and After Effects will complain that it cannot find the files. (There is a way to fix this but it will take time.)




## Import Images
After Effects support many types of image file formats. If your image has an alpha channel, it will support that as well. You can either go to `File > Import > File...` or double-click on the project panel to bring up the import dialog.




## Import PSD
{% include figure.html src="/images/import-assets/psd-import-dialog.png" alt="PSD file import dialog" caption="PSD file import dialog" %}

When you import a PSD file, you will see a popup dialog. You can treat the PSD file in two different ways. If you import as `Footage`, AE will treat it like a regular image file. All the layers will be merged into one. Or, you can specify which layer you want to import by `Choose Layer`. Only the layer selected will be imported into AE.

You can import a PSD file as `Composition`. Then, the PSD file is imported as a composition with its own timeline, and you will see all the layer setup as well as the blending modes and a few other parameters from the file, which is very convenient.

`Composition - Retain Layer Sizes` will retain the size of individual layers if their sizes are different from the document size.


## Import AI
Importing an AI file is very similar to importing a PSD file. Vector shapes are retained so they can be scaled up or down without losing quality. 




## Import Image Sequences
When you have an image sequence to import, you can either import as individual files for a better control over each, or import as a single sequence for a convenience. After Effects will recognize file names with a numeric sequence*(ex. filename-01.jpg, filename-02.jpg, etc.)*. If you don't like to import as a sequence, uncheck the box at the bottom, in this case, `PNG Sequence`.

{% include figure.html src="/images/import-assets/import-sequence.png" alt="Import sequence dialog" caption="Import sequence dialog. Notice the PNG Sequence box is checked." %}

### After importing
After you check the `PNG Sequence` and import, you may have to change the way AE interprets your sequence depending on what frame rate you are working with. Select the sequence from the project panel, right-click and select `Interpret Footage > Main...`. From there, change the frame rate to the one that matches your project.

If you don't check the `PNG Sequence` and import, you will see individual files in the project panel. You can simply drag and drop them into a composition. By default, every layer takes up the entire comp length. While all the files are selected, trim it down to the frame length you want, then right-click, and select `Keyframe Assistant > Sequence Layers...` and hit OK. All your selected layers will be automatically sequenced out.




## Making changes to already imported files
Sometimes, you have to make changes to your source files *after* you import them. When that happens, you don't have to import the updated file from scratch. Simply, right-click on the file name in the project panel, and choose `Reload Footage`.

{% include figure.html src="/images/import-assets/reload-footage.png" alt="Reload Footage" caption="Reload Footage" %}

You will instantly see all the compositions that use the file are updated. However, any new layers you added to the source file *after* you import will not show up. In that case, manually import only the new layers.




## Further Learning
- More information on [Importing and interpreting footage items](https://helpx.adobe.com/after-effects/using/importing-interpreting-footage-items.html)
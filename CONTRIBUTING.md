<!--
SPDX-FileCopyrightText: 2023 Machine-Learning-OER-Collection
SPDX-License-Identifier: CC-BY-4.0
-->

# Contribution

Thank you for your interest in this project.

There are many ways to support us. This guide lets you know how to take part.

### Issues 

If you want to communicate with us, open a new issue. We recommend using labels to ease grouping the issues by their purpose.

#### Issue types

Label name: idea  
Ideas for new material

Label name: question  
For more information

Label name: feedback  
For feedback or mistakes

### Make changes

Remember that all material in this repo is made available under a CC-BY-4.0 and CC0 license.

* Fork the repo.
* Create a working branch.
* Commit changes.
* Push branch.
* Send a pull request (PR). If your changes are related to an issue, link to it.  
* The PR is reviewed.
* The PR can be merged.

### Commit message

Minor changes:
* Create a one-line message.
* Start with a capital letter.
* Use the imperative mood.

Major changes:  
Create a message with a subject line and description to explain what was done and why.

Example:

    $ git commit -m "subject line
    
    short description of what and why"

## Style Guide

### Folder structure
Create for each algorithm one folder with subfolders for images, text and code.

### Code
* Start code with a title.
* Add reference.
* List the used libraries.
* Provide a link to the data source and terms of use. Make sure that it is compatible with the license.
* Provide links to relevant functions and helpful information.
* Document the code. 
* Create .license file.

### License

* For images and .ipynb files, create a .license file and add the SPDX-FileCopyrightText and SPDX-License-Identifier as comments with a # and the actual year.
```
# SPDX-FileCopyrightText: $YEAR $NAME
# SPDX-License-Identifier: CC-BY-4.0
```
* For markdown files, add the SPDX-FileCopyrightText and SPDX-License-Identifier as comments with 
```
<!--
SPDX-FileCopyrightText: 2023 Machine-Learning-OER-Collection
SPDX-License-Identifier: CC-BY-4.0
-->
```
* For more information, see [License.md](/License.md)



### Images
* Use SVG as file format for the images. The open-source software [Inkscape](https://inkscape.org/de/) can be downloaded for creation and editing.
* Use levels to separate text and image objects in the SVG file. This helps to improve the reusability between users with different languages.
* Adjust the canvas size to fit to the image.
* Insert reference in Inkscape under File > Document Properties > Metadata. 
    * Insert references in the image like title, author, license with link and source with link. Optionally, the CC logo can be added, see [Download](https://creativecommons.org/about/downloads/) and [policies](https://creativecommons.org/about/downloads/).
* Create .license file
* If you reused the image and modified it, indicate it, see [Marking your work with a CC license](https://wiki.creativecommons.org/wiki/Marking_your_work_with_a_CC_license).
* Additionally, you can provide a gallery in the readme file of the img folder. This simplifies the browsing of the SVG files.

Layout tips:  
* Don't use the colors green and red to show differences because of color blindness.
* Label diagrams with title.
* Label axes.
* Insert a legend.

### Text snippets
* Use a markdown file format for your text snippets.
* Start with a title.
* Link to the images in the text snippets.
* Use [blocks](https://www.markdownguide.org/basic-syntax/#code) for the code examples.
* Add reference.
* Add license.


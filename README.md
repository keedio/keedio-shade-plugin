# keedio-shade-plugin
This plugins is based on maven-shade-plugin. It has been remiplemented the SimpleRelocation class in order to relocate only the dependency jars not provided excluding the class defined on the main project.

The include tags were deleted so, all dependency libs not tagged as provided/included/test on the pom file are automatically added to the shade jar and relocated to avoid version conflicts

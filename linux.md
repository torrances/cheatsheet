*copy files (by extension) into a target directory without maintaining the target directory structure*
find -type f -iname '*.xml' -exec cp {} ~/temp \;
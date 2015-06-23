*copy files (by extension) into a target directory without maintaining the target directory structure*
find -type f -iname '*.xml' -exec cp {} ~/temp \;

*count the number of files in a directory*
ls -l . | wc -l
*copy files (by extension) into a target directory without maintaining the target directory structure*
find -type f -iname '*.xml' -exec cp {} ~/temp \;

*count the number of files in a directory*
ls -l . | wc -l

*copy a certain number of files from one directory to another*
find . -maxdepth 1 -type f | head -10000 | xargs cp -t $destdir
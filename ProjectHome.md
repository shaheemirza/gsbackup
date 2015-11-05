This project is a python extension to the python gsutil program that was released by the Google Storage team.
Instead of calling cp `*` to copy and rewrite over your files, calling gsproject will only copy over the files that have different modification time or filesize.

On first run the program copies over everything
Concurrent runs download the db file to check for changes.
#!/bin/bash


cp  /mnt/cache/appdata/FolderViewEdits/docker.js /usr/local/emhttp/plugins/folder.view/scripts/docker.js

sh copy_to_git.sh

sh pkg_build.sh

chmod 777 folder.view.plg
chmod -R 777 /mnt/cache/domains/folder.view/folder.view/.git

echo "Finished"
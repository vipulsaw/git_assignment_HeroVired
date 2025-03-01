# git_assignment_HeroVired
## Integrate Git LFS

## Install lfs
 git lfs install
## Create new branch and swithch to it lfs
git checkout -b lfs

## specify the files
 git lfs track "*.mkv"

## Add and Commit large file
 git add largefile.bin

## Commit the changes
 git commit -m "Add large binary file using Git LFS"

## Push changes to repository
 git push origin lfs

## Go to other machine and Download and verify
 git lfs pull




 

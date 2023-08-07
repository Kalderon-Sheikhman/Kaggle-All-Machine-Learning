o associate a file type in your repository with Git LFS, enter git lfs track followed by the name of the file extension you want to automatically upload to Git LFS.

$ git lfs track "*.psd", replace psd with the file extension in your path...
git lfs install
git lfs track "*.csv"
git lfs push --all origin main
git add .
git commit -m 'large file'
git push -u origin main
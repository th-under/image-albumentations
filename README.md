# image-albumentations
increases the number of given images by some variations for deep learning purposes


Sorry for the long list of requirements. 
I had some version conflicts with albumentations.

The following command is added for convenience if you like to rename (renumber) all .png files in the working directory.
bash>  ls -v | cat -n | while read n f; do mv -n "$f" "$n.png"; done

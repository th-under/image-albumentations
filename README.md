# image-albumentations
increases the number of given images by some variations for deep learning purposes

The following command is added for convenience. It numbers all existing .png files in the current directory to 1.png, 2.png, 3.png, ...

bash>  ls -v | cat -n | while read n f; do mv -n "$f" "$n.png"; done

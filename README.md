# GlossEditing

# About
This application controls gloss perception by detecting gloss in an image and highlighting or suppressing glossy areas.<br>
(https://www.ingentaconnect.com/content/ist/jist/2021/00000065/00000006/art00007)

# How to use
1. Put the image files in the img directory. (Note: Currently, only BMP format is supported.)
2. Edit all images in the img directory at once by running "./gestart".
   Use the option "-p" to edit the image with an arbitrary scale factor.
   The scale factor is specified as an arbitrary integer. A positive value emphasizes gloss, a negative value suppresses gloss.
   Example: ./gestart -p 5
3. The glossy edited image will be saved in the result directory.<br>
(Confirmed to run on Ubuntu 20.04 LTS)

# Execution example
![Fig7(a)](https://user-images.githubusercontent.com/92371944/141085159-a461dcff-2b39-47ab-843e-3200f61fec83.png)
<br>original image<br>
![Fig7(b)](https://user-images.githubusercontent.com/92371944/141085262-a689e3a9-613d-45c4-a5c1-d56c4d6046c4.png)
<br>Enhanced image (scale factor 15)<br>
![Fig7(c)](https://user-images.githubusercontent.com/92371944/141085448-3aabeb58-22e4-41b7-8dce-d79ee274520b.png)
<br>Suppressed image (scale factor -5)<br>

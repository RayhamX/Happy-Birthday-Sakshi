# Assets

This repository contains the web app for "Two Worlds, One Birthday".

The site expects the following files in the assets/ directory:

- Image-01.jpg  (hero day)
- Image-02.jpg  (hero night)
- Image-04.jpg
- Image-05.jpg
- Image-06.jpg
- Image-07.jpg
- Image-08.jpg
- Image-09.jpg
- Image-10.jpg
- Image-11.jpg
- Image-12.jpg
- Image-13.jpg
- icon-192.png
- icon-512.png

Notes & next steps:
- Add high-quality JPG images named exactly as above into the assets/ folder.
- The manifest references icon-192.png and icon-512.png; add PNG icons with those names.
- If you want placeholders now, you can create small images with the correct filenames (e.g., using ImageMagick):

  convert -size 800x1000 xc:'#eee' -gravity Center -pointsize 36 -annotate 0 'Image-01' assets/Image-01.jpg

- After adding images, commit and push; the site will render correctly.

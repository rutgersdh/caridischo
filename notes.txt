# Batch resize and crop

$ magick mogrify -path h600 -resize 1200x600 -quality 100 *.png
$ magick mogrify -crop 1200x300+0+0 -path ../banner *.png
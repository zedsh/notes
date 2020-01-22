```
find samples/ -type f -name *.jpg -exec ~/slugify.sh -r {} \;
find samples/ -type f -name *.jpg -exec ~/translate.sh {} \;
find samples/ -type f -name *.jpg -exec mogrify -format png {} \;
find samples/ -type f -name *.jpg -exec rm -f {} \;
```

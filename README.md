<details>
<summary>Itxy Dec 2024</summary>

`docker run --platform=linux/amd64 --rm --entrypoint /bin/bash -v /Users/selie/Documents/Projects/Engrave/Coasters/itxy:/imgs docker.io/samuelrad/potracemagick -c "magick /imgs/IMG_8721.png -units PixelsPerInch -resample 32 -alpha remove -ordered-dither h6x6a  pgm:- | potrace --svg --flat --group --color=#FFFFFF --opaque -t 0.0001 -O 0.001 -z random -u 1 -a 0.0001 -H 8.070866 -o /imgs/lovley-72-h6x6a-black.svg"`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/itxy-2024-12/itxy-32-h6x6a-white.svg">
  <img alt="Logo" src="images/itxy-2024-12/itxy-72-h6x6a-black.svg">
</picture>

</details>


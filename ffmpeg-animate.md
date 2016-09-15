# Frame animation

ffmpeg -r 15 -i /path/to/frm/dir/frm%05d.png -vcodec libx264 -pix_fmt yuv420p -vf “scale=-1:1080” -q 0 /path/to/mov/dir/mov.mp4

Notably, the scale=1920:-1 option scales output to 1080 pixels of height, adjusting width to preserve aspect ratio. This *may* run into a problem with the width resolution not being even, which will result in an error.

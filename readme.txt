A free and open source computer chip builder down to the silicon (soon). It *should* be able to eventually "emulate" these circuits and possibly be used to work with verilog and VHDL as an IDE to program FPGA chips in the future too. This project is being created by scratch in c/c++ and will work on Linux, MacOS, and Windows.




HOW TO GOURCE (in your shell): gource --hide dirnames,filenames --seconds-per-day 0.1 --auto-skip-seconds 1 -1280x720 -o - | ffmpeg -y -r 60 -f image2pipe -vcodec ppm -i - -vcodec libx264 -preset slow -pix_fmt yuv420p -crf 18 -threads 0 -bf 0 gource.mp4

# Mutate
A multi-node, multi-threaded and massively parallel media transcoder.

## Synopsis

### Example: Basic Usage

Check out the available presets for each command before diving in...

    mpresets mreader mwriter

Search the file system for supported media files...

    mreader ~/Media1 /var/media2/

Easily convert any supported media type to another...

    mwriter -p webm480 file.mp4 output.webm

### Example: Scheduling Mutate Tasks

    mwriter -p webm1080 -t my_video.mp4 my_smaller_video.webm

## Installation Notes

Crude right now, but leveraging cpanminus and the cpanfile format for declaring dependencies. 

    sudo cpanm --installdeps .  

I know I should have perlbrew based instructions and have these deps installed locally. I know, maybe we'll get there...

## License
MIT

## Copyright
2015 - 2017 Dan Stephenson (ispyhumanfly)

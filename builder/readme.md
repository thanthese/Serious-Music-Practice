# Requirements

Basically, Ubuntu.  Plus:

## Timidity

    sudo apt-get install timidity

## Espeak

Pre-installed

## Midish

Grab the source from the [official website](http://caoua.org/midish/):

Make sure you have all its dependencies

    sudo apt-get install gcc make libasound2-dev libreadline-dev

Then, assuming you downloaded this file:

    http://caoua.org/midish/midish.tar.gz

the following commands should work:

    tar -xzvf midish.tar.gz
    cd midish
    ./configure
    make
    make install

I had some directory permissions problems.  Overzealous use of

    sudo chmod -R 777 <wherever>

cleared that right up.

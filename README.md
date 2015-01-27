# JEEJ
It's a game prototype. It should be awesome but we don't know yet. Maybe it's the answer to life, or the secret of the magic. Nobody could ever now. Once it'll be release, you might be able to try it and shatter space and time... or maybe not.

## Who are we ?
My friend name is _GGG_, it stands for _Guillaume Gomez de la Galère_, he's a strong boy which love to sculpt his own body and make it the perfection. He's smart and loves C++. He might add some infos to this. Later. If he gets some time between push-ups and jogging.

My fullname is _Bastien Duplessier_, also known as _Zangther_. I'm the original bad guy. I love to be hated and people love hating me. I consider myself as the best in the world in everything I do, and no I didn't steal this one. He did it. I watch some random videos on Youtube and show them to my friends in order to melt their brain in. I was born to be alive, I was born to annoy people. Welcome to this project page, WELCOME TO HELL.

## Why this game ?
Because.

## What will it be ?
A game.

## You find that funny ?
Yes.

## Some random question.
Some random answer.

## Developper section

### What is required ?

You need :
- SFML : A C++ library (http://www.sfml-dev.org/)
       -> Install CMake
       -> Install Boost (https://svn.boost.org/trac/boost/wiki/CMakeConfigAndBuild)

### Any problems ?

#### How to compile ?
You can check this, it explains how to : https://github.com/JoeDralliam/Ocsfml/wiki/Use-Ocsfml

#### I got some weird messages like "Error: Error on dynamically loaded library: [...]: cannot open shared object file: No such file or directory
If it's related to SFML, check if LD includes the SFML libraries. If not, add "include {SFML_PATH}/lib" into the /etc/ld.so.conf file. Then run ldconfig as super-user.

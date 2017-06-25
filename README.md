# travis_arduino_stl

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_arduino_stl.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_arduino_stl)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:

 * Build system: Arduino
 * C++ compiler: Arduino
 * C++ version: Arduino
 * Libraries: Arduino library and STL
 * Code coverage: none
 * Source: one single file, `main.cpp`

More complex builds:

 * [none]

Less complex builds:

 * No STL: [travis_arduino](https://github.com/richelbilderbeek/travis_arduino)

## Details

For compiling, [ino](https://github.com/amperka/ino.git) is used. It works great! 

The main function is put in `src/travis_arduino_stl.ino`. It is required by [ino](https://github.com/amperka/ino.git)
that the sketch is in a `src` folder.

## More complex examples

 * [![Build Status](https://travis-ci.org/richelbilderbeek/ApproxyClock.svg?branch=master)](https://travis-ci.org/richelbilderbeek/ApproxyClock) [ApproxyClock](https://github.com/richelbilderbeek/ApproxyClock)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/IsClock.svg?branch=master)](https://travis-ci.org/richelbilderbeek/IsClock) [IsClock](https://github.com/richelbilderbeek/IsClock)
 * [![Build Status](https://travis-ci.org/richelbilderbeek/PiClock.svg?branch=master)](https://travis-ci.org/richelbilderbeek/PiClock) [PiClock](https://github.com/richelbilderbeek/PiClock)

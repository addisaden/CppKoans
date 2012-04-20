#CppKoans

Inspired by [RubyKoans](https://github.com/edgecase/ruby_koans) and 
[JavaScript-Koans](https://github.com/liammclennan/JavaScript-Koans), this is an attemt to write 
such koans for C/C++.

Some ideas were taken from [PointerKoans](https://github.com/paytonrules/PointerKoan).

###Prerequesites
You will need [CMake](http://cmake.org/) and the 
[Boost Unit Testing Framework (UTF)](http://www.boost.org/doc/libs/1_49_0/libs/test/doc/html/index.html).

##How to walk the path to enlightment
-# Get the sources:  
       git clone git://github.com/torbjoernk/CppKoans.git
-# Create a build directory
       cd CppKoans
       mkdir build
       cd build
-# Configure the build
       cmake ..
-# Compile
       make
-# Run
       ./CppKoans

Now follow the instructions printed from the very beginning.
The files, you will need to edit are in `CppKoans/koans`.
Each time you saved a file and want to rerun the koans, you need to compile it first.
Thus, walking the path to enlightment is a repetition of these steps:
-# Edit and save a file in `CppKoans/koans`
-# Compile in `CppKoans/build` by running `make`
-# Read the master's reply with `./CppKoans/build/CppKoans`

##Licence
Not yet defined. Will come soon.

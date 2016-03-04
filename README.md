# palien [![Build Status](https://secure.travis-ci.org/plicease/App-palien.png)](http://travis-ci.org/plicease/App-palien)

Command line interface to Alien::Base

# SYNOPSIS

    % palien --cflags libfoo
    % palien --cflags Alien::Foo
    % palien --libs libfoo
    % palien --libs Alien::Foo

# DESCRIPTION

This program provides a command line interface to the data stored in
Alien modules.  It is geared primarily for use with Alien::Base based
distributions, but it will attempt to work with non-Alien::Base based
Alien distributions as well.

# OPTIONS

## --bin\_dir

Print out a list of directories with executables in them.

## --dir\_sep _string_

Lists of directories are output separated by _string_, which defaults to ` `.

## --cflags

Print out the compiler flags for the compiler

## --detail | -d

Print out details for each package specified

## --dll

Print out the DLLs, one per line

## --libs

Print out the library flags for the linker

## --modversion

Print out the package version.

## --help | -h

Print out the usage for this command

## --version

Print out the version of this command

# AUTHOR

Graham Ollis &lt;plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2015 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.

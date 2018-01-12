# Stamp Basic II Compiler

This program is a Linux compiler for the Parallax Stamp BASIC II.  

I found this version after some degree of googling (Parallax only links
to the 1.4 version; not sure if this was taken over or is a separate
project at all).

Copyrights:
 - tokenizer.so - Parallax, Inc. (www.parallax.com)
 - the rest of the code - Adrian Schneider
   (adrian.schneider@tiscalinet.ch)
   - NOTE: I tried emailing, received a bounce message from the ISP.


## Changes

These are the changes I needed to make in order to compile (with
warnings)

 - defs.h - added #include <limits.h>
 - stampbc.cc, SBTokenizer.cc, SBCompiler.cc - added #include <stdlib.h>

## Misc

I'm hardly a developer or anything, and probably introduced loads more
problems than I fixed.  Use at your own risk.

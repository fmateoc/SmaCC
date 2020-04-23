# SmaCC
This is a fork of John Brant's SmaCC ( see https://github.com/j-brant/SmaCC ).
Please note that this is not a github fork of the above repository, because it uses a different format for the source code

Since I am not using Pharo, I am also not using their repository format for Smalltalk sources (tonel).
I chose instead the classic Smalltalk fileout format. 

To export the code in fileout format, I loaded the latest Glamorous Toolkit in Pharo 8.0, then I filed out all the SmaCC packages.
It was not fast, but it was conceptually easy - if you know of a better way to do it, please let me know.

One file per package is not a nice granularity for browsing code, but Smalltalk is not made to be browsed as files anyway.
This does look to me as the most convenient way for sharing the code.
It is very easy to export (file out) a whole package from an image, it is also very convenient to file a whole package in

# Why doesn't the file work if I unpack the .zip file on my Apple Mac? #

.rp is a compressed file format and by default OSX unpack both the .zip and the .rp file it contains. At the present time, our recommendation is to unpack the .zip using Windows (which you need to run Axure RP anyway).

# Why are you providing a .zip file instead of a .rp file? #

If you make a .rp file available for direct download from a standard web server, Internet Explorer will append .zip to
the name of the file. Of course, if a user then tries to unzip it, they'll get a directory of files Axure RP can do nothing with, rather than the original .rp file.

The best solution would be to modifty the web server config so it serves a .rp file with the correct mime type, but as we're using code.google.com to host the download, this isn't an option.

So, it's better to avoid all that confusion, provide it as a .zip file and have people unpack it, despite the above mac issue.

# What's the difference between AXLIB and similar design libraries for Axure RP? #

**It's open source, meaning contributions are welcome from all.** Other libraries available at present (November 2008) are best described as tutorials or examples you can base work on. Our intention with AXLIB is that it be a robust library of design patterns you can actually use in your wireframes directly.

# How do I report a bug? #

Please use the project issue tracker available here on code.google.com.

# How do I contribute? #

Please join the [AXLIB discussion list](http://groups.google.com/groups/axlib) and post the details there. Link to your built example elsewhere or upload the file to the files area. Suggestions for future patterns are also welcome on the list.
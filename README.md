﻿SharpAvi
========

A simple .NET library for creating video files in AVI format.

If you want to render some video sequence, and do not want to touch DirectShow or depend on command-line utilities - *SharpAvi* may be what you need.
Writing uncompressed AVI does not require any external dependencies, it's pure .NET code. Files are produced in compliance with the [OpenDML extensions](http://www.jmcgowan.com/avitech.html#OpenDML) which allow (nearly) unlimited file size (no 2GB limit).

Video is created by supplying individual in-memory bitmaps (byte arrays). Audio is not currently supported. Encoding of video streams is supported. Included are implementations of encoders for Motion JPEG (requires WPF) and MPEG-4 (requires external VfW codecs). There is basic support for asynchronous operations.
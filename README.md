Monocle
=======

A simple data capture app using the Kinect, based on [Smithers][smithers].

Features
--------

- Visualization of color, depth, infrared, skeleton, and body index
- Capture a shot at the click of a button
- Compress captured shots into a 7zip archive

Installation
------------

1. Install [Visual Studio 2017 Community Edition][vstudio].
2. Install the [Kinect SDK][kinect].
3. Clone the repository, go to its root, and update the submodule using the following command:
    ```
    git submodule update --init --recursive
    ```
4. Open Visual Studio and build the solution. The app will automatically install all the remaining dependencies.

License
-------

Monocle is licensed under the two-clause BSD license.

Monocle uses 7z.dll, which is part of the 7-Zip program, licensed under the
GNU LGPL license. You can obtain the source code from www.7-zip.org.


[smithers]: https://github.com/MPI-IS/smithers
[vstudio]: https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx
[kinect]: https://www.microsoft.com/en-us/download/details.aspx?id=44561
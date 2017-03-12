# AndroidRTC

[![License](https://img.shields.io/cocoapods/l/AFNetworking.svg)](https://github.com/lgyjg/AndroidRTC/blob/master/LICENSE)

[中文文档](https://github.com/lgyjg/AndroidRTC/blob/master/README_CN.md)

AndroidRTC is a webRTC Android Application demo compiled by android studio.
which is implement the code of webRTC androidapp project in $WEBRTC_ROOT_DIR/webrtc/examples/androidapp directory.

I made this code can be compiled and build in the Android studio.

The project adds the associated "*.so" files of webRTC native library. These files are generated by compiling the webRTC project source.
If you need to update, please compile your own.

The webRTC code repository see: [WebRTC Project Source Code](https://chromium.googlesource.com/external/webrtc.git)

How to clone/download the code of webRTC see : https://webrtc.org/native-code/development/

# Getting started

 you could use this project as a base application for your webrtc project.

# Communication
- [Github Issues](https://github.com/lgyjg/AndroidRTC/issues)

# Build

  To build:

  $ git clone git@github.com:lgyjg/AndroidRTC.git 
  $ cd AndroidRTC/ 
  $ git checkout -b master 
  $ ./gradlew build 

# Bugs and Feedback

For bugs, questions and discussions please use the [Github Issues](https://github.com/lgyjg/AndroidRTC/issues).

# Contribution

If you want use this reposity you should better update the code in webrtc_sdk file form the webRTC source code,
welcome take a PR for those updates.


# LICENSE
MIT License

Copyright (c) 2017 yangjg

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

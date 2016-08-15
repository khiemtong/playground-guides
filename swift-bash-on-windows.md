# Download Swift

* Go to [https://swift.org/download/](https://swift.org/download/)
* Download the latest version Ubuntu version (check using `lsb_release -a`, should be 14.04)  
 ```wget https://swift.org/builds/swift-2.2.1-release/ubuntu1404/swift-2.2.1-RELEASE/swift-2.2.1-RELEASE-ubuntu14.04.tar.gz```
* Extract the tarball`

# Install Dependencies

```
sudo apt-get install clang libicu-dev
```

# Setup Environment

* `vi ~/.bashrc` to edit your Bash profile
* Add swift to your path to make access easy
* Append `export PATH=/path/to/swift/usr/bin:"${PATH}"`
* Load your bash profile `source ~/.bashrc`

# Hello World

* Create your swift program `vi hello.swift`
* Type `print("Hello, world!")`, and save
* Run it `swift hello.swift`

# Troubleshooting

* I get this error -- `swift: /usr/lib/x86_64-linux-gnu/libstdc++.so.6: version `GLIBCXX_3.4.20' not found (required by swift)`
 * You've installed the wrong swift package
* I get this error -- error: failed to launch REPL process: process launch failed: 'A' packet returned an error: 8
 * Known issue https://github.com/swiftdocker/docker-swift/issues/9#issuecomment-162134824 (I haven't found a work around for running `swift` to run just the REPL yet)
 * Swift REPL is not currently working from what I can find

# What do I use this for?
 * To play around with a (new) programming language (i.e. when you don't have a Mac handy)
 * Write some scripts in Swift because you can
 * Bask in the idea that you're using Apple created programming language on Linux in Windows





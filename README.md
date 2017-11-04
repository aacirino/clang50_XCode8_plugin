A XCode 8 plugin to use the LLVM toolchain with clang 5.0, created from Apple's supplied with the specific changes to allow
for the invocation of the toolchain as installed by homebrew, i.e., to use clang as installed in /usr/local/opt/llvm/bin/.

To install the LLVM with home issue the command brew install llvm

To instasll the plugin open the package contents of XCode and copy the plugin to:

Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer/Library/Xcode/Plug-ins/

Or, from the command line from the directory where you downloaded or cloned the plugin, copy the plugin to the destination:

cp -r Clang\ LLVM\ brew.xcplugin /Applications/Xcode.app/Contents/PlugIns/Xcode3Core.ideplugin/Contents/SharedSupport/Developer/Library/Xcode/Plug-ins/

I did not have the time to fix the strings file and I think the plugin needs some tweaks. Feel free to contribute.

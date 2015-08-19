# libzbar

command：

lipo libzbar-armv6-armv7.a -thin armv7 -output libzbar-armv7.a
lipo -create libzbar-* -output libzbar.a
lipo -info libzbar.a 


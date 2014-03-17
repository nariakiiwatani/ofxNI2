WORK IN PROGRESS

This is an attempt to run ofxNI2 on Windows with Code::Blocks.
Still not fully working.
Progress is being discussed at the openFrameworks Forum: http://forum.openframeworks.cc/t/openni-with-ofxni2-and-code-blocks/14896

---
OSX:

Add to Run Script

	cp -R ../../../addons/ofxNI2/libs/OpenNI2/lib/osx/ "$TARGET_BUILD_DIR/$PRODUCT_NAME.app/Contents/MacOS/";
	cp -R ../../../addons/ofxNI2/libs/NiTE2/lib/osx/ "$TARGET_BUILD_DIR/$PRODUCT_NAME.app/Contents/MacOS/";
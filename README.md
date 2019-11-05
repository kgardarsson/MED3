# MED3
Programming side of our MED3 project, a collaborative table instrument.

This project is generated with openFrameworks version 0.10.1.

To run it you have to download the ofxFliducialFinder: https://github.com/SafetyOrange/ofxFiducialFinder

One might get a conversion error. To fix this, add '.getData()' to 'input.getPixels()' to both of the fiducial cpp files. So it should look like this:

	const unsigned char* pixels = input.getPixels().getData();


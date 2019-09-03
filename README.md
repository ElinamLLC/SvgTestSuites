# SharpVectors-TestSuites
This repository contains strip down versions of the various W3C SVG Test Suites for use with the [SharpVectors](https://github.com/ElinamLLC/SharpVectors) test applications.
Except in very few cases where the test files were fixed, folders and files not used by the [SharpVectors](https://github.com/ElinamLLC/SharpVectors) were removed to reduce the size of the download files.

The original test suites are available from [Test Suite Overview](https://www.w3.org/Graphics/SVG/WG/wiki/Test_Suite_Overview).

## W3C Test Suites
The repository contains the following test suites
 * **Svg10.zip** - SVG 1.1 First Edition Test Suite: 13 December 2006 (default)
 * **Svg11.zip** - SVG 1.1 Second Edition Test Suite: 16 August 2011
 * **Svg12.zip** - SVG 1.2 Tiny Test Suite: 12 September 2008

## How to use it

### From Application

The test suite applications will automatically display a prompt dialog, if the default tests are not found.
You can use the dialog to download the test suites. After the download, the application will automatically extract the contents to the respective folders.

You can select a particular test suite version from the `Settings Page` of the test application. If a test suite is not locally available, you will be prompted to download it.

### Manually

1. Extract the contents of the zip file (say Svg10.zip file) directly into the `\Samples\W3cSvgTestSuites\Svg10` folder
2. The zip files (say Svg10.zip) contain the following folders
    * images
    * png
    * svg
    * resources (in some cases)

## License

The copyright and test suite distribution are governed by the [W3C Document License](http://www.w3.org/Consortium/Legal/copyright-documents) and the [W3C Member agreement](http://www.w3.org/2003/01/Member-Agreement). 

This policy both promotes the distribution of a test suite as it was agreed upon within W3C and protects the test suite from unapproved modifications that might harm interoperability.  
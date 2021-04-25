Prerequisites
1. Chrome browser in version 90.0.4430.85.
2. Selenium IDE extension in version 3.17.0.

Additional preparations:
1. In test file, specify path to adequate image file, which should be used in the test. This file is specified in lines 134 and 166 if Zoovu1.side is edited via text editor.. Simply change the image location to the one you want to use. If you're using IDE, change "Value" for steps 12 and 15.
2. I wanted to design a test, so it would work either if you visit the page for the first time, or for the 'next' time. Unfortunately, due to a bug in Selenium IDE, I wasn't able to do so. Workaround is to remove comments after first visit on the page. In IDE these are lines 2, 3 and 4. If using a text editor for Zoovu1.side, these are "//" to be removed in lines 19, 26, 33.
3. Waiting for 3 seconds  was necessary here, as this is roughly how long it took on PC for element to load. This is dependant of the test environment.
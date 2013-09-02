## General Matlab Documentation ##

Working with Low Level File I/O and Encodings

http://blogs.mathworks.com/loren/2006/09/20/working-with-low-level-file-io-and-encodings/

Troubleshooting I18n Messages and Settings

http://www.mathworks.com/help/matlab/matlab_env/troubleshooting-i18n-messages-and-settings.html#bsnnwfp-1

Setting the Locale

http://www.mathworks.com/help/matlab/matlab_env/setting-the-locale.html#brkh9v3-1

How the MATLAB Process Uses Locale Settings

http://www.mathworks.com/help/matlab/matlab_env/how-the-matlab-process-uses-locale-settings.html

## Language Settings ##

From: http://www.mathworks.com/matlabcentral/answers/15423
````Matlab
get(0, 'Language');

import java.nio.charset.Charset
encoding = Charset.defaultCharset()

%Read value
feature('DefaultCharacterSet')

feature('DefaultCharacterSet','UTF8'); %An example setting this value
````

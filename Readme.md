# Vim folding for F

This simple vim plugin provides folding for F#. This works slightly better than
vim's build in indent fold, vim's indent fold will only fold the body, This will
include the line decalring the function.

## Future improvements

This is still, like vim's indent fold, based on the shift width of the file.
This produces awkward results when the indentation does not match a multipla of
shift width.

## Credits

This code is a slight modification of [Steve Losh's](http://stevelosh.com/)
[custom fold expression example](http://learnvimscriptthehardway.stevelosh.com/chapters/49.html). 

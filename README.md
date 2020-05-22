Hexagon Game Board (HGB) is a set of classes to create a manageable set of hexagon.

For examples see: https://github.com/gammillweg/HGBExample1 or 
https://github.com/gammillweg/HGBExample2

https://github.com/gammillweg/HGBExample1 is not very useful.  All it does, with a few
lines in an Android Studio MainActivity, is show how easy it is to create a hive.

https://github.com/gammillweg/HGBExample2 is considerably more complex
than HGBExample1.  It draws the hive, has menu picks to zoom in/out,
expand/contract (the size of the hive), fill between last picks,
toggle the cell ID's on/off, And show a report.  One can also move the
hive about, and can pick cells which are filled with a color.  Even so,
it is only a small demo application.

HGB will create many more than 50 thousand hexagons quickly.  And locate
each very accurately and fast.  HGBExample2 is limited to 60 rings,
and in my emulator, easily generates 74347 cells. The locator only has
problems if the cells are very small.

I will be writing an article to be posted on CodeProject.  When complete, this
README will be updated.

The Examples are complete.  I need to do more documentational work in the
HGB classes.  My original thought was to make HGB a library; but I am backing
away form that thought.  I think it best that HGB be handled as a Package.  Then
you will have access to HGBUtils.java to add any code you like.  And if you
choose to cheat and open HGB code to your application, that is your choice.

As I am new on GitHub, I just recently learned of "git clone <URL>"  (You may not know it.)
On a Linux command line, simply type  "git clone https://github.com/gammillweg/HGBExample2"

If you would like to join an effort to improve HGB, write to gammillgit@outlook.com.

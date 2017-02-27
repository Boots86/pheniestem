This is a site my daughter created for her elementary school Science Technology Engineering and Mathematics (STEM) showcase competition.  Currently not optimized for mobile devices.  It seems to work well for Chrome on Android but iPhone users may have issues.  This is primarily b/c the magic of the interactive map is based on hover events.

Things to try to fix this:
+ Checkbox hack
+ Focus pseudoclass

Things that probably won't help:
+ Target pseudoclass because it requires navigating to new link actually
++ could try having the target be a link to a target of the original page, but this requires page reloads
+ Exceedingly long transition effect because no way to get back to the original state

If she gets really into it we might throw in some javascript that should do it easily, but I'd prefer a pure CSS/HTML solution.

# UniStroke_Character_Recognition
A Java Project



I implemented recognition code for digits using Java's Mouse class. I translated the array of points captured by the mouse events through the pattern recognition process. I scaled and normalized those points and compared them with a standard set of patterns, the base set, to find the pattern that best matches the normalized set of points. 
There were several methods that I created while doing the project, namely: findMinX, that returns the smallest x value from the points in the userPoints array, findMinY, that returns the smallest y value from the points in the userPoints array, findMaxX, that returns the largest x value from the points in the userPoints array, findMaxY, that returns the largest y value from the points in the userPoints array, translate, that moved the points in the userPoints array by sliding them as far to the upper-left as possible, scale, that scaled the points in the userPoints array by stretching the user stroke character so it fills the canvas as nearly as possible while maintaining the aspect ratio of the stroke character, computeScore, that computes and returns a score that is a measure of how closely the normalized userPoints array matches a given pattern array in the baseset array, and findMatch, that finds and returns the index of the base set pattern which most closely matches the user stroke.

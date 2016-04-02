# PulseLoadingIndicator
Loading Indicator in Swift

<img src="http://cl.ly/0y0Q3z3k1Q0q" alt="screen shot" >

##Features

1. Easy to use
2. Show a transparent overlay over the whole screen or part of the screen. The overlay will prevent user interaction with the covered controls while the task is in progress.
3. Show animating UIImageView programmatically in the center of the overlay to indicate a task is being processed

##How To Use
Include the PulseLoadingIndicator.swift file.
I've used Cartography framework to set the constraints so you'll need to include it.
Set the Image for UIImageView
######     let activityIndicator = UIImageView()
######     activityIndicator.image = UIImage(named: "logo")
Call hide method to hide the indicator after long running task.

#####Show indicator to cover entire screen
PulseLoadingIndicator.show()

#####Hide indicator
PulseLoadingIndicator.hide()

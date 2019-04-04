# Multiple Storyboards Example


This is an up to date example working with multiple storyboards, and creating link between them. When working with large projects, sometimes creating different story boards that are seperate from the main storyboard provided with a new project, can be helpful. 

The process is pretty simple. 

You first need to start with a base project, and open the object Library. (You can open this with CMD-Shift-L) Storyboard Reference is what you need to find and drag onto the Main storyboard. Link this to a ViewController.

Create a new Story board by going to New -> File -> and Search for Storyboard. 

Name it and make sure that the view in this story board is set to the Intial View Controller. 

Click on the story board reference in the Main View Controller and click the Attributes Inspector.
Where is says Storyboard, make sure that this is the same as the second story bord that you are trying to get to. 

That's it, you can like this to a button or a navigation item, and it behaves just like a segue. 

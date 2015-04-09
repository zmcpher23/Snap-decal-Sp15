# SnapDecal Project

This is the documentation for the SnapDecal project made by Susanna and Zachary.

##Checking for outdated Browser

Our goal is to add a feature to Snap which ensures that the user will not be running outdated browsers
which may lead to compatability/functionality issues within Snap.

Using the **WhichBrowser** [API](https://github.com/WhichBrowser/WhichBrowser) we will determine the version of the users browser and compare that with a list of most
recent versions for the specific browser.

If the user browser version is out of date, we will display a helpful message advising the user to update to 
the latest browser version in order to have the smoothest Snap experience possible.

###Version Checking
Based on user OS we will check for *FireFox* or *Google Chrome*. Since either OS will have a different release system and therefore we must check from a different set of versions for each OS.

###Which Browser API
The **WhichBrowser** [API](https://github.com/WhichBrowser/WhichBrowser) allows us to create a JavaScript object which will allows us to make queries about the Browser specifically which version of the browser the user is running.

##Block Modification
Currently, users can duplicate and delete individual blocks as well as duplicate multiple connected blocks if and only if the user right-clicks for the drop-down menu on the topmost block of the section he or she wants. We would like to give users the ability to right-click any of the other blocks in the connected component as well (i.e. a "duplicate all" option). We would also like to extend this feature to deleting blocks since users currently cannot delete multiple connected blocks.

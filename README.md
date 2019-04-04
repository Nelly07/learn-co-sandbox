
Hi! 👋

You've opened the IDE Sandbox, an environment that you can access on "readme" and "code-along" lessons in Learn. It's a great place to experiment with code! 🎉

*IMPORTANT*
Saving varies by the type of work you are doing:
-- Most of the work you do in the Sandbox is automatically saved on your behalf to the `learn-co-sandbox` repository in your GitHub account. Please DO NOT touch this repository in GitHub. Doing so will affect your Sandbox experience, and potentially cause your work to fall out of sync.
-- *Git repositories that you clone into the Sandbox are NOT automatically saved.* In this case, you are responsible for committing and pushing your work to GitHub. 

To learn more about the Sandbox, please visit http://help.learn.co/technical-support/learn-ide-in-browser/ide-in-browser-sandbox

volume = 10; //declares a global variable called volume and sets it to 10
 
function returnEleven() {
  var volume = 11;  //declares a local variable called volume and sets it to 11
  return volume;
}
 
returnEleven(); // returns 11
volume; // the global variable is still 10
 
function goToEleven(){
  volume = 11;  //changes the global variable to 11
  return volume;
}
 
goToEleven(); // returns 11
volume; // the global variable volume has been changed to 11

# godCoderXYZ.github.io
Hi Members of the Website and Application Development Branch! This is a file in a repository called, "godCoderXYZ.github.io" (ignore the name), containing four files:
- index.html
- script.js
- style.css
- and README.md

in order to edit the files, clone the repository into your local computer by following these instructions: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository, it helped me a lot.

- In step 4, the terminal is the app on ur computer
- In step 5, when it says "Change the current working directory to the location where you want the cloned directory.", its asking you to navigate to the directory (folder) where u want the files to be downloaded on your local computer. You can navigate to any directory by using the command, cd. If you are currently in the Desktop directory and you want to navigate to a folder within Desktop called vscodeProjects, then run the command, cd vscodeProjects. Similarly, if you are in the vscodeProjects directory and you want to exit back into the Desktop directory, run, cd .., with two full stops afterwards. There's also the command, ls, which displays all the possible directories you can go into from your current directory.

Once ur in the directory u want to be in (doesnt even matter - its just the location of the folder thats containing the repository files), then follow steps 6-7 by running the command:
git clone https://github.com/godCoderXYZ/godCoderXYZ.github.io
- If it doesnt work, try replacing godCoderXYZ with your own username (sign into github)

Then just run the code within the HTML, Javascript, and CSS files using your preferred IDE. For me, this is Visual Studio Code.

Once you finish making changes to your code, remember to update the changes by commiting, using the command:
git commit -m "INSERT A MESSAGE HERE"
- for the message, just briefly and generically state what you modified so its easier to identify the changes in the future.

Now, whenever you want to work on the project, make sure that you update your local repository with the github repository, in case other collaborators have made changes to the files while you were offline. To update your local repository, go to your local repository directory and run the command:
git checkout -f main
Then run the command:
git pull
If the terminal doesn't show you any errors, then your files should be updated and now you can continue working on the updated local repository on your computer.

Good Luck!

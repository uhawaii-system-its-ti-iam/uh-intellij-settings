This project will contain the Java and JavaScript code formatting settings for
the UHGroupings project. These settings are made for the IntelliJ IDE.

This guide will walk you through how to import the UH Intellij Settings repository to your own device. 

## Installation Guide

  1. Head to the repository you wish to contribute to, in this case: 
      https://github.com/uhawaii-system-its-ti-iam/uh-intellij-settings.git
  2. Using the Fork button, Fork the repository to your own GitHub account.
     
  3. Next, clone the repository which you have forked, to a local directory. 
Take care if you already have an existing copy of the source code stored locally, 
  that copy must be deleted and replaced with this new copy.

a. Press the green Clone or Download button and get a copy of the repository's URL. 
In this example, the repository used is https://github.com/zakgilbert/uh-intellij-settings.git

b. Open up your command shell and clone the repository to a location of your choosing.

`$ git clone https://github.com/zakgilbert/uh-intellij-settings.git`

c. Now `cd` into the repository you've just cloned and type `ls` to see the repository's contents.

`$ cd uh-groupings-intellij-settings`

4. Now we can set up our upstream and origin remotes.

a. add the repository you forked from as a remote called 'upstream'

`$ git remote add upstream https://github.com/uhawaii-system-its-ti-iam/uh-intellij-settings.git`

b. Set the URL of your forked version of the repository to a remote called origin. (You will need to go back
to the repository from which you forked from to retrieve the url. See step 2)

`$ git remote set-url origin https://github.com/zakgilbert/uh-intellij-settings.git`

Please acknowledge the difference between your forked version of the repository and the original repository from which forked. 
Typing "git remote -v" should return as follows.


`$ git remote -v`

`origin https://github.com/zakgilbert/uh-intellij-settings.git (fetch)`

`origin https://github.com/zakgilbert/uh-intellij-settings.git (push)`

`upstream https://github.com/uhawaii-system-its-ti-iam/uh-intellij-settings.git (fetch)`

`upstream https://github.com/uhawaii-system-its-ti-iam/uh-intellij-settings.git (push)` 

If the above information is congruent with your device (aside from github username), you're all set and ready
to make changes to the repository.

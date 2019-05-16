# Steps to contribute to this repo
* install Git LFS (see Install Git LFS section)
* prepare project folder
* create an empty Unity project
* quit Unity
* delete `ProjectSetting` folder
* prepare the Git repo
  * run git init to make this project a git repo
  * run git remote add origin <remote_repo_address> to add remote repo
  * pull remote branch origin/master to local branch master
  * run git branch develop to create a new local branch develop
  * run git checkout develop to switch to branch develop
  * pull remote branch origin/develop into local branch develop
  * add .gitconfig file for your system to use Unity’s Smart Merge (for steps, [see this official article](https://docs.unity3d.com/Manual/SmartMerge.html))
* open the project in Unity and start to work


# Install Git LFS
For more information about Git Large File Storage (LFS), [see here](https://git-lfs.github.com/).
* For Mac users, installing Git LFS using Homebrew is recommended. To install, just run `brew install git-lfs`.
* For Windows users, download the installer from official website and run. After the installation process, run git lfs install in your git bash to activate it.

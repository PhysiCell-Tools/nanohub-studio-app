# nanohub-studio-app

This repository documents how one can generate a [nanoHUB](https://nanohub.org/) tool (a.k.a, "app") for a PhysiCell model that uses a [PhysiCell Studio](https://github.com/PhysiCell-Tools/PhysiCell-Studio)-style GUI. 

## High-level steps

1. Create a new, public repository in your github.com account that will be used exclusively for your nanoHUB app. 
2. Clone this repo to your computer, e.g.,:
```
   git clone git@github.com:rheiland/pczombies.git
   cd pczombies
```
3. Create a nanoHUB account if you do not have one: https://nanohub.org/register/
  * Students need to be aware that creating an account on nanoHUB is similar to creating an account on any social media platform. Use your good judgment about publicly sharing personal information. For more background, see https://ferpa.iu.edu/safeguarding/index.html
4. Register a new tool for your model: https://nanohub.org/tools/create
  * fill out the basic information for creating your nanoHUB tool. Tool Name should be 3-15 alphanumeric characters, including at least one non numeric character (e.g., ```pczombies```). Although not required, it’s probably wise to also use only lowercase characters. Provide the URL to your newly created GitHub repo (e.g., ```https://github.com/rheiland/pczombies```) and additional information, e.g., shown below. When you finally click the ```Register Tool``` button, you will be told if that tool name has already been taken, however, it may take a few seconds for that to appear. Also, don't worry if you forget to provide some info on this initial form, you can always edit it later.

<img src="./images/register_tool_sec1.png" width="60%">
<img src="./images/register_tool_sec2.png" width="60%">
<img src="./images/register_tool_sec3.png" width="80%">

5. Donwload the latest release of this sample nanoHUB [worms app](https://github.com/rheiland/pcworms/releases) and unzip it into the folder in step 2.

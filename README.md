# OFCR-2019-AutoUpdate

**This tutorial will provide instruction to experience the experimental OFCR auto update system**.

This tutorial presents two approaches: (1) Command line prompt with `Git` (efficient); (2) [GitHub Desktop](https://desktop.github.com/), which has intuitive user interface.



## Command line prompt

Note: This tutorial is for **non-developers**

1. Install Git from [https://git-scm.com/downloads](https://git-scm.com/downloads). Choose appropriate version according to you OS (e.g. Windows x86/x64)
2. Delete all files in folder `\\OFCR_2019_OpenBeta\GameData\Vehicles\OFCR2019`
3. Right click at local vehicle folder (`\\OFCR_2019_OpenBeta\GameData\Vehicles\OFCR2019`), choose `Git Bash Here`. A command line (a window with black screen) will prompt
4. Type `git init && git init . && git remote add upstream https://github.com/OMGCA/OFCR-2019-AutoUpdate.git` then hit `Enter`
5. Type `git pull upstream master:master` then hit `Enter`. The download process will begin. Please wait patiently for all files to finish download
6. Note that first-time download will spend a lot of time, since it is a full download and it is hosted on GitHub. Future updates will only download **updated** files. We expect shorter download time

Enjoy!

## GitHub Desktop

### Step 1: Delete local vehicle folder
**ALWAYS BACKUP YOUR ORIGINAL FOLDER**
![image](https://i.ibb.co/fC9vjSK/step1-1.png)
### Step 2: Register a GitHub account _(optional)_ and download [GitHub Desktop](https://desktop.github.com/)
### Step 3: Choose 'clone repository' and modify path as shown below
Copy https://github.com/OMGCA/OFCR-2019-AutoUpdate.git in the URL tab
![image](https://i.ibb.co/tK8pP3v/TIM-20181225112125.png)
![image](https://i.ibb.co/PCVjYwR/TIM-20181225132330.png)
### Step 4: Wait for the download to complete
It may take longer to download the whole repo initialially. Afterwards, only changed files will be downloaded.
### Step 5: When updating, simply click 'fetch', then wait until 'pull' is available, then select 'pull'
![image](https://i.ibb.co/jvZkNXY/TIM-20181225112315.png)
![image](https://i.ibb.co/M8N2QbK/TIM-20181225112327.png)
**Update Complete**


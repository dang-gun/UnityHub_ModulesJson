# Unity Hub 'modules.json'
This is a collection of ‘modules.json’ files for Unity Hub  
This is a file extracted immediately after installing Unity.  
[Unity editor archive](https://unity.com/kr/releases/editor/archive)
  
There are cases where Unity Hub does not properly recognize it when Unity is installed manually.  
This is a file for making Unity Hub work properly without reinstalling Unity when this happens.”  

[Korean Readme](https://blog.danggun.net/11857)

## Why use it?
It is used when the following error occurs after manually installing Unity and adding it to Unity Hub.
 
- When ‘Add Modules’ does not appear
![When ‘Add Modules’ ?](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_001.png)

- 'Unity 2022.3.20f1 is no longer available from the Hub. For a better experience, we recommend the latest LTS (Long-Term Support) version. You can find all Editor versions in the Installs Archive.' error.
![no longer available](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_002.png)

## How to use

1. Create a folder with the name of the version you want to add in the folder where Unity Hub is installed (default> C:\Program Files\Unity\Hub\Editor). (Example> 2022.3.20f1)
![Create a folder](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_003.png)

1. Put the ‘modules.json’ file that matches the version(Example> 2022.3.20f1) into the folder you created.

1. Move the ‘Editor’ folder located in the installation folder of the separately installed Unity (Unity Editor) (default> C:\Program Files\Unity [version]) to the folder you created (Example> 2022.3.20f1).
![Move the ‘Editor’](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_004.png)

Now, when you run Unity Hub, the added version is displayed and ‘Add Modules’ works properly.
![works properly](https://raw.githubusercontent.com/dang-gun/UnityHub_ModulesJson/main/Images/UnityHub_error_001_005.png)


## contributing
If you want to upload your own ‘modules.json’ file, please contribute through a 'pull request'

#### Precautions when contributing

- Please only upload files that match the version.
- Do not modify other files.


## Unresolved issues
It seems like it should work just by adding it with ‘Locate’ in Unity Hub, but it doesn’t.  
It definitely only works in the folder where Unity Hub is installed.  

If you know the solution to this problem, please leave it in the issue.  

Code Name: Pensieve

mkdir -p ~/workspace
cd ~/workspace
git clone https://github.com/sagarvemuri/pensieve.git
cd pensieve


Web:
In Eclipse:
File -> New -> Java Project
In 'Create a Java Project' page:
  - Project name: PensieveWeb
  - Uncheck 'Use default location' and browse to pensieve/web/PensieveWeb
  - Use an execution environment JRE: select JavaSE-1.7
  - Create separate foldrs for source and class files
  - Click Next
In 'Java Settings' page:
  - Select Libraries tab and configure the path to your Google app engine SDK.
  (you should have downloaded it to your ~/devtools/<sdk-folder-name>).
  - Click finish

Android:
In Eclipse:
File -> New -> Other
In 'Select a wizard' page:
  - Expand Android and select 'Android Project from Existing Code'
In 'Import Projects' page:
  - Browse to pensieve/android and select it.
  - Under Projects, rename the project to 'PensieveAndroid' (hit tab or click outsdie, so that the name registers before clicking finish.)
  - Unselect 'Copy projects to workspace', if checked.
  - Click Finish


Facebook SDK:
https://developers.facebook.com/docs/android/getting-started
In Eclipse:
File -> Import
  - General -> 'Existing Projects into workspace'
  - Select Facebook sdk directory as the root directory.
  - In the list, unselect all, and select only facebook sdk.
  - Unselect 'Copy projects into workspace'.

Right click on the project, 'Android Tools' -> 'Add support library'.
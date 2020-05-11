# SoftwareSecurity2020
Assignments related to the software security module
-------------------------------------------------------------------------------
For the PROJECT FILE  please visit the following link (It is more than 25mb) :
https://drive.google.com/open?id=1e2dhlBngLz2JtJt14rGaznjN70f7q0FV
-------------------------------------------------------------------------------

		--------------------------------------------------
		GAppv3 - Google API V3 - Resource Aggregation App 
		--------------------------------------------------

1. Save the authorization_token.json Client ID in D:\
	[if D:\ is not available please use a desired disk drive for the .json file--->
	
	-change the following ===>

		-> Models -> GDAppRepo -> UserCredentials -> change the drive path

Sample code: using (var stream = new FileStream(@"D:\authorization_token.json", FileMode.Open, FileAccess.Read))

		-> FolderPath = "File Path"

Sample code: using (var stream = new FileStream(@"<Desired File Path>\authorization_token.json", FileMode.Open, FileAccess.Read))

2. Change the file path of the second .json file to the same directory as the first .json file.

	[if D:\ is not available please use a desired disk drive for the .json file--->
	
	-change the following ===>

		-> Models -> GDAppRepo -> UserCredentials -> change the drive path

Sample code: String FolderPath = @"D:\";

		-> FolderPath = "File Path"

Sample code: String FolderPath = @"<file path>";

Important : Make sure <file path> entered is accessible by the web applicaiton and not blocked by antivirus !!!

3. Save the GAppv3 app folder in desired path

4. Run the GAppv3.sln through Visual Studio 

5. Build the project and Run the project

----------------------------------------------------

1. Provide your own Google Drive Credentials and log in

2. Allow access when the user consent form pops up

3. You can then access/ delete the files of your Google Drive from the GDApp. 

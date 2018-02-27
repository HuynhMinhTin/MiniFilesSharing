# Java_Fresher
Mini sharing files
This is a project for gourp 1 in Java Fresher Program at DXC VietNam .
Project 4: Mini File Sharing (MFS) 
1	Description :
MFS is a web application which allows user to share their file to the other over the internet. Users are required to register and login if they want to upload or download any file from MFS. Guest user could browse file by category, size or uploader but cannot download any file from MFS.
2	Functional Specification :
  •	Guest (not login): 
    o	Search file by name, category, uploader, size 
    o	View information of an uploaded file (with comment). 
    o	Register new account. 
  •	Registered user: 
    o	Search file by name, category, uploader, size 
    o	View information of an uploaded file (with comment). 
    o	Upload file with a limitation of file size according to account level 
    o	Download a file from MFS 
    o	CRUD files which have been uploaded by the his/her self 
    o	Comment on an uploaded file. 
  •	Admin: 
    o	CRUD users 
    o	View information of each user from user dashboard 
    o	Upgrade/downgrade level of a user 
  •	System constrains 
    o	Checking uploading every level of user 
      	Bronze: maximum 5MB each upload 
      	Silver: maximum 10MB each upload 
      	Gold: maximum 20MB each upload 
    o	Auto upgrade user level following total size of uploaded files: 
      	Bronze: 20MB 
      	Silver: 50MB 
      	Gold: above 100MB 
    o	Limit on daily downloading quota: 
      	Bronze: Below 50 MB 
      	Silver: Below 70MB 
      	Gold: Unlimited 

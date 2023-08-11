#### To use this as a boilerplate for your new project, you can follow these steps

1. Clone the base boilerplate in the folder **assignment-solution-product** of your local machine
     
    `git clone https://gitlab-cgi.stackroute.in/testing-assignment-group/RestAssured_Postman_Testing_Assignment`

2. Navigate to assignment-solution-product folder

    `cd assignment-solution-product`

3. Remove its remote or original reference

     `git remote rm origin`

4. Create a new repo in gitlab named `assignment-solution-product` as private repo

5. Add your new repository reference as remote

     `git remote add origin https://gitlab-nht.stackroute.in/{{yourusername}}/assignment-solution-product`

     **Note: {{yourusername}} should be replaced by your username from gitlab**

5. Check the status of your repo 
     
     `git status`

6. Use the following command to update the index using the current content found in the working tree, to prepare the content staged for the next commit.

     `git add .`
 
7. Commit and Push the project to git

     `git commit -a -m "Initial commit | or place your comments according to your need"`

     `git push -u origin master`

8. Check on the git repo online, if the files have been pushed

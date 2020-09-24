# SOSC-Workshop
## Hey Developers ! :woman_technologist: :man_technologist:

**Want to know how can we create and submit our first pull Request** :astonished::trophy:
</br>

Tag along we are going to a wonderful journey of GitHub :octocat:
</br>For this excercise we are going to edit the `source code` of this [website](https://sosc-git.netlify.app/) and create a new pull request :triangular_flag_on_post:

 **:green_apple: Step 1 :-**
 
 Go to this [Github Repository](https://github.com/UttamkiniH/sosc-workshop-git) and click on `fork` button :fork_and_knife: in top right corner of your window. When you click on the fork button github will take you to the forked repository of your account.
 
 **:green_apple: Step 2 :-**
 
When you are in the forked repository of your account the next step is to click on the `code` button indicated in green accent:green_circle:. A pop will display where you will be able to copy the  `https URL` of this repostiory. Go ahead and boot up your terminal :computer: or Git-bash and with the help of `cd` or `ls` commmand navigate to your desired folder directory :open_file_folder:.

Run the following command in your terminal
```bash
git clone https://github.com/YOUR_USER_NAME/sosc-workshop-git
```
 **:apple: Step 3 :-**
 
 In order to edit the **source code** of this website first we need to navigate to the folder :file_folder: by typing this command
 ```bash
 cd sosc-workshop-git
 ```
 Since we are adding  some new feature to the file we will do it by :heavy_plus_sign: creating a **seperate branch**. To create a seperate branch in our file type 
 ```bash
 git branch YOUR_NAME
 ```
 here YOUR_NAME can be any name given to the branch
 
 Since we are in the **master** branch we will change the branch from `master` to your newly created  branch by running this command
 ```bash
 git checkout YOUR_NAME
 ```
 YOUR_NAME is the name given to the branch earlier :point_up_2:
 
  **:green_apple: Step 4 :-**
  
  Now that we are in the **sosc-workshop-git** directory, in order to edit the source code :memo: of this website we need to navigate to **dist** folder so that we can open and edit `index.html` file

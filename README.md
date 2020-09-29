# SOSC-Workshop
## Hey Developers ! :woman_technologist: :man_technologist:

**Want to know how can we create and submit our first pull Request** :astonished::trophy:
</br>

Tag along we are going to a wonderful journey of GitHub :octocat:
</br>For this excercise we are going to edit the `source code` of this [website](https://sosc-git.netlify.app/) and create a new pull request :triangular_flag_on_post:

---

 **:green_apple: Step 1 :-**
 
 Go to this [Github Repository](https://github.com/UttamkiniH/sosc-workshop-git) and click on `fork` button :fork_and_knife: in top right corner of your window. When you click on the fork button github will take you to the forked repository of your account.

----
 
 **:green_apple: Step 2 :-**
 
When you are in the forked repository of your account the next step is to click on the `code` button indicated in green accent:green_circle:. A pop will display where you will be able to copy the  `https URL` of this repostiory. Go ahead and boot up your terminal :computer: or Git-bash and with the help of `cd` or `ls` commmand navigate to your desired folder directory :open_file_folder:.

Run the following command in your terminal
```bash
git clone https://github.com/YOUR_USER_NAME/sosc-workshop-git
```
---

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
 
 ---
 
  **:green_apple: Step 4 :-**
  
  Now that we are in the **sosc-workshop-git** directory, in order to edit the source code :memo: of this website we need to navigate to **dist** folder so that we can open and edit `index.html` file

So let us do that First we are openeing **dist** folder by this command
```bash
cd dist
```
and then to open the `index.html` file run this command
```bash
code index.html
```
**:x:  code** is a keyword used to open VS code there are different keywords for different editors
**gedit** for linux to open text editor and  **atom** for atom-ide and plenty more make sure to check the keyword **:x:**

---

**:green_apple: Step 5 :-**

When the text editor or any ide pops up scroll down :computer_mouse: to the text **your name** in `index.html`file. Rename :pencil: the text to **YOUR_NAME** make sure that you dont rename the other users USER_NAME.

After saving the file :heavy_check_mark: we need to `add`and `commit` the file in order to make changes in our Github Repository :card_file_box:

Run this command to `add` the file
```bash
git add index.html
```
and to `commit` the file we can run this command
```bash
git commit -m "YOUR_MESSAGE"
```

---

**:green_apple: Step 6 :-**

Now let us push our changes to our **remote** Github Repository :card_file_box: type the following command
```bash
git push -u origin BRANCH_NAME
```
BRANCH_NAME refers to the name given to your branch in **step 3**
origin refers to remote repository that is your github repository.

---

**:green_apple: Step 7 :-**
  
  Now go to your **forkerd GitHub repository** :file_folder: in Github :card_index_dividers:
  
  There you can see a message :speech_balloon: saying that to **create &  pull request** click on that and add your comment or a message. After that you can just scroll down and click on the **create a pull request** and there you go you have created your first **pull request :astronaut:**
  
  Then the owner:hatched_chick: of this Repository will **merge** the changes and you will be able to see the changes in [SOSC-WORKSHOP](https://sosc-git.netlify.app/) :monocle_face:.

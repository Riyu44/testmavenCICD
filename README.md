##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
First Contributions
This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.


#### fork this repository

If you don't have git on your machine, install it.
Fork this repository
Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

#### Clone the repository
clone this repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command:

git clone "url you just copied"
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

copy URL to clipboard

For example:

git clone git@github.com:this-is-you/first-contributions.git
where this-is-you is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

##### Create a branch
Change to the repository directory on your computer (if you are not already there):

cd first-contributions
Now create a branch using the git switch command:

git switch -c your-new-branch-name
For example:

git switch -c add-alonzo-church
Make necessary changes and commit those changes

Now commit those changes using the git commit command after adding them to the staging area:

git commit -m "Add your-name to Contributors list"
replacing your-name with your name.

Push changes to GitHub
Push your changes using the command git push:

git push -u origin your-branch-name
replacing your-branch-name with the name of the branch you created earlier.

If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

##### create a pull request

Now submit the pull request.

##### submit pull request

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged
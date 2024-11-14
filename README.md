# house-price-prediction
Git and other commands used:

    mkdir <file_name> to create the folder
    cd <file name> to go inside the folder
    git init, initializing folder as git repository
    git add . to add all the files into git track
    git commit -m "<message>", it commits whatever is there in the track
    git remote add origin <GitHub repository link>, builds connection between git and github
    git push --set-upstream origin master, sends all the files from git to github.

Docker Commands:

    docker build -t <file_name> .
    docker run <file_name

Steps:

    Create the required files such as the dataset csv file(house-price-prediction.csv), requirements txt file, training model python file, Dockerfile
    Create a new item under the Freestyle Project in Jenkins
    Select Git in Source Code Management
    Add Execute Windows Batch Command Step in Build Steps
    Save the configurations
    Build now and visualize console output
    Now open the command prompt with the path of the folder containing the required files
    Execute the Docker commands mentioned above
    The output can be visualized in the command prompt and the Docker Desktop app

Output: ![my3 proof execution of house price prediction](https://github.com/user-attachments/assets/d5547cdb-172c-4b7a-86aa-3e00e679d633)

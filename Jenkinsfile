pipeline {
    agent any 
    stages {
        stage("Checkout") {
            steps {
                git branch: "main", url: "https://github.com/mabuelmagdd/Jenkins-Task1.git"
            }
        }
        stage("Run the script") {
            steps {
                sh "./pyscript.py"
            }
        }
    }
}

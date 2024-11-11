pipeline{
  agent any 
  stages{
    stage("Checkout"){
      script {
        git branch: "main", url: "https://github.com/mabuelmagdd/Jenkins-Task1.git"
       }
    }
    stage("Run the script"){
      script {
        sh "./pyscript.py"
       }
    }
  }
}

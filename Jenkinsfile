pipeline{
agent any
  stages{
    stage('Build'){
      steps{
       sh "echo 'Hello Vishwanathan!'"
       sh "git status" 
       sh "git fetch origin main"
       sh "git pull origin main"
       sh "git status" 
      }
    }
  }
}

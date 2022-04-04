pipeline{
agent any
  stages{
    stage('Build'){
      steps{
       sh "echo 'Hello Vishwanathan!'"
       sh "git status" 
       sh "git fetch origin main"
       sh "git pull origin main"
       sh "git checkout main"
       sh "git status" 
       sh "git pull origin main" 
       sh "git commit -am 'test commits1'"
       sh "echo 'commits successful'" 
      }
    }
  }
}

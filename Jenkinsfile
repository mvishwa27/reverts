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
       //sh "echo '\n hello2'>>revert_test1.txt" 
       //sh "git commit --allow-empty -am 'test commits1'"
       //sh "echo 'commits successful'" 
        
       git add -A 
       if ! git diff-index --quiet HEAD; then
       git commit -m 'Message here' \n
       git push origin main" 
       echo 'done'
        
       //sh "git pull origin main" 
       //sh "git push origin main" 
      }
    }
  }
}

pipeline {
  agent any
  stages{
    stage('code checkout '){
      when {
        branch 'devlop'
      }
      steps{
      echo "code checkout successful"
            }
       }

    stage('maven build '){
      when {
        branch 'test'
      }
      steps{
      echo "successfully project build in test branch"
            }
       }

    stage('tomcat deployment '){
      when {
        branch 'main'
      }
      steps{
      echo "Application successfully deploied to tomcat server "
            }
       }
  }
}

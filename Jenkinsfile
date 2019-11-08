pipeline {
   agent any

   stages {
      stage('Build Project') {
         steps {
            sh "javac HelloWorld.java"
         }
      }
      stage('Test') {
         steps {
            echo 'Testing project'
            sh "java HelloWorld"
         }
      }
      stage('Deploy') {
         steps {
            echo 'Deploying...'
         }
      }
   }
}
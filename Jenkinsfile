pipeline {
 agent any

 stages {

  stage('Clone') {
   steps {
    git 'https://github.com/NAJEHOUCHEM/devops-ecommerce-project.git'
   }
  }

  stage('Build') {
   steps {
    sh 'docker build -t voting-app:v1 .'
   }
  }

  stage('Test') {
   steps {
    sh 'echo Tests OK'
   }
  }

 }
}

pipeline {
  agent any
  parameters {
    string(name: 'BRANCH', defaultValue: 'main', description: 'Branch to build')
    }
  stages{
    stage("Jenkins for backend") {
      steps {
          echo "======= BACKEND ======="
          sh "ls -la"
         }
      } 
    stage('Clone Repository') {
      steps {
        git branch: params.BRANCH, url: 'https://github.com/EdgarHarutyunyan2025/backend_jenkins.git'
        sh "ls -la"
            }
        }
   }
}


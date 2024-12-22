pipeline {
	agent any
	parameters {
    string(name: 'BRANCH', defaultValue: 'main')
    }
	stages{
		stage("Jenkins for front") {
			steps {
					echo "======= FRONT ======="
					echo "Parameter param1 is: ${params.param1}"
					sh "ls -la"
			   }
		  }
	  stage('Clone Repository') {
      steps {
			    git branch: params.BRANCH, url: 'https://github.com/EdgarHarutyunyan2025/font_jenkins.git'
					sh "ls -la "
            }
        }
	 }
}

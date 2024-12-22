pipeline {
	agent any
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
          git 'https://github.com/EdgarHarutyunyan2025/font_jenkins.git'
					sh "ls -la "
            }
        }
	 }
}

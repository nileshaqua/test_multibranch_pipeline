pipeline{
	agents any
        stages{
	  stage('build'){
                      steps{
		           'echo "build is successful..."'
                            sh 'systemctl status jenkins'
                            sh 'docker build -t myimage'
                           }
			}
		}
	}

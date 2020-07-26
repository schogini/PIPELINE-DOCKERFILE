pipeline {
	agent {
		dockerfile true
	}
	stages {
		stage('First'){
			steps {
				echo "Hello I am inside the custom docker image"
				sh 'cat /usr/share/nginx/html/index.html'
			}
		}

	}
}


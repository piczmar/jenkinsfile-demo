pipeline {
    agent {
    	node{
        	label 'docker'
    	}
	}
	stages {
        stage('Example') {
            steps {
                nodejs(nodeJSInstallationName: 'Node 6.x'){
                    sh 'npm config ls'
                    sh 'npm --version'
      				sh 'npm install'
                }
            }
        }
    }
}


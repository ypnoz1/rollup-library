pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				//bat for windows, sh for linux
				echo 'Start install...'
                bat 'npm install'
				echo 'Start build...'
				bat 'npm rollup'
            }
        }
    }
}
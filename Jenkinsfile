pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo ‘build step executing’
            }
        }
	stage(‘test’) {
            steps {
                echo ‘test step executing’
            }
        }
    }
}

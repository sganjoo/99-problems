pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh “echo build step executing”
            }
        }
	stage(‘test’) {
            steps {
                print ‘test step executing’
            }
        }
    }
}

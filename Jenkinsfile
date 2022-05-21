pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
                sh 'echo hello'
		sh '''
		  echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}

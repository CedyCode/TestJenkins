pipeline {
    agent { docker { image 'gcc' } }
    stages {
        stage('build') {
            steps {
                sh 'gcc --version'
            }
        }
    }
}

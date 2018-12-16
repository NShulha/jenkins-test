pipeline {
    agent { docker { image 'ruby' } }
    stages {
        stage('build') {
            steps {
                bash 'ruby --version'
            }
        }
    }
}

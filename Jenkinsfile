pipeline {
    agent any 
    stages {
        stage ('verfiy version') {
            steps {
                sh 'docker run --rm flyway/flyway'
            }
        }
    }
}
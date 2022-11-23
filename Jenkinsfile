pipeline {
    agent any
    triggers {
        cron "0 0 * * FRI"
    }
    stages {
        stage('Echo') {
            steps {
                echo 'Trigger auto '
            }
        }
    }
}
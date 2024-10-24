@Library('icit-scripts')_

pipeline {
    agent {
        label 'ubuntu'
    }

    stages {
        stage('Notify') {
            steps {
                notifyZohoSuccess('Kidalo', 'https://kidalo.testing.icitdev.nl')
            }
        }
    }
}

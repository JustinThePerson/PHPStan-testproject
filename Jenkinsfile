@Library('icit-scripts')_

pipeline {
    agent {
        label 'ubuntu'
    }

    stages {
        stage('Notify') {
            steps {
                notifyZohoSuccess('Kidalo test was een geintje', 'https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs')
            }
        }
    }
}

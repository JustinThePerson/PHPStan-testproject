pipeline{
    agent{
        label 'ubuntu'
    }
    stages{
        stage('Test notification') {
                notifyZohoSuccess('Dit is een test', 'https://test.com')
            }
    }
}

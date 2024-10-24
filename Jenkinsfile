@Library('icit-scripts')_

pipeline{
  agent{
    label 'ubuntu'
  }
  stages{

    stage('Test') {
      notifyZohoSuccess('Dit is een test', 'https://test.com')
    }
  }
}

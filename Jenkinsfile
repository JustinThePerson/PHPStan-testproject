pipeline{
    agent{
        label 'ubuntu'
    }
    stages{
    stage('Test notification') {
    try {
                // Test success notification
                echo "Testing success notification..."
                notifyZohoSuccess('Dit is een test', 'https://kidalo.acc.icitdev.nl')
                echo "Success notification test completed"
            } catch (Exception e) {
                echo "Test failed: ${e.getMessage()}"
            }
    }
    }
}

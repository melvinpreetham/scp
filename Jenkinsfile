node {
    stage('Checkout') {
        // Checkout the code from the Git repository
        checkout scm
    }

    stage('Build') {
        // Run Maven clean and test
        sh 'mvn clean test'
    }
}


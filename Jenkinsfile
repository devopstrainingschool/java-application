pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "3.8.6"
    }

    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                
                // Run Maven on a Unix agent.
                sh "mvn  clean"

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }

            
        }
    }
}

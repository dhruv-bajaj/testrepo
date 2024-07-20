pipeline {
    agent any
    tools {
        nodejs "nodejs"  // Ensure this matches the name configured in Manage Jenkins/Global Tool Configuration
    }
    stages {
        stage("Build") {
            steps {
                sh "npm install"
                sh "npm run build"
            }
        }
    }
}
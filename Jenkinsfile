pipeline {
    agent any
    tools {
        nodejs "nodejs"  // Ensure this matches the name configured in Manage Jenkins/Global Tool Configuration
    }
    stages {
        stage("Build") {
            steps {
                powershell "npm install"
                powershell "npm run build"
            }
        }
    }
}
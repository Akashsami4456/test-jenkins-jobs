pipeline {
    agent any

    triggers {
        githubPush()  // Trigger the build for GitHub push events
    }

    stages {
        stage('Build') {
            steps {
                script {
                    // Add logic to handle PR events if required
                    if (env.GIT_BRANCH.contains("pull/")) {
                        // Handle PR-specific logic here
                        echo "This is a Pull Request"
                    }
                }
            }
        }
    }
}

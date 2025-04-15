// pipeline {
//     agent any

//     environment {
//         // Define environment variables here
//         APP_NAME = 'my-app'
//         DEPLOY_ENV = 'staging'
//     }

//     options {
//         // Keep only the last 10 builds
//         buildDiscarder(logRotator(numToKeepStr: '10'))
//         // Timestamps for logs
//         timestamps()
//     }

//     stages {
//         stage('Checkout') {
//             steps {
//                 // Checkout source code from SCM
//                 checkout scm
//             }
//         }

//         stage('Build') {
//             steps {
//                 echo "Building ${env.APP_NAME}..."
//                 // Example build command
//                 sh './build.sh'
//             }
//         }

//         stage('Test') {
//             steps {
//                 echo "Running tests for ${env.APP_NAME}..."
//                 // Example test command
//                 sh './run-tests.sh'
//                 // Archive test reports if any
//                 junit 'reports/**/*.xml'
//             }
//         }

//         stage('Deploy') {
//             when {
//                 branch 'main'
//             }
//             steps {
//                 echo "Deploying ${env.APP_NAME} to ${env.DEPLOY_ENV} environment..."
//                 // Example deploy command
//                 sh './deploy.sh'
//             }
//         }
//     }

//     post {
//         always {
//             echo 'Pipeline execution completed.'
//             // Archive artifacts if needed
//             archiveArtifacts artifacts: 'build/**/*.*', fingerprint: true
//         }
//         success {
//             echo 'Pipeline succeeded.'
//         }
//         failure {
//             echo 'Pipeline failed.'
//         }
//     }
// }



pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }
    }
}

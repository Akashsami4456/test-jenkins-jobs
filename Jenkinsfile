pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Hello Akash sami from Jenkins Test!'
            }
        }
    }
}

// pipeline {
//     agent any

//     triggers {
//         cron('H/2 * * * *') // Every 2 minutes
//     }

//     stages {
//         stage('Scheduled Build') {
//             steps {
//                 echo "Build triggered by cron at ${new Date()}"
//             }
//         }
//     }
// }


// pipeline {
//   agent any
//   triggers {
//     GenericTrigger(
//       genericVariables: [
//         [key: 'PR_ACTION', value: '$.action'],
//         [key: 'PR_NUMBER', value: '$.number'],
//         [key: 'PR_BRANCH', value: '$.pull_request.head.ref'],
//         [key: 'PR_BASE', value: '$.pull_request.base.ref']
//       ],
//       causeString: 'Triggered on PR: $PR_ACTION #$PR_NUMBER from $PR_BRANCH → $PR_BASE',
//       printContributedVariables: true,
//       printPostContent: true
//     )
//   }
//   stages {
//     stage('PR Event Triggered') {
//       steps {
//         echo "GitHub PR Action: ${env.PR_ACTION}"
//         echo "PR Number: ${env.PR_NUMBER}"
//         echo "Source Branch: ${env.PR_BRANCH}"
//         echo "Target Branch: ${env.PR_BASE}"
//       }
//     }
//   }
// }

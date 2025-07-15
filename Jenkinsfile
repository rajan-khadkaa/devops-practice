
//sh for linux -ubuntu
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello from Jenkins in Ubuntu!"'
                sh '''
                    echo "Multiline shell steps work too"
                    ls -lah
                '''
            }
        }
    }
}



//bat for windows
// pipeline {
//     agent any
//     stages {
//         stage('Build') {
//             steps {
//                 bat 'echo "Hello World"'
//                 bat '''
//                     echo "Multiline shell steps works too"
//                     dir
//                 '''
//             }
//         }
//     }
// }


// pipeline {
//     agent { docker { image 'node:22.17.0-alpine3.22' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'node --version'
//             }
//         }
//     }
// }
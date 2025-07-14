pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World"'
                bat '''
                    echo "Multiline shell steps works too"
                    dir
                '''
            }
        }
    }
}


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
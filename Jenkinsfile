@Library('sharedlibs') _
pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                welcome('shiva')
            }
            steps {
                script {
                    cal.add(2,3)
                }
            }
            steps {
                script {
                    cal.sub(2,3)
                }
            }
            steps {
                script {
                    cal.mul(2,3)
                }
            }
            steps {
                script {
                    cal.div(2,3)
                }
            }
        }
    }
}

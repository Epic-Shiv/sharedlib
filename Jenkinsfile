@Library('sharedlibs') _
pipeline {
    agent any

    stages {
        stage('Welcome') {
            steps {
                welcome('shiva')
                script {
                    cal.add(2,3)
                    cal.sub(2,3)
                    cal.mul(2,3)
                    cal.div(2,3)
                }
            }
        }
    }
}

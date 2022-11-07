pipeline {
    agent any
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                IFS=$'\n'
                for i in $(cat release.yml)
                do
                sed's(0\5\g) $i
                echo $i
                done
                    '''
                }
            }
        }
    }
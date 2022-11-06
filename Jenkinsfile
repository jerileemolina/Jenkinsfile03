pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                IFS=$'\n'
                for linea in $(cat release.yml)
                do
                lineauno="$(cut -d ":" -f1)"
                lineados="$(cut -d ":" -f2)"
                echo " El nombre es $lineauno y su version es $lineados"
                done
                    '''
                }
            }
        }
    }
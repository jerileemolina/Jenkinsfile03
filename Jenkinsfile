pipeline {
    agent any
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                IFS=$'\n'
                for i in $(cat release.yml)
                do
                echo "Y la versión de $(echo "$i" | cut -d ":" -f1) ahora es$(echo "$i" | cut -d ":" -f2 | sed's/5/10'g)"
                done
                    '''
                }
            }
        }
    }
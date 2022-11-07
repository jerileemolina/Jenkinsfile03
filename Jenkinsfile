pipeline {
    agent any
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                IFS=$'\n' 
                for i in $(cat release.yml)
                do 
                "La versión de $(echo "$i" | cut -d ":" -f1) es$(echo "$i" | cut -d ":" -f2) y ahora es $(echo "$i" | cut -d ":" -f2 | sed 's /5/10/g')" 
                done
                
                    '''
                }
            }
        }
    }
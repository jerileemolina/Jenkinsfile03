pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                while read linea;
                do
                lineauno=`echo $linea | cut -d ":" -f1 release.yml`
                lineados=`echo $linea | cut -d ":" -f2 release.yml`
                echo " El nombre es $lineauno y su version es $lineados"
                done
                    '''
                }
            }
        }
    }
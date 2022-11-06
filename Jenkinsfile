pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                while read -r linea;
                do
                lineauno=$(cut -d ":" -f1 release.yml)
                lineados=$(cut -d ":" -f2 release.yml)
                echo "El nombre es $lineauno y su version es $lineados"
                done
                    '''
                }
            }
        }
    }
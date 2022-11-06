pipeline {
    agent any
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                file=release.yml
                while read -r linea;
                do
                lineauno=$(echo $linea|awk -F ":" {'print $1})
                lineados=$(echo $linea|awk -F ":" {'print $2})
                echo "El nombre es $lineauno y su version es $lineados"
                done
                    '''
                }
            }
        }
    }
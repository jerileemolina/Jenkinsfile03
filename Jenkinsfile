pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                file=release.yml
                while read -r linea;
                do
                lineauno=$(echo${linea}|cut -d ":" -f1 file)
                lineados=$(echo${linea}|cut -d ":" -f2 file)
                echo "El nombre es $lineauno y su version es $lineados"
                done
                    '''
                }
            }
        }
    }
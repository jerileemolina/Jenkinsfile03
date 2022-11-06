pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                file=release.yml
                while IFS= read -r linea;
                do
                lineauno=$(echo${linea}|cut -d ":" -f1 file)
                lineados=$(echo${linea}|cut -d ":" -f2 file)
                echo "El nombre es $lineauno y su version es $lineados"
                // cambioversion=$(sed 's/5/10/g' file)
                // echo " La versión anterior de $lineauno era $lineados y ahora es $cambioversion"
                done
                    '''
                }
            }
        }
    }
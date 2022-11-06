pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                while read linea;
                do
                lineauno=`echo $lineauno | cut -d ":" -f1`
                lineados=`echo $lineados | cut -d ":" -f2`
                echo " El nombre es $lineauno y su version es $lineados"
                cambioversion=`echo $lineados | sed s/5/10/g` 
                echo " La versión anterior de $lineauno era $lineados y ahora es $cambioversion"                done
                    '''
                }
            }
        }
    }
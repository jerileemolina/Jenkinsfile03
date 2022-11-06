pipeline {
    agent any 
    stages {
        stage ('Ejercicio3') {
            steps {
                sh '''
                for variable in ('cat release.yml')
                do
                nombre_java=`echo $variable | cut -d ":" -f1`
                version_guardada=`echo $variable | cut -d ":" -f2`
                echo "$nombre_java es la version $version_guardada"
                done
                '''
                }
            }
        }
    }
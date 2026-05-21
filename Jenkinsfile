pipeline {
    agent any
    stages {
        stage('Descargar código') {
            steps {
                checkout scm
            }
        }
        stage('Validar PHP') {
            steps {
                echo "Validando sintaxis de ficheros PHP..."
                // Aquí iría el comando real de validación PHP
            }
        }
        stage('Desplegar en Apache') {
            steps {
                echo "Desplegando ficheros en el servidor web..."
                // Aquí iría el copiado de archivos y el reinicio de Apache
            }
        }
    }
}
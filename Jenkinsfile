pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Etapa Build: Compilando el código fuente...'
            }
        }
        stage('Test') {
            steps {
                echo 'Etapa Test: Ejecutando pruebas unitarias...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Etapa Deploy: Desplegando en el entorno de prueba...'
            }
        }
    }
}

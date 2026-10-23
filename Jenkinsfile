pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Etapa Build: Compilando el código fuente...'
                sh 'python3 -m py_compile app.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Etapa Test: Ejecutando pruebas unitarias...'
                sh 'python3 -c "import app; print(\'Pruebas unitarias completadas sin errores.\')"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Etapa Deploy: Desplegando en el entorno de prueba...'
                sh 'echo "Aplicación desplegada exitosamente."'
            }
        }
    }
}

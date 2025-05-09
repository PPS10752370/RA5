pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // Cada minuto, para pruebas. Sustituir por 'SCM webhooks' en real.
    }
    stages {
        stage('Instalar dependencias') {
            steps {
                sh 'pip install -r requirements.txt || true'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 -m unittest test_calculadora.py'
            }
        }
    }
}

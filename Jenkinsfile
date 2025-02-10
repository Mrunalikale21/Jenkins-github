pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/Mrunalikale21/Jenkins-github.git' // Replace with your actual repository
            }
        }
        stage('Compile C++ Program') {
            steps {
                sh 'g++ -o output main.cpp' // Compile the C++ program
            }
        }
        stage('Run Program') {
            steps {
                sh './output' // Run the compiled program
            }
        }
    }
}


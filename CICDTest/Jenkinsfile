/* Requer o plugin Docker Pipeline */
pipeline {
agent { docker { image 'maven:3.9.6-eclipse-temurin-21-alpine' } }
stages {
stage('build') {
steps {
sh 'mvn –version'
}
}
}
}
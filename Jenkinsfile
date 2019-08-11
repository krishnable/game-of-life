
pipeline {
agent any
stages {
stage('git') {
steps {
git 'https://github.com/krishnable/game-of-life.git'
}
}
stage('build') {
steps {
   sh 'mvn package'
}
}
}
}

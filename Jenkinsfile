
pipeline {
agent any
stages {
stage('git') {
steps {
git branch: 'Feature-A', url: 'https://github.com/krishnable/game-of-life.git'
}
}
stage('build') {
steps {
   sh 'mvn package'
}
}
}
}

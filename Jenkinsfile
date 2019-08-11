
pipeline {
agent any
     triggers {
        pollSCM 'H/10 * * * *'
    }
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

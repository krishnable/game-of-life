
pipeline {
agent any
stages {
stage('git') {
steps {
git branch: 'dev', url: 'https://github.com/krishnable/game-of-life.git'}
}
stage('build') {
steps {
   sh 'mvn package'
}
}
}
}

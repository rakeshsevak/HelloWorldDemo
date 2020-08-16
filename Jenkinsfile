pipeline {
agent any

stages {
stage('build') {
steps {
 echo 'building'
 mvn install
}
}
stage ('test') {
steps {
echo 'testing'
}
}
stage('deploy') {
steps {
echo 'deploying'
}
}
}
}

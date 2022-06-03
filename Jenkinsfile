pipeline {

agent any

stages {

stage('Build') {

steps {

bat "javac hello.java"
bat  'java -version'

}

}

stage('Run') {

steps {

bat "java hello"
}
}
}
}

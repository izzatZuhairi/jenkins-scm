pipeline {
    agent any

    stages {
        stage ("deploy"){
            steps {
                input message: "continue", ok: "yes"
            }
        }
        stage ("build") {
            steps {
                echo "building"
            }
        }
    }
}
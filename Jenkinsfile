pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
	stage('Git clone'){
	   steps{
		git url :"https://github.com/Leelavathy29/Maven-Proj.git", branch:"main"
	   }
	}
    }
}

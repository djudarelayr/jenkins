pipeline {
	agent any
	options {
		timeout(10)
		ansiColor('xterm')
	
	}
	environments {
		FOO=bar
	}
	stages {
		stage("hi") {
			steps {
				echo "hello"
			}
		}
	}
}

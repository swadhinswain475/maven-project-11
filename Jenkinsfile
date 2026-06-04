pipeline{
	tools{
		jdk 'JAVA_HOME'
		maven 'MAVEN_HOME'
	}
	agent any
	stages{
		stage("git checkout"){
			steps{
			git 'https://github.com/swadhinswain475/maven-project-11.git'
			}
		}
		
		stage("maven install"){
			steps{
			 sh 'mvn clean install'
			}
		}
	}
}

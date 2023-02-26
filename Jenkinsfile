pipeline {
	agent any
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '//home/khushi/Documents/apache-maven-3.8.7/bin/mvn install'
	                 }}
		stage('Deployment'){
		    steps {
			sh 'cp target/myntra.war home/khushi/Documents/GRRAS-MavenJenkins/apache-tomcat-9.0.70/webapps'
	}
}}}

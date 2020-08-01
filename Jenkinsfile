#!/usr/bin/env groovy
@Library(['deop.rautomates.jecda' ]) _ 

	def  paramap =  [ : ]
	paramap[ "ApplicationURL" ] = ApplicationURL
	paramap[ "ApplicationRevision" ] = ApplicationRevision
	
	pipeline {
	    agent { node { master }  }
	    stages {
	        stage ("Init") {
	        	script {
	        	    gitche(paramap)
	        	}
	         }
	    }
	}

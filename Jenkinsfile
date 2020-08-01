#!/usr/bin/env groovy
@Library('deop.rautomates.jecda.gitche') _ 

	def  paramap =  [ : ]
	paramap[ "ApplicationURL" ] = ApplicationURL
	paramap[ "ApplicationRevision" ] = ApplicationRevision

			stage ("Init") {
				script {
					gitche(paramap)
				}

			}

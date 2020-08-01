@Library('deop.rautomates.jecda')
node {
	def paramap [ : ]
	paramap[ "ApplicationURL" ] = ApplicationURL
	paramap[ "ApplicationRevision" ] = ApplicationRevision
	script {
		gitche(paramap)
	}
}


@Library('deop.rautomates.jecda')
pipeline {
    node {
    	def paramap [ : ]
		paramap[ "ApplicationURL" ] = ApplicationURL
		paramap[ "ApplicationRevision" ] = ApplicationRevision
		script {
			gitche(paramap)
		}
    }
}
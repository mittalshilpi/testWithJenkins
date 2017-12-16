#!groovy

//def_tag = (params.RELEASE_TAG != 'default' ) ? params.RELEASE_TAG : "

stage('Exec NPM') {
	ansiColor('xterm'){
		sh '''
			ls -al
			npm --verbose install
			ls -al
			'''
		}
	}
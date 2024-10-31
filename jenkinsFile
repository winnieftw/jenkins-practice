node {
	stage 'Checkout'
	checkout scm

	stage 'Build'
	sh 'javac helloWorld.java'

	stage 'Test'
	sh 'java HelloWorld | grep Hello'
}

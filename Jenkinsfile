node('master') {
    stage(' =~ Simple Pythonista =~ ') {
        helloWorld('python_pkgchecker')
    }
    stage(' =~ Pythonistas Garage =~ ') {
        buildUtils('jenkins-infra-stdlibs') 
    }
}

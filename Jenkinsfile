@Library('libpipelines') _

hose {
    EMAIL = 'cd'
    FREESTYLE_BRANCHING = true
    UPSTREAM_VERSION = '2.2.0'

    DEV = { config ->
        doCompile(config)
        doUT(config)
        doPackage(config)
        doStaticAnalysis(config)
        doDeploy(config)
	doDocker(config)
    }     
}

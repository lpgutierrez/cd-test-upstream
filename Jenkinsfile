@Library('libpipelines') _

hose {
    EMAIL = 'cd'
    FREESTYLE_BRANCHING = true
    UPSTREAM_VERSION = '1.0.0'
 // Random comment
    DEV = { config ->
        doCompile(config)
        doUT(config)
        doPackage(config)
        doStaticAnalysis(config)
        doDeploy(config)
	doDocker(config)
    }     
}

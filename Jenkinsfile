@Library('libpipelines') _

hose {
    EMAIL = 'cd'
    FREESTYLE_BRANCHING = true

    DEV = { config ->
        doCompile(config)
        doUT(config)
        doPackage(config)
        doStaticAnalysis(config)
        doDeploy(config)
	doDocker(config)
    }     
}

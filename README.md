	(IMP! - The below contents can be replaced with information about this repository once it has been made a note of!)


Great! You now have your basic GitHub repository set up!

Let me get you onboarded on a few necessary requirements!

As a part of the Compliance Check, the following Status Checks are to be set under:

Settings > Branches (under "Code and automation") > Edit ("main" Branch Protection Rule) > Enable "Require status checks to pass before merging" ("Require branches to be up to date before merging" can remain Disabled) > type in the following Status Checks based on the type of repository this is


	Service Repository -
 
		i. build-and-publish-deploy-image / build-and-publish-image
	
		ii. isolated-tests / isolated-tests
	
		iii. secrets-scanner / secret-scanner
	
		iv. integ-tests / deploy-services
	
		v. integ-tests / integ-tests
	
		vi. integ-tests / cleanup-and-release-integ
	
	
	Utility Repository -

		i. build-and-publish-deploy-image / build-and-publish-image
	
		ii. isolated-tests / isolated-tests
	
		iii. secrets-scanner / secret-scanner
	
	

NOTE:

Please refer to the following links for further information - 

1. Compliance Check -

    a. Workflow - https://github.com/compute-cloud/ops-workflows/actions/workflows/compliance_check.yaml
	
    b. Documentation - https://rndwiki-pro.its.hpecorp.net/display/ComputeCentral/Compliance+Check+for+Service+Repositories
	
2. Automated GitHub Repository Creation -

    a. Workflow - https://github.com/compute-cloud/ops-workflows/actions/workflows/auto_github_repo_creation.yaml
	
    b. Documentation - https://rndwiki-pro.its.hpecorp.net/display/ComputeCentral/Automated+GitHub+Repository+Creation
.PHONY: build

build:
	sam build

deploy-infra:
	sam build && aws-vault exec mandy --no-session -- sam deploy

deploy-site:
	aws-vault exec mandy --no-session -- aws s3 sync ./ResumeChallenge/frontend s3://cloudresumecv





	 
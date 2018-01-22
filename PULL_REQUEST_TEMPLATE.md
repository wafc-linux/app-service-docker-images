Review and check the following guidelines before submitting a PR.

	1. Create a new folder for a new docker image and include a version folder . Such as 
	+my-image
	         \  0.1 
		       \Dockerfile and other files 
		
	Note : If you are updating an existing image  , create a new version folder within your image folder.
	2. Include a README.md within version folder to describe :
		a. Any changes with deployment of use of the image 
		b. Include comments if the image is not backward compatible and how user can manually upgrade to new version 
	3. SSH support included in the docker image 
	4. Do no use VOLUME with the docker image since it is not supported 
	5. Use only ONE external port in addition to SSH port 2222
	6. For built in runtime images for PHP , NodeJS , .NET Core etc please submit a PR with a version number of the framework. Such as Version:7.1 or Version:7.1.4 in the commit message  
	7. For Custom images , please do not submit a version in the commit message so  that we can use a custom Guid for versioning purposes. 
	8. 
	
[] - Please check this box once you've submitted the PR if you've read through the Contribution Guide and best practices checklist.
[] - I certify that the Docker image was tested successfully at runtime using Web App for Containers or Linux Web App.

### Changelog
- Add your list of changes here 
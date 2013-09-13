aws-silverstripe-cookbooks
==========================

Chef cookbooks for deploying Silverstripe on AWS using AWS Opworks.
This cookbook is setup for the following stack configuration:

- PHP App Server containing Silverstripe application files
- Seperate MySQl db server as DB layer in Opworks

The current stack setup uses the default Silverstripe cms & frmework bundle supplied by the download .tar.gz file.
This cookbook will be updated to use composer to pull in the cms and framework repositories on the server, with the installer set up as the base repository in the AWS Opwroks stack

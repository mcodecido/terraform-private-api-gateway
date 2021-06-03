Accessing a private API Gateway using VPC Endpoints
This module creates an example of a privately accessible API Gateway and a VPC Endpoint and restrict access only through it.

Read the original article on Medium.

Requirements
No requirements.

Providers
Name	Version
aws	n/a
Inputs
Name	Description	Type	Default	Required
apigw_name	API Gateway Name	string	"some-api"	no
stage_name	API Gateway Stage Name	string	"test"	no
tags	Tags to add to resources	map(string)	{}	no
Outputs
Name	Description
apigw_url	API Gateway URL

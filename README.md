# AnsibleAssessment

#Description
This was created with Google Colab. It reads a markdown file containting meeting notes, parses it, and writes the formatted notes into a newly created google document on the authenticated user's drive.

This is based on the requirements from the Ansible Health assessment for the position - Fullstack Software Engineer

#Setup
Load the notebook into colab

Save the meeting notes into the colab instance at the root directory as: assessmentData.md

Enable google API, setup Branding, and authorize credentials (internal) for desktop applications according to this documentation: https://developers.google.com/workspace/docs/api/quickstart/python

#Dependencies
For the environment: 
  google-api-python-client 
  google-auth-httplib2
  google-auth-oauthlib

For the python commannds:
  re
  googleapiclient
  google.oauth2.credentials
  google.colab

#How to Run:
After setup is complete all you have to do is use the "Run All" button on the interface. Or you can use reset the runtime and runall if you'd like.
When the authentication command executes you will be prompted to log into your google account and grant access to your drive and cloud projects. Give it all access.
When the script finishes the new formatted meeting notes document will be in your google drive

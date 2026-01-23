# CSE 135 HW1 Submission

## Team Member
- Kevin William Peoples (PID: A17465911)

## Server Login for Grading
### Grader account credentials
- Username: grader
- Password: Kevin09

Tested by logging into the site using HTTP Basic Authentication in the browser and via curl.


IP address:138.68.236.246  
Droplet name: ubuntu-s-1vcpu-2gb-sfo2-01


### SSH Key
- Not used. Grading access is provided via HTTP Basic Authentication.


> I verified that I can successfully log in to the `grader` account before submission.

## Site Link
- https://kp-cse135.site/

## Site Contents
- Homepage with student information and homework links
- About page for the student
- favicon
- robots.txt
- hw1/hello.php
- hw1/report.html

## GitHub Auto Deploy Setup

- **Repository:** https://github.com/kepeoples/cse135-site
- **Deployment method:** GitHub Actions
- **Deployment trigger:** Pushes to the `main` branch automatically trigger a deployment to the server via GitHub Actions.

### Deployment Demonstration Video
- **Video link:** https://drive.google.com/drive/search?dmr=1&ec=wgc-drive-globalnav-goto&q=github-deploy

The video demonstrates making a code change, pushing it to GitHub, and the corresponding GitHub Actions workflow running and successfully deploying the update to the live site.

## Login Credentials for Website
- Username: grader
- Password: Kevin09

## Compression Verification Summary
HTTP compression was enabled on the server and verified using the browser DevTools Network tab.

- The response returned a `200 OK` status code
- The `Content-Encoding` response header was set to `gzip`
- The browser advertised support for compression via the `Accept-Encoding` request header
- Page content rendered correctly after compression, confirming no functional issues

## Server Header Removal Summary

The default web server header was removed and replaced with a custom value.

- The `Server` response header no longer exposes the underlying web server software
- The header was verified using the Network headers view in browser DevTools
- No server version or implementation details are leaked

## Extra Credit: Analytics (if applicable)
- <Brief description of analytics configuration and verification>

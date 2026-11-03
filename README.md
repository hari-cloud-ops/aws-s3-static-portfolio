# AWS S3 Static Portfolio

## Overview
A simple portfolio website hosted using Amazon S3 static website hosting.

## Live website
[Open my portfolio](http://hari-cloud-portfolio-077376431681-ap-southeast-2-an.s3-website-ap-southeast-2.amazonaws.com)

## Architecture
Browser → Amazon S3 static website endpoint

## AWS service used
- Amazon S3

## What I configured
- Enabled static website hosting.
- Uploaded `index.html` to the S3 bucket.
- Configured read-only public access for the website page.
- Tested the S3 website endpoint in a browser.

## Limitations and cost notes
The S3 website endpoint uses HTTP, not HTTPS. S3 storage, requests, and data transfer may incur charges. AWS credits may cover eligible usage, but they do not guarantee zero cost.

## Security
No AWS credentials, access keys, or private information are included in this project.

# AWS S3 Static Website

## Project Overview

This project demonstrates hosting a static website using Amazon S3 Static Website Hosting.

The website is stored in an Amazon S3 bucket and served as a static website through the S3 website endpoint.

## AWS Service Used

* Amazon S3

## Architecture

```text
Internet
   |
   v
Amazon S3
   |
   v
S3 Bucket
   |
   v
index.html
   |
   v
Static Website
```

## Configuration

The S3 bucket was configured for static website hosting with:

* Static Website Hosting: Enabled
* Index Document: `index.html`
* Public read access for website objects
* Bucket Policy allowing `s3:GetObject`

## Deployment Steps

1. Created an S3 bucket.
2. Uploaded `index.html`.
3. Enabled Static Website Hosting.
4. Configured public access.
5. Added a Bucket Policy for public read access.
6. Accessed the website using the S3 Website Endpoint.

## Skills Demonstrated

* Amazon S3
* Static Website Hosting
* S3 Bucket Configuration
* Bucket Policies
* AWS Permissions
* Basic Cloud Deployment

## Project Status

**S3 Static Website Deployment Successful**

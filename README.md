Amazon Web Services Bundle
==========================

Notice
======

This bundle is now officially maintained. Special thanks to Mark Badolato [`mbadolato`](https://github.com/mbadolato)

[![Latest Stable Version](https://poser.pugx.org/cybernox/amazon-webservices-bundle/v/stable.png)](https://packagist.org/packages/cybernox/amazon-webservices-bundle)
[![Total Downloads](https://poser.pugx.org/cybernox/amazon-webservices-bundle/downloads.png)](https://packagist.org/packages/cybernox/amazon-webservices-bundle)


Overview
--------
This is a Symfony2 Bundle for interfacing with Amazon Web Services (AWS).

This bundle uses the latest [AWS SDK for PHP](http://github.com/amazonwebservices/aws-sdk-for-php) by loading the SDK, and enabling you to instantiate the SDK's various web service objects, passing them back to you for direct use in your Symfony2 application..

For installation, configuration, and usage details, please see [`Resources/doc/README.md`](https://github.com/ThePhalcons/AmazonWebServicesBundle/blob/master/Resources/doc/README.md)

Changelog
---------
PR#15 submitted by @Fran6co requires a type chnage to the enable_extensions parameter in config.yml. See step 5b of [Resources/doc/README.md`](https://github.com/ThePhalcons/AmazonWebServicesBundle/blob/master/Resources/doc/README.md) for the new format.

Example Use Cases
-----------------
1. Connect to, and manipulate, any of the available Amazon Web Services, such as EC2, Amazon S3, SQS, SES, Amazon DynamoDB, Amazon Glacier, etc.

2. Utilize Amazon S3 and CloudFront as a Content Delivery Network (CDN) for a Symfony 2 application. Please see the information, graciously provided by [adurieux](https://github.com/adurieux), in [`Resources/doc/cdn.md`](https://github.com/ThePhalcons/AmazonWebServicesBundle/blob/master/Resources/doc/cdn.md).

3. Score dates with Supermodels (This feature not yet implemented)

License
-------

This bundle is under the MIT license. See the complete license in the bundle:

    Resources/meta/LICENSE
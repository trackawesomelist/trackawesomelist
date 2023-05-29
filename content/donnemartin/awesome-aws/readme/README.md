# Awesome Aws Overview

A curated list of awesome Amazon Web Services (AWS) libraries, open source repos, guides, blogs, and other resources.  Featuring the Fiery Meter of AWSome.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/donnemartin/awesome-aws/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung) · [😺 donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws) · ⭐ 12K · 🏷️ Platforms

[ [Daily](/content/donnemartin/awesome-aws/README.md) / [Weekly](/content/donnemartin/awesome-aws/week/README.md) / Overview ]

---

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/data-science-ipython-notebooks/master/images/aws.png">
</p>
<br/>

# Awesome AWS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome AWS libraries, open source repos, guides, blogs, and other resources.

Inspired by the [awesome (⭐254k)](https://github.com/sindresorhus/awesome) list.

## The Fiery Meter of AWSome

*   Repo with 0100+ Stars: :fire:
*   Repo with 0200+ Stars: :fire::fire:
*   Repo with 0500+ Stars: :fire::fire::fire:
*   Repo with 1000+ Stars: :fire::fire::fire::fire:
*   Repo with 2000+ Stars: :fire::fire::fire::fire::fire:

Repos not on `The Fiery Meter of AWSome` can still be awesome, see [A Note on Repo AWSomeness (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md#a-note-on-repo-awsomeness).

### `awesome-aws` Python Module

[![Build Status](https://travis-ci.org/donnemartin/awesome-aws.svg?branch=master)](https://travis-ci.org/donnemartin/awesome-aws) [![Codecov](https://img.shields.io/codecov/c/github/donnemartin/awesome-aws.svg)](https://codecov.io/github/donnemartin/awesome-aws) [![PyPI version](https://badge.fury.io/py/awesome-aws.svg)](http://badge.fury.io/py/awesome-aws)

The Python module [`awesome-aws`](https://github.com/donnemartin/awesome-aws/tree/master/awesome) regularly scans repos on [Awesome AWS (⭐12k)](https://github.com/donnemartin/awesome-aws) to maintain the accuracy of the `Fiery Meter of AWSome`.

## Contributing

Contributions are welcome!

Review the [Contributing Guidelines (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md).

Also check out the [Watch List (⭐12k)](https://github.com/donnemartin/awesome-aws/issues/34).

## Index

*   [SDKs and Samples](#sdks-and-samples)
    *   [Android](#android-sdk)
    *   [C++](#c-sdk)
    *   [Clojure](#clojure-sdk)
    *   [Go](#go-sdk)
    *   [iOS](#ios-sdk)
    *   [IoT](#iot-sdk)
    *   [Java](#java-sdk)
    *   [JavaScript](#javascript-sdk)
    *   [Haskell](#haskell-sdk)
    *   [Perl](#perl-sdk)
    *   [PHP](#php-sdk)
    *   [Python](#python-sdk)
    *   [Ruby](#ruby-sdk)
    *   [Rust](#rust-sdk)
    *   [Scala](#scala-sdk)
    *   [Xamarin](#xamarin-sdk)
    *   [Unity](#unity-sdk)
    *   [.NET](#net-sdk)
*   [Command Line Tools](#command-line-tools)
    *   [Universal Command Line Interface](#universal-command-line-interface)
    *   [Windows PowerShell](#windows-powershell)
*   [IDE Toolkits](#ide-toolkits)
    *   [Eclipse Toolkit](#eclipse-toolkit)
    *   [Visual Studio Toolkit](#visual-studio-toolkit)
*   [Open Source Repos](#open-source-repos)
    *   [API Gateway](#api-gateway)
    *   [CLI](#cli)
    *   [CloudFormation](#cloudformation)
    *   [CloudSearch](#cloudsearch)
    *   [CloudTrail](#cloudtrail)
    *   [CloudWatch](#cloudwatch)
    *   [Code Deploy](#code-deploy)
    *   [Code Pipeline](#code-pipeline)
    *   [Cognito](#cognito)
    *   [Data Pipeline](#data-pipeline)
    *   [Device Farm](#device-farm)
    *   [DynamoDB](#dynamodb)
    *   [Elastic Beanstalk](#elastic-beanstalk)
    *   [Elastic Container Service](#elastic-container-service)
    *   [Elastic File System](#elastic-file-system)
    *   [Elastic MapReduce](#elastic-mapreduce)
    *   [Elastic Search](#elastic-search)
    *   [Elasticache](#elasticache)
    *   [Glacier](#glacier)
    *   [Kinesis](#kinesis)
    *   [Lambda](#lambda)
    *   [Machine Learning](#machine-learning)
    *   [Mobile Analytics](#mobile-analytics)
    *   [OpsWorks](#opsworks)
    *   [Redshift](#redshift)
    *   [Route 53](#route-53)
    *   [S3](#s3)
    *   [SNS](#sns)
    *   [SQS](#sqs)
    *   [Data](#data)
    *   [DevOps](#devops)
    *   [Security](#security)
    *   [Accompanying](#accompanying-repos)
    *   [Miscellaneous](#miscellaneous-repos)
*   [Guides, Books, Documentation, and Training](#guides-books-documentation-and-training)
    *   [Getting Started Guides](#getting-started-guides)
    *   [General Guides](#general-guides)
    *   [Books](#books)
    *   [Whitepapers](#whitepapers)
    *   [Documentation](#documentation)
    *   [Training](#training)
    *   [Case Studies: Powered by AWS](#case-studies-powered-by-aws)
*   [Social](#social)
    *   [Blogs](#blogs)
    *   [Twitter Influencers](#twitter-influencers)
    *   [Facebook Pages](#facebook-pages)
    *   [YouTube Channels](#youtube-channels)
    *   [LinkedIn Groups](#linkedin-groups)
    *   [Subreddits](#subreddits)
    *   [Conferences](#conferences)
*   [Latest KPIs and Stats](#latest-kpis-and-stats)
*   [Appendix of Core Services](#appendix-of-core-services)
    *   [Services in Plain English](#services-in-plain-english)
    *   [Compute](#compute-services)
    *   [Networking](#networking-services)
    *   [Enterprise Applications](#enterprise-applications)
    *   [Analytics](#analytics-services)
    *   [Artificial Intelligence](#artificial-intelligence)
    *   [Management Tools](#management-tools)
    *   [Security and Identity](#security-and-identity-services)
    *   [Internet of Things](#internet-of-things-service)
    *   [Mobile Services](#mobile-services)
    *   [Storage and Content Delivery](#storage-and-content-delivery-services)
    *   [Databases](#databases)
    *   [Application Services](#application-services)
    *   [Developer Tools](#developer-tools)
    *   [Miscellaneous Services](#miscellaneous-services)
*   [Contributing](#contributing)
*   [Credits](#credits)
*   [Other Awesome Lists](#other-awesome-lists)
*   [Contact Info](#contact-info)
*   [License](#license)

## SDKs and Samples

*AWS and community SDKs with samples and docs, grouped by language.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/TK96G8T.png">
</p>
<br/>

### Android SDK

*   [Repo :fire::fire::fire: (⭐990)](https://github.com/aws/aws-sdk-android)
*   [Repo with Samples :fire::fire::fire: (⭐1k)](https://github.com/awslabs/aws-sdk-android-samples)
*   [Install](http://sdk-for-android.amazonwebservices.com/latest/aws-android-sdk.zip)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-android/)
*   [Learn More](https://aws.amazon.com/mobile/sdk/)

### C++ SDK

*   [Repo :fire::fire::fire::fire: (⭐1.7k)](https://github.com/awslabs/aws-sdk-cpp)
*   [Blog with Samples](https://aws.amazon.com/blogs/aws/introducing-the-aws-sdk-for-c/)

*The C++ SDK is a labs project with limited docs and/or samples.*

### Clojure SDK

*   [Repo :fire::fire::fire: (⭐995)](https://github.com/mcohen01/amazonica)
*   [Install (⭐995)](https://github.com/mcohen01/amazonica#installation)
*   [Docs (⭐995)](https://github.com/mcohen01/amazonica#documentation)

*The Clojure SDK is a community project with limited docs and/or samples.*)

### Go SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐8.3k)](https://github.com/aws/aws-sdk-go)
*   [Install (⭐8.3k)](https://github.com/aws/aws-sdk-go/wiki)
*   [Docs](http://docs.aws.amazon.com/sdk-for-go/api/)
*   [Learn More](https://aws.amazon.com/sdk-for-go/)

Related Repos:

*   [goamz/goamz :fire::fire: (⭐373)](https://github.com/goamz/goamz)

### iOS SDK

*   [Repo :fire::fire::fire::fire: (⭐1.6k)](https://github.com/aws/aws-sdk-ios)
*   [Repo with Samples :fire::fire::fire::fire: (⭐1k)](https://github.com/awslabs/aws-sdk-ios-samples)
*   [Install](http://sdk-for-ios.amazonwebservices.com/latest/aws-ios-sdk.zip)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-ios/)
*   [Learn More](https://aws.amazon.com/mobile/sdk/)

### IoT SDK

*   [Repo for Arduino (⭐90)](https://github.com/awslabs/aws-sdk-arduino)
*   [Repo for C :fire::fire::fire: (⭐885)](https://github.com/aws/aws-iot-device-sdk-embedded-C)
*   [Repo for JavaScript :fire::fire::fire: (⭐952)](https://github.com/aws/aws-iot-device-sdk-js)
*   [Repo for Arduino Yun :fire: (⭐162)](https://github.com/aws/aws-iot-device-sdk-arduino-yun/)
*   [Docs](http://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html)

*The IoT SDK is a labs project with limited docs and/or samples.*

### Java SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐4k)](https://github.com/aws/aws-sdk-java)
*   [Repo with Samples :fire::fire: (⭐218)](https://github.com/awslabs/aws-java-sample)
*   [Install](http://sdk-for-java.amazonwebservices.com/latest/aws-java-sdk.zip)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-java/)
*   [Learn More](https://aws.amazon.com/sdk-for-java/)

### JavaScript SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐7.4k)](https://github.com/aws/aws-sdk-js)
*   [Repo with Samples :fire::fire: (⭐300)](https://github.com/awslabs/aws-nodejs-sample)
*   [Install](http://docs.aws.amazon.com/AWSJavaScriptSDK/guide/node-intro.html)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-javascript/)
*   [Learn More](https://aws.amazon.com/sdk-for-node-js/)

Related Repos:

*   [aws/aws-amplify :fire::fire::fire::fire::fire: (⭐9.2k)](https://github.com/aws/aws-amplify)
*   [chilts/awssum :fire::fire: (⭐460)](https://github.com/chilts/awssum)
*   [mirkokiefer/aws-lib :fire::fire::fire: (⭐681)](https://github.com/mirkokiefer/aws-lib)
*   [SaltwaterC/aws2js :fire::fire: (⭐238)](https://github.com/SaltwaterC/aws2js)

### Haskell SDK

*   [Repo :fire::fire::fire: (⭐558)](https://github.com/brendanhay/amazonka)
*   [Docs](http://hackage.haskell.org/packages/#cat:AWS)

Related Repos:

*   [aristidb/aws :fire::fire: (⭐229)](https://github.com/aristidb/aws)

*The Haskell SDK is a community project with limited docs and/or samples.*

### Perl SDK

*   [Repo :fire: (⭐166)](https://github.com/pplu/aws-sdk-perl)
*   [Repo with Samples :fire: (⭐166)](https://github.com/pplu/aws-sdk-perl/tree/master/examples)
*   [Install (⭐166)](https://github.com/pplu/aws-sdk-perl#installation)
*   [Docs](https://metacpan.org/pod/Paws)
*   [Learn More](https://metacpan.org/pod/Paws)

*The Perl SDK is a community project.*

### PHP SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐5.8k)](https://github.com/aws/aws-sdk-php)
*   [Repo with Samples (⭐87)](https://github.com/awslabs/aws-php-sample)
*   [Install](http://docs.aws.amazon.com/aws-sdk-php/v3/guide/getting-started/installation.html)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-php/)
*   [Learn More](https://aws.amazon.com/sdk-for-php/)

Related Repos:

*   [aws-sdk-php-laravel :fire::fire::fire::fire: (⭐1.6k)](https://github.com/aws/aws-sdk-php-laravel)
*   [aws-sdk-php-silex (⭐81)](https://github.com/aws/aws-sdk-php-silex)
*   [aws-sdk-php-zf2 :fire: (⭐101)](https://github.com/aws/aws-sdk-php-zf2)

### Python SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐8.1k)](https://github.com/boto/boto3)
*   [Repo with Samples :fire: (⭐190)](https://github.com/awslabs/aws-python-sample)
*   [Install (⭐6.5k)](http://github.com/boto/boto#installation)
*   [Docs](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
*   [Learn More (⭐6.5k)](http://github.com/boto/boto/blob/develop/README.rst#boto)

Related Repos:

*   [boto3 :fire::fire::fire::fire::fire: (⭐8.1k)](https://github.com/boto/boto3)
*   [botocore :fire::fire::fire::fire: (⭐1.3k)](https://github.com/boto/botocore)

### Ruby SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐3.4k)](https://github.com/aws/aws-sdk-ruby)
*   [Repo with S3 Sample (⭐32)](https://github.com/awslabs/aws-ruby-sample)
*   [Install](http://docs.aws.amazon.com/sdk-for-ruby/v3/developer-guide/setup-install.html)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-ruby/)
*   [Samples :fire::fire::fire::fire::fire: (⭐7.6k)](https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/ruby/example_code/)

Related Repos:

*   [aws-sdk-rails :fire::fire::fire: (⭐542)](https://github.com/aws/aws-sdk-rails)
*   [appoxy/aws :fire::fire: (⭐233)](https://github.com/appoxy/aws)
*   [rightscale/right\_aws :fire::fire: (⭐452)](https://github.com/rightscale/right_aws)

### Rust SDK

*   [Repo :fire::fire::fire::fire::fire: (⭐2.6k)](https://github.com/rusoto/rusoto)
*   [Install (⭐2.6k)](https://github.com/rusoto/rusoto#installation)
*   [Docs](https://docs.rs/rusoto_core/)

*The Rust SDK is a community project with limited docs and/or samples.*

### Scala SDK

*   [Repo (⭐72)](https://github.com/awslabs/aws-scala-sdk)

Related Repos:

*   [atlassian/aws-scala](https://bitbucket.org/atlassian/aws-scala)
*   [seratch/AWScala :fire::fire::fire: (⭐741)](https://github.com/seratch/AWScala)

*The Scala SDK is a labs project with limited docs and/or samples.*

### Unity SDK

*   [Repo :fire: (⭐105)](https://github.com/aws/aws-sdk-unity)
*   [Repo with Samples :fire: (⭐159)](https://github.com/awslabs/aws-sdk-unity-samples)
*   [Install](https://s3.amazonaws.com/aws-unity-sdk/latest/aws-unity-sdk.zip)
*   [Docs](http://docs.aws.amazon.com/mobile/sdkforunity/developerguide/)

### Xamarin SDK

*   [Repo (⭐45)](https://github.com/awslabs/aws-sdk-xamarin)
*   [Blog with Samples](https://blog.xamarin.com/amazon-web-services-aws-mobile-sdks-for-xamarin-now-available/)

*The Xamarin SDK is a labs project with limited docs and/or samples.*

### .NET SDK

*   [Repo :fire::fire::fire::fire: (⭐1.9k)](https://github.com/aws/aws-sdk-net)
*   [Repo with Samples (⭐20)](https://github.com/awslabs/aws-auto-scaling-console-sample)
*   [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
*   [Docs](https://aws.amazon.com/documentation/sdk-for-net/)
*   [Learn More](https://aws.amazon.com/sdk-for-net/)
*   [Samples :fire: (⭐193)](https://github.com/awslabs/aws-sdk-net-samples)

## Command Line Tools

*AWS and community command line tools with samples and docs.*

<br/>
<p align="center">
  <img src="https://raw.githubusercontent.com/donnemartin/data-science-ipython-notebooks/master/images/commands.png">
</p>
<br/>

### Universal Command Line Interface

*   [Repo :fire::fire::fire::fire::fire: (⭐14k)](https://github.com/aws/aws-cli)
*   [Install](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-set-up.html)
*   [Docs](https://aws.amazon.com/documentation/cli/)
*   [Learn More](https://aws.amazon.com/cli/)

Related Repos:

*   [awslabs/aws-shell :fire::fire::fire::fire::fire: (⭐6.9k)](https://github.com/awslabs/aws-shell)
*   [donnemartin/saws :fire::fire::fire::fire::fire: (⭐5.1k)](https://github.com/donnemartin/saws)

### Windows PowerShell

*   [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
*   [Docs](https://aws.amazon.com/documentation/powershell/)
*   [Learn More](https://aws.amazon.com/powershell/)

## IDE Toolkits

*Official IDE toolkits with samples and docs.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/x4nu914.png">
</p>
<br/>

### Eclipse Toolkit

*   [Install](http://docs.aws.amazon.com/AWSToolkitEclipse/latest/ug/tke_setup.html)
*   [Docs](https://aws.amazon.com/documentation/awstoolkiteclipse/)
*   [Learn More](https://aws.amazon.com/eclipse/)

### Visual Studio Toolkit

*   [Install](http://sdk-for-net.amazonwebservices.com/latest/AWSToolsAndSDKForNet.msi)
*   [Docs](https://aws.amazon.com/documentation/aws-toolkit-visual-studio/)
*   [Learn More](https://aws.amazon.com/visualstudio/)

## Open Source Repos

*AWS and community open source projects, grouped by service.  See [A Note on Repo AWSomeness (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md#a-note-on-repo-awsomeness) for more details.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/wbhTgga.png">
</p>
<br/>

### API Gateway

AWS Repos:

*   [api-gateway-secure-pet-store :fire::fire: (⭐310)](https://github.com/awslabs/api-gateway-secure-pet-store) - Cognito credentials through Lambda.
*   [aws-apigateway-sdk-java (⭐30)](https://github.com/awslabs/aws-apigateway-sdk-java) - SDK for Java.
*   [aws-apigateway-swagger-importer :fire::fire::fire: (⭐517)](https://github.com/awslabs/aws-apigateway-importer) - Tools to work with Swagger.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### CLI

AWS Repos:

*   [awscli-aliases :fire::fire: (⭐435)](https://github.com/awslabs/awscli-aliases) - Repository for AWS CLI aliases.
*   [amazon-ecs-cli :fire::fire::fire::fire: (⭐1.7k)](https://github.com/aws/amazon-ecs-cli) - ECS CLI using the same Docker Compose file format and familiar Compose commands.
*   [aws-cli :fire::fire::fire::fire::fire: (⭐14k)](https://github.com/aws/aws-cli) - Universal Command Line Interface.
*   [aws-shell :fire::fire::fire::fire::fire: (⭐6.9k)](https://github.com/awslabs/aws-shell)
*   [awscli-cookbook (⭐38)](https://github.com/awslabs/awscli-cookbook) - Installs the CLI tools and provides a set of LWRPs for use within chef cookbooks.
*   [awsmobile-cli :fire: (⭐141)](https://github.com/aws/awsmobile-cli) - CLI experience for Frontend developers in the JavaScript ecosystem.

Community Repos:

*   [achiku/jungle :fire::fire::fire: (⭐844)](https://github.com/achiku/jungle) - Operations by EC2 and ELB cli should be simpler.
*   [dbcli/athenacli :fire: (⭐197)](https://github.com/dbcli/athenacli) - a CLI tool for AWS Athena service that can do auto-completion and syntax highlighting.
*   [donnemartin/saws :fire::fire::fire::fire::fire: (⭐5.1k)](https://github.com/donnemartin/saws) - A Supercharged AWS Command Line Interface.
*   [timkay/aws :fire::fire: (⭐407)](https://github.com/timkay/aws) - Easy command line access to Amazon EC2, S3, SQS, ELB, and SDB.
*   [wallix/awless :fire::fire::fire::fire::fire: (⭐4.9k)](https://github.com/wallix/awless) - a Powerful CLI for EC2, IAM and S3 in Go.
*   [99designs/aws-vault :fire::fire::fire::fire::fire: (⭐7.5k)](https://github.com/99designs/aws-vault) - A tool for securely storing AWS credentials, written in Go.

### CloudFormation

AWS Repos:

*   [aws-cdk :fire::fire::fire::fire::fire: (⭐10k)](https://github.com/aws/aws-cdk) - Framework for defining cloud infrastructure in code.
*   [aws-cfn-custom-resource-examples (⭐85)](https://github.com/awslabs/aws-cfn-custom-resource-examples) - Custom resource examples.
*   [aws-cfn-resource-bridge (⭐71)](https://github.com/aws/aws-cfn-resource-bridge) - Custom resource framework.
*   [cfn-python-lint :fire::fire::fire::fire::fire: (⭐2.2k)](https://github.com/awslabs/cfn-python-lint) - A tool for linting/validating CloudFormation.
*   [cfncluster-cookbook (⭐94)](https://github.com/awslabs/cfncluster-cookbook) - Sample Cookbook.
*   [cfncluster :fire::fire::fire: (⭐761)](https://github.com/awslabs/cfncluster) - Framework that deploys and maintains HPC clusters.

Community Repos:

*   [Appliscale/perun (⭐85)](https://github.com/Appliscale/perun) - A CLI tool for linting/validation and managing CloudFormation templates and stacks.
*   [bazaarvoice/cloudformation-ruby-dsl :fire::fire: (⭐206)](https://github.com/bazaarvoice/cloudformation-ruby-dsl) - Ruby DSL for creating templates.
*   [beaknit/cform :fire: (⭐103)](https://github.com/beaknit/cform) - SublimeText plugin.
*   [cloudreach/sceptre :fire::fire::fire::fire: (⭐1.4k)](https://github.com/cloudreach/sceptre) - A CLI tool for automating CloudFormation.
*   [cloudtools/troposphere :fire::fire::fire::fire::fire: (⭐4.8k)](https://github.com/cloudtools/troposphere) - Python library to create descriptions.
*   [peterkh/cumulus :fire::fire: (⭐205)](https://github.com/peterkh/cumulus) - Manages stacks.
*   [envato/stack\_master :fire::fire: (⭐283)](https://github.com/envato/stack_master) - A CLI tool to manage CloudFormation stacks.
*   [sparkleformation/sfn (⭐63)](https://github.com/sparkleformation/sfn) - CLI for stack management.
*   [sparkleformation/sparkle\_formation :fire::fire: (⭐221)](https://github.com/sparkleformation/sparkle_formation) - Ruby DSL for template creation.
*   [Stelligent/cfn\_nag :fire::fire::fire::fire: (⭐1.1k)](https://github.com/stelligent/cfn_nag) - Linting tool for CloudFormation templates

### CloudSearch

AWS Repos:

*   [cloudsearchable (⭐51)](https://github.com/awslabs/cloudsearchable) - An ActiveRecord-style ORM query interface.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### CloudTrail

AWS Repos:

*   [aws-cloudtrail-processing-library (⭐81)](https://github.com/aws/aws-cloudtrail-processing-library) - Easily consume and process log files.

Community Repos:

*   [AppliedTrust/traildash :fire::fire: (⭐363)](https://github.com/AppliedTrust/traildash) - Slick dashboard.
*   [GorillaStack/auto-tag :fire::fire: (⭐420)](https://github.com/GorillaStack/auto-tag) - Automatically tag AWS resources on creation, for cost assignment.

### CloudWatch

AWS Repos:

*   [cloudwatch-logs-subscription-consumer :fire::fire: (⭐397)](https://github.com/awslabs/cloudwatch-logs-subscription-consumer) - Kinesis stream reader.
*   [ecs-cloudwatch-logs (⭐69)](https://github.com/awslabs/ecs-cloudwatch-logs) - Assets in the blog post on using Amazon ECS and Amazon CloudWatch logs.
*   [logstash-output-cloudwatchlogs (⭐38)](https://github.com/awslabs/logstash-output-cloudwatchlogs) - A logstash plugin that sends logs to CloudWatch.
*   [opsworks-cloudwatch-logs-cookbooks (⭐8)](https://github.com/awslabs/opsworks-cloudwatch-logs-cookbooks) - OpsWorks sample cookbook.

Community Repos:

*   [jorgebastida/awslogs :fire::fire::fire::fire::fire: (⭐4.6k)](https://github.com/jorgebastida/awslogs) - Simple CLI for querying groups, streams and events.
*   [newrelic-platform/newrelic\_aws\_cloudwatch\_plugin :fire: (⭐156)](https://github.com/newrelic-platform/newrelic_aws_cloudwatch_plugin) - New Relic plugin.

### Code Deploy

AWS Repos:

*   [aws-codedeploy-agent :fire::fire: (⭐311)](https://github.com/aws/aws-codedeploy-agent) - Sample agent.
*   [aws-codedeploy-plugin :fire: (⭐153)](https://github.com/awslabs/aws-codedeploy-plugin) - Jenkins plugin.
*   [aws-codedeploy-samples :fire::fire::fire: (⭐620)](https://github.com/awslabs/aws-codedeploy-samples) - Samples and template scenarios.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Code Pipeline

AWS Repos:

*   [aws-codepipeline-custom-job-worker (⭐33)](https://github.com/awslabs/aws-codepipeline-custom-job-worker) - Develop your own job worker when creating a custom action.
*   [aws-codepipeline-jenkins-aws-codedeploy\_linux (⭐46)](https://github.com/awslabs/aws-codepipeline-jenkins-aws-codedeploy_linux) - Four-stage pipeline for Linux.
*   [aws-codepipeline-plugin-for-jenkins (⭐83)](https://github.com/awslabs/aws-codepipeline-plugin-for-jenkins) - Jenkins plugin.
*   [aws-codepipeline-s3-aws-codedeploy\_linux :fire: (⭐145)](https://github.com/awslabs/aws-codepipeline-s3-aws-codedeploy_linux) - Simple pipeline for Linux.
*   [AWSCodePipeline-Jenkins-AWSCodeDeploy\_Windows (⭐13)](https://github.com/awslabs/AWSCodePipeline-Jenkins-AWSCodeDeploy_Windows) - Four-stage pipeline for Windows.
*   [AWSCodePipeline-S3-AWSCodeDeploy\_Windows (⭐8)](https://github.com/awslabs/AWSCodePipeline-S3-AWSCodeDeploy_Windows) - Simple pipeline for Windows.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Cognito

AWS Repos:

*   [amazon-cognito-android (⭐31)](https://github.com/aws/amazon-cognito-android) - Sync SDK for Android.
*   [amazon-cognito-developer-authentication-sample (⭐98)](https://github.com/awslabs/amazon-cognito-developer-authentication-sample) - Authentication sample.
*   [amazon-cognito-dotnet (⭐9)](https://github.com/aws/amazon-cognito-dotnet) - Sync SDK for .NET.
*   [amazon-cognito-ios (⭐34)](https://github.com/aws/amazon-cognito-ios) - Sync SDK for iOS.
*   [amazon-cognito-js :fire::fire: (⭐203)](https://github.com/aws/amazon-cognito-js) - Sync SDK for JavaScript.
*   [amazon-cognito-streams-sample (⭐9)](https://github.com/awslabs/amazon-cognito-streams-sample) - Consuming Streams sample.
*   [cognito-sample-nodejs :fire: (⭐124)](https://github.com/awslabs/cognito-sample-nodejs) - Sample App for Node.js.

Community Repos:

*   [capeless/warrant :fire::fire: (⭐454)](https://github.com/capless/warrant) - Python library for using Cognito.
*   [rahulpsd18/cognito-backup-restore :fire: (⭐187)](https://github.com/rahulpsd18/cognito-backup-restore) - Tool for backing up and restoring Cognito user pools.

### Data Pipeline

AWS Repos:

*   [data-pipeline-samples :fire::fire: (⭐461)](https://github.com/awslabs/data-pipeline-samples) - Sample pipelines.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Device Farm

AWS Repos:

*   [aws-device-farm-appium-tests-for-sample-app (⭐87)](https://github.com/awslabs/aws-device-farm-appium-tests-for-sample-app) - Appium TestNG Android tests.
*   [aws-device-farm-calabash-tests-for-sample-app (⭐9)](https://github.com/awslabs/aws-device-farm-calabash-tests-for-sample-app) - Calabash Android tests.
*   [aws-device-farm-gradle-plugin (⭐59)](https://github.com/awslabs/aws-device-farm-gradle-plugin) - Gradle plugin.
*   [aws-device-farm-jenkins-plugin (⭐87)](https://github.com/awslabs/aws-device-farm-jenkins-plugin) - Jenkins plugin.
*   [aws-device-farm-sample-app-for-android :fire: (⭐164)](https://github.com/awslabs/aws-device-farm-sample-app-for-android) - Sample Android app.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### DynamoDB

AWS Repos:

*   [aws-dotnet-session-provider (⭐32)](https://github.com/aws/aws-dotnet-session-provider) - A session state provider for ASP.NET apps.
*   [aws-dotnet-trace-listener (⭐14)](https://github.com/aws/aws-dotnet-trace-listener) - A trace listener for System.Diagnostics that can be used to log events.
*   [aws-dynamodb-encryption-java :fire: (⭐134)](https://github.com/awslabs/aws-dynamodb-encryption-java) - Encryption Client for Java.
*   [aws-dynamodb-examples :fire::fire: (⭐479)](https://github.com/awslabs/aws-dynamodb-examples) - Samples using the Java SDK.
*   [aws-dynamodb-mars-json-demo (⭐50)](https://github.com/awslabs/aws-dynamodb-mars-json-demo) - Stores and indexes NASA JPL Mars images.
*   [aws-dynamodb-session-tomcat (⭐95)](https://github.com/aws/aws-dynamodb-session-tomcat) - Session store for Apache Tomcat.
*   [aws-sessionstore-dynamodb-ruby (⭐67)](https://github.com/aws/aws-sessionstore-dynamodb-ruby) - Handles sessions for Ruby web apps.
*   [dynamodb-cross-region-library :fire::fire: (⭐275)](https://github.com/awslabs/dynamodb-cross-region-library) - Cross-region replication.
*   [dynamodb-geo :fire::fire: (⭐272)](https://github.com/awslabs/dynamodb-geo) - Library to create and query geospatial data.
*   [dynamodb-import-export-tool (⭐91)](https://github.com/awslabs/dynamodb-import-export-tool) - Import and export examples.
*   [dynamodb-online-index-violation-detector (⭐9)](https://github.com/awslabs/dynamodb-online-index-violation-detector) - Finds violations on an online GSI's hash key and range key.
*   [dynamodb-streams-kinesis-adapter (⭐89)](https://github.com/awslabs/dynamodb-streams-kinesis-adapter) - Kinesis interface to consume and process data from a DynamoDB stream.
*   [dynamodb-tictactoe-example-app (⭐48)](https://github.com/awslabs/dynamodb-tictactoe-example-app) - Lightweight python app.
*   [dynamodb-titan-storage-backend :fire::fire: (⭐444)](https://github.com/awslabs/dynamodb-titan-storage-backend) - Storage Backend for Titan.
*   [dynamodb-transactions :fire::fire: (⭐352)](https://github.com/awslabs/dynamodb-transactions) - Performs atomic writes and isolated reads across multiple items and tables.
*   [logstash-input-dynamodb :fire: (⭐105)](https://github.com/awslabs/logstash-input-dynamodb) - Logstash input plugin.

Community Repos:

*   [channl/dynamodb-lambda-autoscale :fire::fire: (⭐312)](https://github.com/channl/dynamodb-lambda-autoscale) - Autoscale DynamoDB provisioned capacity using Lambda.
*   [lyft/confidant :fire::fire::fire::fire: (⭐1.8k)](https://github.com/lyft/confidant) - Stores secrets, encrypted at rest.
*   [sebdah/dynamic-dynamodb :fire::fire::fire: (⭐612)](https://github.com/sebdah/dynamic-dynamodb) - Provides auto-scaling.
*   [sensedeep/dynamodb-onetable :fire::fire::fire: (⭐568)](https://github.com/sensedeep/dynamodb-onetable) - DynamoDB library for single table designs using NodeJS.

### Elastic Beanstalk

AWS Repos:

*   [aws-eb-glassfish-dockerfiles (⭐32)](https://github.com/aws/aws-eb-glassfish-dockerfiles) - GlassFish docker files.
*   [aws-eb-python-dockerfiles (⭐58)](https://github.com/aws/aws-eb-python-dockerfiles) - Python docker files.
*   [eb-demo-php-simple-app :fire: (⭐142)](https://github.com/awslabs/eb-demo-php-simple-app) - Simple PHP app.
*   [eb-docker-multiple-ports (⭐56)](https://github.com/awslabs/eb-docker-multiple-ports) - Simple Node.js and Tomcat apps using Docker images.
*   [eb-docker-nginx-proxy :fire: (⭐141)](https://github.com/awslabs/eb-docker-nginx-proxy) - Simple PHP app using the PHP-FPM and Nginx Docker images.
*   [eb-docker-virtual-hosting (⭐29)](https://github.com/awslabs/eb-docker-virtual-hosting) - Simple PHP, Tomcat, and Nginx applications using Docker images.
*   [eb-node-express-sample :fire::fire: (⭐277)](https://github.com/awslabs/eb-node-express-sample) - Sample express app.
*   [eb-node-express-signup (⭐77)](https://github.com/awslabs/eb-node-express-signup) - Express framework and Bootstrap Node.js sample app.
*   [eb-node-express (⭐8)](https://github.com/awslabs/eb-node-express) - Sample app referenced in the Developer Guide.
*   [eb-py-flask-signup-worker (⭐45)](https://github.com/awslabs/eb-py-flask-signup-worker) - Python app that illustrates worker roles.
*   [eb-py-flask-signup :fire::fire: (⭐271)](https://github.com/awslabs/eb-py-flask-signup) - Python signup form app with Flask and Bootstrap.
*   [eb-python-flask (⭐37)](https://github.com/awslabs/eb-python-flask) - Simple Python and Flask app.
*   [eb-wif-sample (⭐18)](https://github.com/awslabs/eb-wif-sample) - Sample login app with Web Identity Federation.

Community Repos:

*   [alienfast/elastic-beanstalk :fire: (⭐194)](https://github.com/alienfast/elastic-beanstalk) - Gem with rake configuration and deployment for rails apps.
*   [ThoughtWorksStudios/eb\_deployer :fire::fire: (⭐400)](https://github.com/ThoughtWorksStudios/eb_deployer) - Blue-green deployment automation.

### Elastic Compute Cloud

AWS Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

Community Repos:

*   [alestic/ec2-consistent-snapshot :fire::fire: (⭐441)](https://github.com/alestic/ec2-consistent-snapshot) - Initiate consistent EBS snapshots in EC2.
*   [ConradIrwin/aws-name-server :fire::fire::fire: (⭐556)](https://github.com/ConradIrwin/aws-name-server) - DNS server that lets you look up instances by name.
*   [cristim/autospotting :fire::fire::fire::fire::fire: (⭐2.2k)](https://github.com/autospotting/autospotting) - Automatically rolling-replace on-demand EC2 instances in AutoScaling groups with compatible spot instances.
*   [evannuil/aws-snapshot-tool :fire::fire: (⭐211)](https://github.com/evannuil/aws-snapshot-tool) - Automates EBS snapshots and rotation.
*   [kelseyhightower/kubernetes-the-hard-way :fire::fire::fire::fire::fire: (⭐35k)](https://github.com/kelseyhightower/kubernetes-the-hard-way) - Bootstrap Kubernetes the hard way on EC2. No scripts.
*   [mirakui/ec2ssh :fire::fire: (⭐248)](https://github.com/mirakui/ec2ssh) - SSH config manager.
*   [openebs/openebs :fire::fire::fire::fire::fire: (⭐8.1k)](https://github.com/openebs/openebs) - Containerized block storage QoS SLAs, tiering and replica policies across AZs and environments, and predictable and scalable performance.
*   [skavanagh/EC2Box :fire::fire: (⭐422)](https://github.com/skavanagh/EC2Box) - A web-based SSH console to manage multiple instances simultaneously.
*   [wbailey/claws :fire: (⭐163)](https://github.com/wbailey/claws) - CLI-driven console with capistrano integration.

### Elastic Container Service

AWS Repos:

*   [amazon-ecs-agent :fire::fire::fire::fire: (⭐2k)](https://github.com/aws/amazon-ecs-agent) - Agent that runs on and starts containers.
*   [amazon-ecs-amazon-efs (⭐67)](https://github.com/awslabs/amazon-ecs-amazon-efs) - Persists Data from containers.
*   [amazon-ecs-init :fire: (⭐189)](https://github.com/aws/amazon-ecs-init) - RPM developed to support the Amazon ECS Container Agent.
*   [blox :fire::fire::fire: (⭐952)](https://github.com/blox/blox) - Open source tools for building custom schedulers on ECS.
*   [ecs-blue-green-deployment :fire::fire: (⭐443)](https://github.com/awslabs/ecs-blue-green-deployment) - Blue-green deployment on ECS.
*   [ecs-cloudwatch-logs (⭐69)](https://github.com/awslabs/ecs-cloudwatch-logs) - Assets from the blog using Amazon ECS and Amazon CloudWatch logs.
*   [ecs-demo-php-simple-app :fire: (⭐154)](https://github.com/awslabs/ecs-demo-php-simple-app) - Simple PHP app.
*   [ecs-mesos-scheduler-driver :fire: (⭐169)](https://github.com/awslabs/ecs-mesos-scheduler-driver) - Integrates Apache Mesos.
*   [ecs-refarch-continuous-deployment :fire::fire::fire: (⭐836)](https://github.com/awslabs/ecs-refarch-continuous-deployment) - Reference Architecture for continuous deployment to ECS using CodePipeline.
*   [ecs-task-kite (⭐61)](https://github.com/awslabs/ecs-task-kite) - Simple ambassador container for inter-task communication.
*   [lambda-ecs-worker-pattern :fire::fire: (⭐291)](https://github.com/awslabs/lambda-ecs-worker-pattern) - Extends Lambda using SQS and ECS.
*   [py-flask-signup-docker (⭐80)](https://github.com/awslabs/py-flask-signup-docker) - Python sample app.
*   [service-discovery-ecs-consul :fire: (⭐108)](https://github.com/awslabs/service-discovery-ecs-consul) - Assets from the blog Service Discovery via Consul with Amazon ECS.

Community Repos:

*   [Lumoslabs/broadside (⭐44)](https://github.com/lumoslabs/broadside) - Command line tool for deploying revisions of containerized applications.
*   [Stelligent/mu :fire::fire::fire: (⭐972)](https://github.com/stelligent/mu) - Command line tool to simplify ECS deployments via CodeBuild and CodePipeline.

### Elastic File System

AWS Repos:

*   [amazon-ecs-amazon-efs (⭐67)](https://github.com/awslabs/amazon-ecs-amazon-efs) - Persist data from ECS.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Elastic MapReduce

AWS Repos:

*   [emr-bootstrap-actions :fire::fire::fire: (⭐612)](https://github.com/awslabs/emr-bootstrap-actions) - Sample bootstrap actions.
*   [emr-sample-apps (⭐64)](https://github.com/awslabs/emr-sample-apps) - Sample apps.

Community Repos:

*   [Yelp/mrjob :fire::fire::fire::fire::fire: (⭐2.6k)](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or EMR.

### Elastic Search

AWS Repos:

*   [logstash-output-amazon\_es :fire::fire: (⭐376)](https://github.com/awslabs/logstash-output-amazon_es) - Logstash output plugin to sign and export events.
*   [opsworks-elasticsearch-cookbook (⭐36)](https://github.com/awslabs/opsworks-elasticsearch-cookbook) - OpsWorks Elasticsearch sample cookbook.

Community Repos:

*   [elastic/elasticsearch-cloud-aws :fire::fire::fire: (⭐580)](https://github.com/elastic/elasticsearch-cloud-aws) - Plugin for Elasticsearch.

### Elasticache

AWS Repos:

*   [aws-elasticache-cluster-client-libmemcached (⭐22)](https://github.com/awslabs/aws-elasticache-cluster-client-libmemcached) - Libmemcached library support.
*   [aws-elasticache-cluster-client-memcached-for-java (⭐83)](https://github.com/awslabs/aws-elasticache-cluster-client-memcached-for-java) - Client for Java.
*   [aws-elasticache-cluster-client-memcached-for-php (⭐58)](https://github.com/awslabs/aws-elasticache-cluster-client-memcached-for-php) - Enhanced PHP library connecting to ElastiCache.
*   [elasticache-cluster-config-net (⭐28)](https://github.com/awslabs/elasticache-cluster-config-net) - Config object for Enyim's MemcachedClient to enable auto discovery.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Glacier

Community Repos:

*   [vsespb/mt-aws-glacier :fire::fire::fire: (⭐535)](https://github.com/vsespb/mt-aws-glacier) - Perl Multithreaded Multipart sync to Glacier.

### Kinesis

AWS Repos:

*   [amazon-kinesis-aggregators :fire: (⭐150)](https://github.com/awslabs/amazon-kinesis-aggregators) - Provides a simple way to create real time aggregations.
*   [amazon-kinesis-client-net (⭐57)](https://github.com/awslabs/amazon-kinesis-client-net) - Client Library for .NET.
*   [amazon-kinesis-client-nodejs :fire::fire: (⭐287)](https://github.com/awslabs/amazon-kinesis-client-nodejs) - Client Library for Node.js.
*   [amazon-kinesis-client-python :fire::fire: (⭐351)](https://github.com/awslabs/amazon-kinesis-client-python) - Client Library for Python.
*   [amazon-kinesis-client-ruby :fire: (⭐144)](https://github.com/awslabs/amazon-kinesis-client-ruby) - Client Library for Ruby.
*   [amazon-kinesis-client :fire::fire::fire: (⭐612)](https://github.com/awslabs/amazon-kinesis-client) Client library for Amazon Kinesis.
*   [amazon-kinesis-connectors :fire::fire: (⭐328)](https://github.com/awslabs/amazon-kinesis-connectors) - Libary to integrate with other AWS and non-AWS services.
*   [amazon-kinesis-data-visualization-sample :fire: (⭐171)](https://github.com/awslabs/amazon-kinesis-data-visualization-sample) - Sample data visualization app.
*   [amazon-kinesis-learning (⭐105)](https://github.com/awslabs/amazon-kinesis-learning) - Learning Kinesis Development.
*   [amazon-kinesis-producer :fire::fire: (⭐376)](https://github.com/awslabs/amazon-kinesis-producer) - Producer Library.
*   [amazon-kinesis-scaling-utils :fire::fire: (⭐333)](https://github.com/awslabs/amazon-kinesis-scaling-utils) - Provides the ability to scale streams.
*   [aws-fluent-plugin-kinesis :fire::fire: (⭐290)](https://github.com/awslabs/aws-fluent-plugin-kinesis) - Fluent Plugin.
*   [dynamodb-streams-kinesis-adapter (⭐89)](https://github.com/awslabs/dynamodb-streams-kinesis-adapter) - DynamoDB Streams Adapter.
*   [kinesis-log4j-appender (⭐62)](https://github.com/awslabs/kinesis-log4j-appender) - Log4J Appender.
*   [kinesis-poster-worker (⭐69)](https://github.com/awslabs/kinesis-poster-worker) - Simple multi-threaded Python Poster and Worker.
*   [kinesis-storm-spout :fire: (⭐107)](https://github.com/awslabs/kinesis-storm-spout) - Spout for Storm.
*   [mqtt-kinesis-bridge (⭐40)](https://github.com/awslabs/mqtt-kinesis-bridge) - Simple MQTT bridge in Python.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Lambda

AWS Repos:

*   [amazon-elasticsearch-lambda-samples :fire::fire: (⭐394)](https://github.com/awslabs/amazon-elasticsearch-lambda-samples) - Data ingestion for Elasticsearch from S3 and Kinesis.
*   [awslabs/aws-sam-local :fire::fire::fire::fire::fire: (⭐6.3k)](https://github.com/awslabs/aws-sam-local) - CLI tool for local development and testing of Serverless applications.
*   [aws-lambda-go :fire::fire::fire::fire::fire: (⭐3.3k)](https://github.com/aws/aws-lambda-go) - Libraries, samples and tools to help Go developers develop Lambda functions.
*   [aws-lambda-java-libs :fire::fire: (⭐473)](https://github.com/aws/aws-lambda-java-libs) - Official mirror for interface definitions and helper classes.
*   [aws-lambda-redshift-loader :fire::fire::fire: (⭐593)](https://github.com/awslabs/aws-lambda-redshift-loader) - Redshift loader.
*   [chalice :fire::fire::fire::fire::fire: (⭐9.8k)](https://github.com/awslabs/chalice) - Python Serverless Microframework.
*   [create-thumbnails-lambda (⭐28)](https://github.com/awslabs/create-thumbnails-lambda) - Uses the grunt-aws-lambda plugin to help you develop and test.
*   [lambda-ecs-worker-pattern :fire::fire: (⭐291)](https://github.com/awslabs/lambda-ecs-worker-pattern) - Extends Lambda using SQS and ECS.
*   [lambda-refarch-fileprocessing :fire::fire: (⭐449)](https://github.com/awslabs/lambda-refarch-fileprocessing) - Reference Architecture for Real-time File Processing.
*   [lambda-refarch-iotbackend :fire::fire: (⭐254)](https://github.com/awslabs/lambda-refarch-iotbackend) - Reference Architecture for creating an IoT Backend.
*   [lambda-refarch-mobilebackend :fire::fire::fire: (⭐586)](https://github.com/awslabs/lambda-refarch-mobilebackend) - Reference Architecture for creating a Mobile Backend.
*   [lambda-refarch-webapp :fire::fire::fire::fire: (⭐1.5k)](https://github.com/awslabs/lambda-refarch-webapp) - Reference Architecture for creating a Web Application.

Community Repos:

*   [alestic/lambdash :fire::fire::fire: (⭐529)](https://github.com/alestic/lambdash) - Lambda shell - Run sh commands inside the Lambda environment.
*   [Alephbet/gimel :fire::fire: (⭐226)](https://github.com/Alephbet/gimel) - Run your own A/B testing backend using Lambda.
*   [apex/apex  (⭐27)](https://github.com/apex/apex) - Minimal AWS Lambda function manager with Go support.
*   [claudiajs/claudia :fire::fire::fire::fire::fire: (⭐3.8k)](https://github.com/claudiajs/claudia) - Deploy Node.js projects to Lambda and API Gateway easily.
*   [cloudnative/lambda-chat :fire::fire: (⭐388)](https://github.com/cloudnative/lambda-chat) - A chat application without servers.
*   [danilop/LambdAuth :fire::fire::fire::fire: (⭐1.4k)](https://github.com/danilop/LambdAuth) - Sample authentication service.
*   [eawsy/aws-lambda-go :fire::fire::fire: (⭐704)](https://github.com/eawsy/aws-lambda-go) - A fast and clean way to execute Go on Lambda.
*   [garnaat/kappa :fire::fire::fire: (⭐902)](https://github.com/garnaat/kappa) - Kappa is a CLI tool that makes it easier to deploy, update, and test functions for AWS Lambda.
*   [goadapp/goad :fire::fire::fire::fire: (⭐1.9k)](https://github.com/goadapp/goad) - Lambda powered, highly distributed, load testing tool.
*   [graphcool/chromeless :fire::fire::fire::fire::fire: (⭐13k)](https://github.com/graphcool/chromeless) - Automate Chrome through Lambda.
*   [grycap/scar :fire::fire::fire: (⭐587)](https://github.com/grycap/scar) - Transparently execute containers out of Docker images in AWS Lambda.
*   [jeremydaly/lambda-api :fire::fire::fire::fire: (⭐1.3k)](https://github.com/jeremydaly/lambda-api) - Lightweight web framework for your serverless applications.
*   [jimpick/lambda-comments :fire::fire::fire: (⭐623)](https://github.com/jimpick/lambda-comments) - Blog commenting system built with Lambda.
*   [jorgebastida/gordon :fire::fire::fire::fire::fire: (⭐2k)](https://github.com/jorgebastida/gordon) - λ Gordon is a tool to create, wire and deploy AWS Lambdas using CloudFormation.
*   [ks888/LambStatus :fire::fire::fire::fire: (⭐1.3k)](https://github.com/ks888/LambStatus) - A status page system inspired by StatusPage.io, built on AWS Lambda.
*   [kubek2k/lambdoku :fire::fire::fire: (⭐572)](https://github.com/kubek2k/lambdoku) - Heroku-like experience when using Lambda.
*   [lambci/lambci :fire::fire::fire::fire::fire: (⭐4k)](https://github.com/lambci/lambci) - A continuous integration system built on Lambda.
*   [littlstar/s3-lambda :fire::fire::fire::fire: (⭐1.1k)](https://github.com/littlstar/s3-lambda) - Lambda functions over S3 objects with concurrency control (each, map, reduce, filter).
*   [mentum/lambdaws :fire::fire::fire::fire: (⭐1.3k)](https://github.com/mentum/lambdaws) - Deploy, run and get results in a breeze.
*   [Miserlou/Zappa :fire::fire::fire::fire::fire: (⭐12k)](https://github.com/Miserlou/Zappa) - Serverless WSGI Python Web Apps with AWS Lambda + API Gateway.
*   [nficano/python-lambda :fire::fire::fire::fire: (⭐1.4k)](https://github.com/nficano/python-lambda) - A toolkit for developing and deploying serverless Python code in Lambda.
*   [serverless/serverless :fire::fire::fire::fire::fire: (⭐45k)](https://github.com/serverless/serverless) The Serverless Application Framework (formerly JAWS).
*   [Tim-B/grunt-aws-lambda :fire::fire: (⭐247)](https://github.com/Tim-B/grunt-aws-lambda) - Grunt plugin.
*   [trek10inc/aws-lambda-debugger :fire::fire: (⭐290)](https://github.com/trek10inc/aws-lambda-debugger) - Remote debugging tool for Lambda functions running on Node 6.10

### Machine Learning

AWS Repos:

*   [machine-learning-samples :fire::fire::fire: (⭐866)](https://github.com/awslabs/machine-learning-samples) - Sample apps.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Mobile Analytics

AWS Repos:

*   [aws-sdk-mobile-analytics-js (⭐80)](https://github.com/aws/aws-sdk-mobile-analytics-js) - JavaScript SDK.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### OpsWorks

AWS Repos:

*   [opsworks-attribute-customization (⭐4)](https://github.com/awslabs/opsworks-attribute-customization) - Attribute customization example.
*   [opsworks-capistrano (⭐9)](https://github.com/awslabs/opsworks-capistrano) - Capistrano with instances.
*   [opsworks-cloudwatch-logs-cookbooks (⭐8)](https://github.com/awslabs/opsworks-cloudwatch-logs-cookbooks) - CloudWatch sample cookbook.
*   [opsworks-cookbooks :fire::fire::fire::fire: (⭐1.1k)](https://github.com/aws/opsworks-cookbooks) - Chef Cookbooks.
*   [opsworks-demo-php-photo-share-app (⭐16)](https://github.com/awslabs/opsworks-demo-php-photo-share-app) - Simple PHP photo share app.
*   [opsworks-demo-php-simple-app (⭐45)](https://github.com/awslabs/opsworks-demo-php-simple-app) - Simple PHP app.
*   [opsworks-demo-rails-photo-share-app (⭐15)](https://github.com/awslabs/opsworks-demo-rails-photo-share-app) - A sample Rails app.
*   [opsworks-elasticsearch-cookbook (⭐36)](https://github.com/awslabs/opsworks-elasticsearch-cookbook) - Elasticsearch sample cookbook.
*   [opsworks-example-cookbooks :fire: (⭐99)](https://github.com/awslabs/opsworks-example-cookbooks) - Cookbooks used with the sample apps.
*   [opsworks-first-cookbook (⭐9)](https://github.com/awslabs/opsworks-first-cookbook) - Cookbook used to demonstrate simple recipes.
*   [opsworks-windows-demo- (⭐31)](https://github.com/awslabs/opsworks-windows-demo-nodejs) - A sample Node.JS app.
*   [opsworks-windows-demo-cookbooks (⭐9)](https://github.com/awslabs/opsworks-windows-demo-cookbooks) - Cookbooks for Windows.
*   [todo-sample-app-cookbooks (⭐5)](https://github.com/awslabs/todo-sample-app-cookbooks) - Custom cookbooks associated with the todo-sample-app.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### Redshift

AWS Repos:

*   [aws-lambda-redshift-loader :fire::fire::fire: (⭐593)](https://github.com/awslabs/aws-lambda-redshift-loader) - Lambda database loader.
*   [amazon-redshift-utils :fire::fire::fire::fire::fire: (⭐2.6k)](https://github.com/awslabs/amazon-redshift-utils) - Applies optimal Column Encoding to existing Tables.

Community Repos:

*   [Lumoslabs/aleph (⭐77)](https://github.com/lumoslabs/aleph) - A full featured web application for writing and running Redshift
    queries. Supports revision tracking of queries and has basic visualization support.
*   [getredash/redash :fire::fire::fire::fire::fire: (⭐23k)](https://github.com/getredash/redash/) - A web application that allows to easily query an existing database, share the dataset and visualize it in different ways. Initially was developed to work with Redshift, and has great support for it.
*   [everythingMe/redshift\_console (⭐92)](https://github.com/EverythingMe/redshift_console) -  A simple tool to monitor and manage a Redshift cluster. The first release has basic tools to monitor running queries, WLM queue and your tables/schemas.

### Route 53

AWS Repos:

*   [route53-infima :fire::fire: (⭐326)](https://github.com/awslabs/route53-infima) - Manages service-level fault isolation.

Community Repos:

*   [barnybug/cli53 :fire::fire::fire::fire: (⭐1.9k)](https://github.com/barnybug/cli53) - cli53 is a command line tool for Amazon Route 53 which provides import and export from BIND format and simple command line management of Route 53 domains.
*   [winebarrel/roadworker :fire::fire: (⭐315)](https://github.com/winebarrel/roadworker) - Roadworker is a tool to manage Route53. It defines the state of Route53 using DSL, and updates Route53 according to DSL.

### S3

Community Repos:

*   [anomalizer/ngx\_aws\_auth :fire::fire: (⭐455)](https://github.com/anomalizer/ngx_aws_auth) - Implements proxying of authenticated requests.
*   [bloomreach/s4cmd :fire::fire::fire::fire: (⭐1.3k)](https://github.com/bloomreach/s4cmd) - S3 command line tool, faster than S3cmd for large files.
*   [CulturalMe/meteor-slingshot :fire::fire::fire: (⭐592)](https://github.com/CulturalMe/meteor-slingshot) - Upload files in meteor.
*   [danilop/yas3fs :fire::fire::fire: (⭐639)](https://github.com/danilop/yas3fs) - Yet Another S3-backed File System, inspired by s3fs.
*   [grippy/node-s3 (⭐96)](https://github.com/grippy/node-s3) - Node.js app to manage buckets.
*   [jubos/fake-s3 :fire::fire::fire::fire::fire: (⭐2.9k)](https://github.com/jubos/fake-s3) - Lightweight S3 clone that simulates most commands.
*   [kahing/goofys :fire::fire::fire::fire::fire: (⭐4.7k)](https://github.com/kahing/goofys) -  a Filey System for Amazon S3 written in Go.
*   [littlstar/s3renity :fire::fire::fire::fire: (⭐1.1k)](https://github.com/littlstar/s3renity) - Batch functions with concurrency control (each, map, reduce, filter, join)
*   [marcel/aws-s3 :fire::fire::fire: (⭐782)](https://github.com/marcel/aws-s3) - Ruby implementation of Amazon's S3 REST API.
*   [mardix/flask-cloudy :fire::fire: (⭐239)](https://github.com/mardix/flask-cloudy) - Flask extension.
*   [MathieuLoutre/grunt-aws-s3 :fire::fire: (⭐294)](https://github.com/MathieuLoutre/grunt-aws-s3) - Grunt plugin.
*   [mickael-kerjean/filestash :fire::fire::fire::fire::fire: (⭐7.9k)](https://github.com/mickael-kerjean/filestash) - A modern web client for S3.
*   [minio/mc :fire::fire::fire::fire::fire: (⭐2.5k)](https://github.com/minio/mc) -  Minio Client for filesystem and cloud storage.
*   [minio/minio :fire::fire::fire::fire::fire: (⭐39k)](https://github.com/minio/minio) - Object storage server compatible with S3.
*   [mumrah/s3-multipart :fire: (⭐162)](https://github.com/mumrah/s3-multipart) - Parallel upload/download to S3 via Python.
*   [ncw/rclone :fire::fire::fire::fire::fire: (⭐38k)](https://github.com/ncw/rclone) - Rsync for various cloud storage providers such as S3.
*   [owocki/s3\_disk\_util :fire: (⭐169)](https://github.com/owocki/s3_disk_util) - S3 Disk usage (du) utility.
*   [peak/s5cmd :fire::fire::fire: (⭐1.7k)](https://github.com/peak/s5cmd) - Fast S3 and local filesystem execution tool with wildcard and batch command support.
*   [pgherveou/gulp-awspublish :fire::fire: (⭐397)](https://github.com/pgherveou/gulp-awspublish) - Gulp plugin.
*   [rlmcpherson/s3gof3r :fire::fire::fire::fire: (⭐1.1k)](https://github.com/rlmcpherson/s3gof3r) - Fast, concurrent, streaming access, includes a CLI.
*   [s3git/s3git :fire::fire::fire::fire: (⭐1.4k)](https://github.com/s3git/s3git) - CLI tool that allows you to create a distributed, decentralized and versioned repository.
*   [s3fs-fuse/s3fs-fuse :fire::fire::fire::fire::fire: (⭐7.2k)](https://github.com/s3fs-fuse/s3fs-fuse) - Allows Linux and Mac OS X to mount an S3 bucket via FUSE.
*   [s3tools/s3cmd :fire::fire::fire::fire::fire: (⭐4.2k)](https://github.com/s3tools/s3cmd) - CLI for managing S3 and CloudFront.
*   [schickling/git-s3 :fire::fire: (⭐229)](https://github.com/schickling/git-s3) - Deploy your git repo to a bucket.
*   [sorentwo/carrierwave-aws :fire::fire: (⭐405)](https://github.com/sorentwo/carrierwave-aws) - Adapter for CarrierWave.
*   [spring-projects/aws-maven :fire::fire: (⭐215)](https://github.com/spring-projects/aws-maven) -  Maven Wagon for S3.
*   [tongwang/s3fs-c :fire: (⭐132)](https://github.com/tongwang/s3fs-c) - Mounts buckets for use on a local file system.
*   [mishudark/s3-parallel-put :fire::fire: (⭐306)](https://github.com/mishudark/s3-parallel-put) - CLI that supports parallel uploads.
*   [waynehoover/s3\_direct\_upload :fire::fire::fire: (⭐651)](https://github.com/waynehoover/s3_direct_upload) - Direct Upload to Amazon S3 With CORS
*   [weavejester/clj-aws-s3 :fire: (⭐199)](https://github.com/weavejester/clj-aws-s3) - Client library for Clojure.

### SES

Community Repos:

*   [drewblas/aws-ses :fire::fire::fire: (⭐549)](https://github.com/drewblas/aws-ses) - Provides an easy ruby DSL & interface.
*   [microapps/MoonMail :fire::fire::fire::fire: (⭐1.9k)](https://github.com/microapps/MoonMail) - Shoot billions of emails using SES and Lambda.

### Simple Workflow

AWS Repos:

*   [aws-flow-ruby :fire: (⭐139)](https://github.com/aws/aws-flow-ruby) - Creates background jobs and multistep workflows.
*   [aws-flow-ruby-samples (⭐66)](https://github.com/awslabs/aws-flow-ruby-samples) - AWS Flow Framework for Ruby samples.
*   [aws-flow-ruby-opsworks-helloworld (⭐6)](https://github.com/awslabs/aws-flow-ruby-opsworks-helloworld) - Hello World sample.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### SimpleDB

Community Repos:

*   [rjrodger/simpledb :fire: (⭐136)](https://github.com/rjrodger/simpledb) - Node.js library.

### SNS

AWS Repos:

*   [aws-php-sns-message-validator :fire: (⭐198)](https://github.com/aws/aws-php-sns-message-validator) - Message validation for PHP.

Community Repos:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### SQS

AWS Repos:

*   [amazon-sqs-java-messaging-lib :fire: (⭐150)](https://github.com/awslabs/amazon-sqs-java-messaging-lib) - Holds the Java Message Service to communicate with SQS.

Community Repos:

*   [phstc/shoryuken :fire::fire::fire::fire: (⭐2k)](https://github.com/phstc/shoryuken) - A super efficient SQS thread based message processor for Ruby.

### Data

AWS Repos:

*   [aws-data-wrangler :fire::fire::fire::fire::fire: (⭐3.5k)](https://github.com/awslabs/aws-data-wrangler) - Connects Pandas DataFrames and AWS data related services.

Community Repos:

*   [donnemartin/data-science-ipython-notebooks :fire::fire::fire::fire::fire: (⭐25k)](https://github.com/donnemartin/data-science-ipython-notebooks) - Big data/data science notebooks.
*   [everpeace/vagrant-mesos :fire::fire: (⭐437)](https://github.com/everpeace/vagrant-mesos) - Spin up your Mesos Cluster with Vagrant.
*   [jhorey/ferry :fire::fire: (⭐252)](https://github.com/jhorey/ferry) -  Define, run, and deploy big data apps using Docker.
*   [nathanmarz/storm-deploy :fire::fire::fire: (⭐516)](https://github.com/nathanmarz/storm-deploy) - One click deploy for Storm clusters.

### DevOps

Community Repos:

*   [cloud-custodian/cloud-custodian :fire::fire::fire::fire::fire: (⭐4.8k)](https://github.com/cloud-custodian/cloud-custodian) - Rules engine for management, DSL in yaml for query, filter, and actions on resources.
*   [chef-cookbooks/aws :fire::fire: (⭐556)](https://github.com/chef-cookbooks/aws) - Development repository for aws Chef cookbook.
*   [colinbjohnson/aws-missing-tools :fire::fire::fire::fire: (⭐1.3k)](https://github.com/colinbjohnson/aws-missing-tools) - Tools for managing resources including EC2, EBS, RDS and Route53.
*   [k1LoW/awspec :fire::fire::fire::fire: (⭐1.2k)](https://github.com/k1LoW/awspec) - RSpec tests your resources.
*   [mitchellh/vagrant-aws :fire::fire::fire::fire::fire: (⭐2.6k)](https://github.com/mitchellh/vagrant-aws) - Use Vagrant to manage your EC2 and VPC instances.
*   [NixOS/nixops :fire::fire::fire::fire: (⭐1.3k)](https://github.com/NixOS/nixops) - Use NixOS to provision EC2 instances, S3 buckets, and other resources.

### Security

AWS Repos:

*   [aws-sha256-agentcs (⭐6)](https://github.com/awslabs/aws-sha256-agentcs) - SHA256 Agent Compatibility Ccanner.
*   [aws-tvm-anonymous (⭐33)](https://github.com/awslabs/aws-tvm-anonymous) - Token Vending Machine for Anonymous Registration.
*   [aws-tvm-identity (⭐38)](https://github.com/awslabs/aws-tvm-identity) - Token Vending Machine for Identity Registration.
*   [s2n :fire::fire::fire::fire::fire: (⭐4.3k)](https://github.com/awslabs/s2n) - An implementation of the TLS/SSL protocols.

Community Repos:

*   [AdRoll/hologram :fire::fire::fire: (⭐783)](https://github.com/AdRoll/hologram) - Easy, painless credentials on developer laptops.
*   [alex/letsencrypt-aws :fire::fire::fire: (⭐729)](https://github.com/alex/letsencrypt-aws) - Automatically provision and update certificates.
*   [bridgecrewio/checkov :fire::fire::fire::fire::fire: (⭐5.6k)](https://github.com/bridgecrewio/checkov) - Terraform static analysis, verifies security best practices.
*   [cloudsploit/scans :fire::fire::fire::fire: (⭐2.6k)](https://github.com/cloudsploit/scans) - Detects security risks.
*   [iSECPartners/Scout2 :fire::fire::fire::fire: (⭐1.7k)](https://github.com/iSECPartners/Scout2) - Security auditing tool.
*   [jordanpotti/AWSBucketDump :fire::fire::fire::fire: (⭐1.2k)](https://github.com/jordanpotti/AWSBucketDump) - Security Tool to Look For Interesting Files in S3 Buckets.
*   [Netflix/bless :fire::fire::fire::fire::fire: (⭐2.7k)](https://github.com/Netflix/bless) - SSH Certificate Authority that runs as a Lambda function.
*   [Netflix/security\_monkey :fire::fire::fire::fire::fire: (⭐4.3k)](https://github.com/Netflix/security_monkey) - Monitors policy changes and alerts on insecure configurations.
*   [RiotGames/cloud-inquisitor :fire::fire: (⭐452)](https://github.com/RiotGames/cloud-inquisitor) - Tool to enforce ownership and data security.
*   [salesforce/policy\_sentry :fire::fire::fire::fire: (⭐1.8k)](https://github.com/salesforce/policy_sentry/) - IAM Least Privilege Policy Generator.
*   [sebsto/AWSVPN :fire: (⭐180)](https://github.com/sebsto/AWSVPN) - Start a private VPN server in the cloud.
*   [trailofbits/algo :fire::fire::fire::fire::fire: (⭐27k)](https://github.com/trailofbits/algo) - Set up a personal IPSEC VPN on EC2 and other cloud services.
*   [ttlequals0/autovpn :fire::fire::fire::fire: (⭐2k)](https://github.com/ttlequals0/autovpn) - Create On Demand Disposable OpenVPN Endpoints.

### Accompanying Repos

AWS Repos:

*Repos Accompanying Blogs, Training Events, and Conferences.*

*   [aws-arch-backoff-simulator :fire: (⭐221)](https://github.com/awslabs/aws-arch-backoff-simulator) - Jitter and backoff Simulator for AWS architecture blog.
*   [aws-big-data-blog :fire::fire::fire: (⭐894)](https://github.com/awslabs/aws-big-data-blog) - Samples from the AWS Big Data Blog.
*   [aws-demo-php-simple-app (⭐12)](https://github.com/awslabs/aws-demo-php-simple-app) - PHP apps from the AWS Blogs.
*   [aws-mobile-sample-wif (⭐3)](https://github.com/awslabs/aws-mobile-sample-wif) - Samples from the AWS Mobile SDK blog.
*   [aws-mobile-self-paced-labs-samples (⭐15)](https://github.com/awslabs/aws-mobile-self-paced-labs-samples) - Android Snake Game from a self-paced lab.
*   [aws-quickstart](https://github.com/aws-quickstart/) - Official repository for AWS Quick Start.
*   [aws-spot-labs :fire::fire::fire: (⭐888)](https://github.com/awslabs/aws-spot-labs) - Best practices using AWS Spot Instances.
*   [aws-training-demo :fire: (⭐128)](https://github.com/awslabs/aws-training-demo) - Demos from the Technical Trainers community.
*   [java-meme-generator-sample (⭐54)](https://github.com/awslabs/java-meme-generator-sample) - Meme generation app from re:Invent 2012.
*   [railsconf2013-tech-demo :fire: (⭐167)](https://github.com/awslabs/railsconf2013-tech-demo) - Seahorse demo from RailsConf 2013.
*   [reinvent2013-js-blog-demo (⭐30)](https://github.com/awslabs/reinvent2013-js-blog-demo) - Demo blogging app from re:Invent 2013.
*   [reinvent2013-mobile-photo-share (⭐23)](https://github.com/awslabs/reinvent2013-mobile-photo-share) - Mobile photo share app from re:Invent 2014.
*   [reinvent2014-scalable-site-management (⭐54)](https://github.com/awslabs/reinvent2014-scalable-site-management) - Scalable site management sample from re:Invent 2014.
*   [reinvent2015-dev309 (⭐7)](https://github.com/awslabs/reinvent2015-dev309) - Large Scale Metrics Analysis from re:Invent 2015.
*   [timely-security-analytics (⭐28)](https://github.com/awslabs/timely-security-analytics) - Security analytics sample from 2015 re:Invent 2015.
*   [todo-sample-app (⭐27)](https://github.com/awslabs/todo-sample-app) - Simple "Todo" app from RailsConf 2014.

Community Repos:

*   [startup-class/setup :fire::fire: (⭐296)](https://github.com/startup-class/setup) -  EC2 setup files for Startup Engineering MOOC.

### Miscellaneous Repos

AWS Repos:

*   [amediamanager (⭐62)](https://github.com/awslabs/amediamanager) - Media manager.
*   [aws-hal-client-java (⭐15)](https://github.com/awslabs/aws-hal-client-java) - Java client for the Hypertext Application Language.
*   [aws-model-validators (⭐9)](https://github.com/awslabs/aws-model-validators) - Tools for validating the AWS service JSON model files.
*   [aws-sdk-js-sample-video-transcoder (⭐22)](https://github.com/awslabs/aws-sdk-js-sample-video-transcoder) - Sample cross-platform video transcoder app.
*   [simplebeerservice :fire::fire: (⭐317)](https://github.com/awslabs/simplebeerservice) - Cloud-connected kegerator that streams live sensor data to AWS.

Community Repos:

*   [bcoe/thumbd :fire::fire: (⭐442)](https://github.com/bcoe/thumbd) - Node.js/ImageMagick-based image thumbnailing service.
*   [cdkpatterns/serverless :fire::fire::fire::fire: (⭐2.1k)](https://github.com/cdk-patterns/serverless) - Deployable serverless architecture patterns built in AWS CDK.
*   [Comcast/cmb :fire::fire: (⭐279)](https://github.com/Comcast/cmb) - Highly available, horizontally scalable queuing and notification service.
*   [convox/rack :fire::fire::fire::fire: (⭐1.9k)](https://github.com/convox/rack) - Open-source PaaS on AWS.
*   [devops-israel/aws-inventory :fire::fire: (⭐386)](https://github.com/devops-israel/aws-inventory) - Display all your AWS resources on a single web page.
*   [donnemartin/dev-setup :fire::fire::fire::fire: (⭐5.9k)](https://github.com/donnemartin/dev-setup) - Mac setup of various developer tools and AWS services.
*   [dtan4/terraforming :fire::fire::fire::fire::fire: (⭐4.3k)](https://github.com/dtan4/terraforming) - Export existing resources to Terraform style (tf, tfstate).
*   [segmentio/stack :fire::fire::fire::fire::fire: (⭐2.1k)](https://github.com/segmentio/stack) - A set of Terraform modules for configuring production infrastructure.
*   [j2labs/microarmy  (⭐0)](https://github.com/j2labs/microarmy) - Deploy micro instances to launch a coordinated siege.
*   [jpillora/grunt-aws :fire: (⭐174)](https://github.com/jpillora/grunt-aws) - Grunt interface into the Node.JS SDK.
*   [jvehent/haproxy-aws :fire::fire: (⭐279)](https://github.com/jvehent/haproxy-aws) - Documentation on building a HTTPS stack with HAProxy.
*   [localstack/localstack :fire::fire::fire::fire::fire: (⭐47k)](https://github.com/localstack/localstack) - A fully functional local AWS cloud stack. Develop and test your cloud apps offline!
*   [meducation/propono :fire::fire: (⭐316)](https://github.com/meducation/propono) - Easy-to-use pub/sub in Ruby.
*   [mozilla/awsbox :fire::fire::fire: (⭐812)](https://github.com/mozilla/awsbox) - A featherweight PaaS on top of EC2 for deploying node apps.
*   [Netflix/aminator :fire::fire::fire: (⭐936)](https://github.com/Netflix/aminator) - A tool for creating EBS AMIs.
*   [Netflix/archaius :fire::fire::fire::fire::fire: (⭐2.4k)](https://github.com/Netflix/archaius) - Library for configuration management API.
*   [Netflix/asgard :fire::fire::fire::fire::fire: (⭐2.2k)](https://github.com/Netflix/asgard) - Web interface for application deployments and cloud management.
*   [Netflix/aws-autoscaling :fire::fire: (⭐427)](https://github.com/Netflix/aws-autoscaling) - Tools for using auto scaling and documentation best practices.
*   [Netflix/chaosmonkey :fire::fire::fire::fire::fire: (⭐13k)](https://github.com/Netflix/chaosmonkey) - Resiliency tool that helps applications tolerate random instance failures.
*   [Netflix/eureka :fire::fire::fire::fire::fire: (⭐12k)](https://github.com/Netflix/eureka) - Service registry for resilient mid-tier load balancing and failover.
*   [Netflix/EVCache :fire::fire::fire::fire: (⭐1.9k)](https://github.com/Netflix/EVCache) - A distributed in-memory data store.
*   [Netflix/Fenzo :fire::fire::fire: (⭐702)](https://github.com/Netflix/Fenzo) - Extensible Scheduler for Mesos Frameworks.
*   [Netflix/ice :fire::fire::fire::fire::fire: (⭐2.8k)](https://github.com/Netflix/ice) - Usage and cost monitoring tool.
*   [Netflix/ribbon :fire::fire::fire::fire::fire: (⭐4.4k)](https://github.com/Netflix/ribbon) - Remote procedure call library with built in software load balancers.
*   [Netflix/SimianArmy :fire::fire::fire::fire::fire: (⭐7.9k)](https://github.com/Netflix/SimianArmy) - Tools to keep your cloud operating in top form.
*   [Netflix/zuul :fire::fire::fire::fire::fire: (⭐13k)](https://github.com/Netflix/zuul) - Edge service that provides dynamic routing, monitoring, resiliency, security, and more.
*   [niftylettuce/gulp-aws-splash :fire::fire:](https://github.com/niftylettuce/gulp-aws-splash) - Open-source LaunchRock alternative. Build beautiful splash pages.
*   [puppetlabs/puppetlabs-aws :fire: (⭐188)](https://github.com/puppetlabs/puppetlabs-aws) - Puppet module for managing resources to build out infrastructure.
*   [mhart/react-server-routing-example :fire::fire: (⭐300)](https://github.com/mhart/react-server-routing-example) - Sample universal client/server routing and data in React.
*   [Similarweb/finala :fire::fire::fire: (⭐692)](https://github.com/similarweb/finala) - A resource cloud scanner that analyzes and reports wasteful and unused resources to cut unwanted expenses.
*   [snowplow/snowplow :fire::fire::fire::fire::fire: (⭐6.5k)](https://github.com/snowplow/snowplow) - Enterprise-strength web, mobile and event analytics, powered by Hadoop, Kafka, Kinesis, Redshift and Elasticsearch.
*   [Spinnaker/spinnaker :fire::fire::fire::fire::fire: (⭐8.9k)](https://github.com/Spinnaker/spinnaker) - Successor to asgard supporting pipelines and more.
*   [spulec/moto :fire::fire::fire::fire::fire: (⭐6.8k)](https://github.com/spulec/moto) - Allows your python tests to easily mock out the boto library.

## Guides, Books, Documentation, and Training

*How-to's, training, whitepapers, docs, and case studies.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/LxYDN5K.png">
</p>
<br/>

### Getting Started Guides

AWS Guides:

*   [Getting Started with AWS](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-intro.html)
*   [Getting Started Tutorials](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html)
    *   [Run a Virtual Server](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2614)
    *   [Store Files](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2683)
    *   [Share Digital Media](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2755)
    *   [Deploy a Website](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2767)
    *   [Host a Website (Linux)](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2836)
    *   [Host a Website (Windows)](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2908)
    *   [Run a Database](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e2980)
    *   [Analyze Your Data](http://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-tutorials.html#d0e3065)

Community Guides:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### General Guides

AWS Guides:

*   [Analyzing Big Data](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-gs.html)
*   [Working with the AWS Management Console](http://docs.aws.amazon.com/awsconsolehelpdocs/latest/gsg/getting-started.html)
*   [Deploying a Web App Using Elastic Beanstalk](http://docs.aws.amazon.com/gettingstarted/latest/deploy/overview.html)
*   [Hosting a Web App](http://docs.aws.amazon.com/gettingstarted/latest/wah-linux/web-app-hosting-intro.html)
*   [Hosting a .NET Web App](http://docs.aws.amazon.com/gettingstarted/latest/wah/web-app-hosting-intro.html)
*   [Hosting a Static Website](http://docs.aws.amazon.com/gettingstarted/latest/swh/website-hosting-intro.html)
*   [Quick Start Deployment Guides](https://aws.amazon.com/documentation/quickstart/)

Community Guides:

*   [Open Guide to AWS :fire::fire::fire::fire::fire: (⭐34k)](https://github.com/open-guides/og-aws)

### Books

*   Amazon Web Services in Action [Manning](https://www.manning.com/books/amazon-web-services-in-action) or [Amazon.com](http://amzn.com/1617292885)
*   AWS Lambda in Action [Manning](https://www.manning.com/books/aws-lambda-in-action) or [Amazon.com](http://amzn.com/1617293717) - [Code Repo :fire::fire: (⭐279)](https://github.com/danilop/AWS_Lambda_in_Action)

### Whitepapers

*   [AWS Well-Architected Framework](https://d0.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf)
*   [Whitepapers](https://aws.amazon.com/whitepapers/)

### Documentation

*   [Documentation](https://aws.amazon.com/documentation/)
*   [AWS Billing and Cost Management](https://aws.amazon.com/documentation/account-billing/)
*   [AWS Marketplace](https://aws.amazon.com/documentation/marketplace/)
*   [AWS Support](https://aws.amazon.com/documentation/aws-support/)
*   [AWS General Reference](http://docs.aws.amazon.com/general/latest/gr/)
*   [AWS Glossary](http://docs.aws.amazon.com/general/latest/gr/glos-chap.html)

### Training

*   [Training and Certification](https://aws.amazon.com/training/)
*   [Webinars](https://aws.amazon.com/about-aws/events/)

### Case Studies: Powered by AWS

*   [Adobe](https://aws.amazon.com/solutions/case-studies/adobe/)
*   [AdRoll](https://aws.amazon.com/solutions/case-studies/adroll/)
*   [Airbnb](https://aws.amazon.com/solutions/case-studies/airbnb/)
*   [Autodesk](https://aws.amazon.com/solutions/case-studies/autodesk/)
*   [Citrix](https://aws.amazon.com/solutions/case-studies/citrix/)
*   [Comcast](https://aws.amazon.com/solutions/case-studies/comcast/)
*   [Coursera](https://aws.amazon.com/solutions/case-studies/coursera/)
*   [Docker](https://aws.amazon.com/solutions/case-studies/docker/)
*   [Dow Jones](https://aws.amazon.com/solutions/case-studies/dow-jones/)
*   [Dropbox](https://www.dropbox.com/)
*   [Dropcam](https://aws.amazon.com/solutions/case-studies/dropcam/)
*   [Expedia](https://aws.amazon.com/solutions/case-studies/expedia/)
*   [Foursquare](https://aws.amazon.com/solutions/case-studies/foursquare/)
*   [IMDb](https://aws.amazon.com/solutions/case-studies/imdb/)
*   [Instrumental](https://instrumentalapp.com/blog/aws-kinesis/)
*   [Intuit](https://aws.amazon.com/solutions/case-studies/soasta-intuit/)
*   [Johnson & Johnson](https://aws.amazon.com/solutions/case-studies/johnson-and-johnson/)
*   [Lionsgate](https://aws.amazon.com/solutions/case-studies/lionsgate/)
*   [mlbam](https://aws.amazon.com/solutions/case-studies/major-league-baseball-mlbam/)
*   [NASA](https://aws.amazon.com/solutions/case-studies/nasa-jpl-curiosity/)
*   [Netflix](https://aws.amazon.com/solutions/case-studies/netflix/)
*   [Nike](https://web.archive.org/web/20150910200649/http://aws.amazon.com/solutions/case-studies/nike/)
*   [Nokia](https://web.archive.org/web/20161210062336/https://aws.amazon.com/solutions/case-studies/nokia/)
*   [PBS](https://aws.amazon.com/solutions/case-studies/pbs/)
*   [Pfizer](https://web.archive.org/web/20161210034734/https://aws.amazon.com/solutions/case-studies/pfizer/)
*   [Philips](https://aws.amazon.com/solutions/case-studies/philips/)
*   [Reddit](https://web.archive.org/web/20150905070945/https://aws.amazon.com/solutions/case-studies/reddit/)
*   [Samsung](https://aws.amazon.com/solutions/case-studies/samsung/)
*   [Siemens](https://aws.amazon.com/solutions/case-studies/siemens/)
*   [Slack](https://aws.amazon.com/solutions/case-studies/slack/)
*   [Spotify](https://web.archive.org/web/20180608043124/https://aws.amazon.com/solutions/case-studies/spotify/)
*   [Swiftkey](https://web.archive.org/web/20160410051253/https://aws.amazon.com/solutions/case-studies/swiftkey/)
*   [The Weather Company](https://aws.amazon.com/solutions/case-studies/the-weather-company/)
*   [Ticketmaster](https://aws.amazon.com/solutions/case-studies/ticketmaster/)
*   [Time Inc](https://aws.amazon.com/solutions/case-studies/time-inc/)
*   [Twilio](https://aws.amazon.com/solutions/case-studies/twilio/)
*   [U.S. Department of State](https://aws.amazon.com/solutions/case-studies/exchangesconnect/)
*   [Ubisoft](https://aws.amazon.com/solutions/case-studies/ubisoft/)
*   [Yelp](https://aws.amazon.com/solutions/case-studies/yelp-docker/)
*   [Zillow](https://aws.amazon.com/solutions/case-studies/zillow/)

## Social

*Blogs, discussion groups, conferences, and social media.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/kRRBa1e.png">
</p>
<br/>

### Blogs

AWS Blogs:

*   [Official Blog](https://aws.amazon.com/blogs/aws/)
    *   [Brasil](https://aws.amazon.com/pt/blogs/aws-brasil/)
    *   [China](https://aws.amazon.com/cn/blogs/china/)
    *   [Germany](https://aws.amazon.com/de/blogs/germany/)
    *   [Japan](https://aws.amazon.com/jp/blogs/news/)
    *   [Korea](http://aws.amazon.com/ko/blogs/korea/)
*   [DevOps](https://aws.amazon.com/blogs/devops/)
*   [Architecture](https://aws.amazon.com/blogs/architecture/)
*   [Big Data](https://aws.amazon.com/blogs/big-data/)
*   [Compute](https://aws.amazon.com/blogs/compute/)
*   [Mobile](https://aws.amazon.com/blogs/mobile/)
*   [Messaging](https://aws.amazon.com/blogs/messaging-and-targeting/)
*   [Java](https://aws.amazon.com/blogs/developer/category/programing-language/java/)
*   [PHP](https://aws.amazon.com/blogs/developer/category/programing-language/php/)
*   [Ruby](https://aws.amazon.com/blogs/developer/category/programing-language/ruby/)
*   [.NET](https://aws.amazon.com/blogs/developer/category/programing-language/dot-net/)
*   [Security](https://aws.amazon.com/blogs/security/)
*   [Startup](https://medium.com/aws-activate-startup-blog)
*   [Partner Network](https://aws.amazon.com/blogs/apn/)
*   [SAP](https://aws.amazon.com/blogs/awsforsap/)

Community Blogs:

*   [All Things Distributed](http://www.allthingsdistributed.com/) - Werner Vogels, AWS CTO.
*   [Things I Like...](http://jeff-barr.com/) - Jeff Barr, AWS Chief Evangelist.
*   [Netflix Tech Blog](http://techblog.netflix.com/)
*   [A Curated List of Engineering Blogs (⭐24k)](https://github.com/kilimchoi/engineering-blogs)
*   [AWS Geek](https://www.awsgeek.com/)

### Twitter Influencers

AWS Tweeps:

*   [@awscloud](https://twitter.com/awscloud) - Official Twitter feed.
*   [@AWS\_Partners](https://twitter.com/AWS_Partners)
*   [@AWSIdentity](https://twitter.com/AWSIdentity)
*   [@AWSMarketplace](https://twitter.com/AWSMarketplace)
*   [@AWSreInvent](https://twitter.com/AWSreInvent) - Official Twitter account for re:Invent.
*   [@AWSStartups](https://twitter.com/AWSStartups)
*   [@ajassy](https://twitter.com/ajassy) - Andy Jassy: Senior Vice-President.
*   [@Ianmmmm](https://twitter.com/Ianmmmm) - Ian Massingham - Technical Evangelist.
*   [@jeffbarr](https://twitter.com/jeffbarr) - Jeff Barr: Chief Evangelist.
*   [@mndoci](https://twitter.com/mndoci) - Deepak Singh: GM EC2.
*   [@mza](https://twitter.com/mza) - Matt Wood: Product Strategy.
*   [@Werner](https://twitter.com/Werner) - Werner Vogels: CTO.
*   [Community heroes, Evangelists, etc](https://twitter.com/awscloud/lists)

Community Tweeps:

*   [@kennwhite](https://twitter.com/kennwhite)
*   [@esh](https://twitter.com/esh)
*   [@garnaat](https://twitter.com/garnaat)
*   [@quinnypig](https://twitter.com/quinnypig)
*   [@awsgeek](https://twitter.com/awsgeek)

### Facebook Pages

AWS Pages:

*   [amazonwebservices](https://www.facebook.com/amazonwebservices) - Official Facebook page.
*   [awsreinvent](https://www.facebook.com/awsreinvent) - Official Facebook page for re:Invent.

Community Pages:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

### YouTube Channels

AWS Channels:

*   [AmazonWebServices](https://www.youtube.com/user/AmazonWebServices)
*   [AWSDeutsch](https://www.youtube.com/user/AWSAktuell)
*   [AWSJapan](https://www.youtube.com/user/AmazonWebServicesJP)
*   [AWSKorea](https://www.youtube.com/user/AWSKorea)
*   [AWSLatinAmerica](https://www.youtube.com/channel/UCvaUAVzIIGsRNlUDWkQFCeA)
*   [AWSTutorialSeries](https://www.youtube.com/user/awstutorialseries)
*   [AWSWebinars](https://www.youtube.com/user/AWSwebinars)

Community Channels:

*   [Backspace Academy](https://www.youtube.com/channel/UCav3fsasRc5VOqvZiT5avgw)
*   [Cloud Academy](https://www.youtube.com/channel/UCeRY0LppLWdxWAymRANTb0g/videos)
*   [Linux Academy](https://www.youtube.com/user/pineheadtv/playlists)

### LinkedIn Groups

AWS Page:

*   [Amazon Web Services](https://www.linkedin.com/company/amazon-web-services)

Community Groups:

*   [Amazon AWS Architects](https://www.linkedin.com/grp/home?gid=4387417)
*   [Amazon AWS Architects, Engineers, Developers, Consultants, Entrepreneurs Experts](https://www.linkedin.com/grps?gid=3748455)
*   [Amazon Web Services (AWS) for Business](https://www.linkedin.com/grps?gid=5122002)
*   [Amazon Web Services Architects](https://www.linkedin.com/grps?gid=4233997)
*   [Amazon Web Services Community Network](https://www.linkedin.com/grp/home?gid=49531)
*   [Amazon Web Services Enthusiasts](https://www.linkedin.com/grps?gid=2485626)
*   [Amazon Web Services Users](https://www.linkedin.com/grps?gid=86137)

### Subreddits

*   [/r/aws/](https://www.reddit.com/r/aws/)
*   [/r/AWS\_cloud/](https://www.reddit.com/r/AWS_cloud/)

### Conferences

AWS Conferences:

*   [re:Invent](https://reinvent.awsevents.com/) - Annual user conference. The event features keynote announcements, training and certification opportunities, over 250 technical sessions, a partner expo, after hours activities, and more.
*   [Summits](https://aws.amazon.com/summits/) - Global one-day events that are designed to educate new customers about the AWS platform and offer existing customers deep technical content to be more successful with AWS.
*   [AWSome Day](https://aws.amazon.com/events/awsome-day/awsome-day-online/) - Global one-day events are delivered by AWS Education's technical instructors and are ideal for IT pros, developers and technical managers who would like to learn about how to get started in the AWS Cloud.

Community Conferences:

*   [Contribute (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CONTRIBUTING.md)

## Latest KPIs and Stats

*Latest key performance indicators and other interesting stats.*

<br/>
<p align="center">
  <img src="http://i.imgur.com/KP2TmJv.png">
</p>
<br/>

*   Over 1 million customers active in past 30 days.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
*   $7B+ annual revenue run-rate business.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    *   81% year over year revenue growth.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
*   EC2 usage up 95% year over year.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
*   S3 data transfer up 120% year over year.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    *   S3 holds trillions of objects and regularly peaks at 1.5 million requests per second.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
*   Database services usage up 127% year over year.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
    *   $1B annual revenue run-rate business.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
*   2 million new EBS volumes created per day.<sup>[4](https://www.youtube.com/watch?v=OuyUbvtgfDk)</sup>
*   Customers have launched more than 15 million Hadoop clusters.<sup>[3](http://www.forbes.com/sites/benkepes/2014/11/25/scale-beyond-comprehension-some-aws-numbers/)</sup>
*   102Tbps network capacity into a data center.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
*   500+ major new features and services launched since 2014.<sup>[1](https://www.youtube.com/watch?v=D5-ifl7KJ00)</sup>
*   All 14 other cloud providers combined have 1/5th the aggregate capacity of AWS.<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>
*   Every day, AWS adds enough new server capacity to support all of Amazon's global infrastructure when it was a $7B annual revenue enterprise (in 2004).<sup>[2](http://highscalability.com/blog/2015/1/12/the-stunning-scale-of-aws-and-what-it-means-for-the-future-o.html)</sup>

## Appendix of Core Services

*Appendix of official services, grouped by service category.*

### Services in Plain English

*   [Amazon Web Services in Plain English](https://www.expeditedssl.com/aws-in-plain-english) - Entertaining and educational, a community contribution.

### Compute Services

*   [Auto Scaling](https://aws.amazon.com/autoscaling/) - Launches or terminates EC2 instances based on policies, schedules, and health checks.
*   [Batch](https://aws.amazon.com/batch/) - Run batch jobs at scale.
*   [Blox](https://blox.github.io/) - Open source projects for building custom schedulers on ECS.
*   [EC2 Container Service (ECS)](https://aws.amazon.com/ecs/) - Supports Docker containers on EC2 instances.
*   [EC2 Systems Manager](https://aws.amazon.com/ec2/systems-manager/) - Easily configure and manage EC2 and on-premises systems.
*   [Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) - Provides quick deployment and management of applications in the cloud.
*   [Elastic Compute Cloud (EC2)](http://aws.amazon.com/ec2/) - Provides scalable virtual private servers using Xen.
*   [Elastic GPUs](https://aws.amazon.com/ec2/Elastic-GPUs/) - Attach low-cost GPUs to EC2 instances for graphics acceleration.
*   [Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/) - Automatically distributes incoming traffic across multiple EC2 instances.
*   [Lambda](https://aws.amazon.com/lambda/) - Runs code in response to events and automatically manages EC2 instances.
*   [Lightsail](https://amazonlightsail.com/) - Launch and manage simple virtual private servers.
*   [Virtual Private Cloud (VPC)](https://aws.amazon.com/vpc/) - Creates a logically isolated set of EC2 instances which can be connected to an existing network using a VPN connection.

### Networking Services

*   [Direct Connect](https://aws.amazon.com/directconnect/) - Provides dedicated connections to AWS for faster and cheaper data throughput.
*   [Elastic Load Balancing (ELB)](https://aws.amazon.com/elasticloadbalancing/) - Automatically distributes incoming traffic across multiple EC2 instances.
*   [Route 53](https://aws.amazon.com/route53/) - Provides a highly available and scalable Domain Name System (DNS) web service.
*   [Virtual Private Cloud (VPC)](https://aws.amazon.com/vpc/) - Creates a logically isolated set of EC2 instances which can be connected to an existing network using a VPN connection.

### Enterprise Applications

*   [WorkDocs](https://aws.amazon.com/workdocs/) - Provides a fully managed, secure enterprise storage and sharing service.
*   [WorkMail](https://aws.amazon.com/workmail/) - Provides managed email and calendaring service.
*   [WorkSpaces](https://aws.amazon.com/workspaces/) - Provides a cloud-based desktop experience to end-users.
*   [Workspaces Application Manager (WAM)](http://aws.amazon.com/workspaces/applicationmanager/) - Simplifies deployment and management of WorkSpaces.

### Analytics Services

*   [Athena](https://aws.amazon.com/athena/) - Query data on S3 instantly.
*   [Data Pipeline](https://aws.amazon.com/datapipeline/) - Provides workload management by processing and moving data between services.
*   [Elastic MapReduce (EMR)](http://aws.amazon.com/elasticmapreduce/) - Hosts a Hadoop and Spark framework running on EC2 and S3.
*   [Elasticsearch Service (ES)](https://aws.amazon.com/elasticsearch-service/) - Managed Elasticsearch, a popular open-source search and analytics engine.
*   [Glue](https://aws.amazon.com/glue/) - Prepare and load data to data stores.
*   [Kinesis](https://aws.amazon.com/kinesis/) - Provides real-time data processing over large, distributed data streams.
*   [Kinesis Analytics](https://aws.amazon.com/kinesis/analytics/) - Write standard SQL queries on streaming data without having to learn any new programming skills.
*   [Kinesis Firehose](https://aws.amazon.com/kinesis/firehose/) - Captures and automatically loads streaming data into S3 and Redshift.
*   [Quicksight](https://aws.amazon.com/quicksight/) - Provides cloud-powered business intelligence for 1/10th the cost of traditional BI solutions.
*   [Redshift](https://aws.amazon.com/redshift/) - Provides petabyte-scale data warehousing with columnar storage and multi-node compute.

### Artificial Intelligence

*   [Lex](https://aws.amazon.com/lex/) - Build conversational interfaces through voice or text.
*   [Machine Learning](https://aws.amazon.com/machine-learning/) - Provides managed machine learning technology.
*   [Polly](https://aws.amazon.com/polly/) - Turn text into lifelike speech.
*   [Rekognition](https://aws.amazon.com/rekognition/) - Deep learning-based image analysis.

### Management Tools

*   [CloudFormation](https://aws.amazon.com/cloudformation/) - Provides a file-based interface for provisioning other resources.
*   [CloudTrail](https://aws.amazon.com/cloudtrail/) - Provides logs of all activity.
*   [CloudWatch](https://aws.amazon.com/cloudwatch/) - Provides monitoring for AWS cloud resources and applications, starting with EC2.
*   [Command Line Interface (CLI)](https://aws.amazon.com/cli/) - Provides a CLI to manage all services.
*   [Config](https://aws.amazon.com/config/) - Provides a detailed view of all resources.
*   [Management Console (AWS Console)](https://aws.amazon.com/console/) - A web-based interface to manage all services.
*   [OpsWorks](https://aws.amazon.com/opsworks/) - Provides configuration of EC2 services using Chef.
*   [Personal Health Dashboard](https://aws.amazon.com/premiumsupport/phd/) - Your personalized view of service health.
*   [Service Catalog](https://aws.amazon.com/servicecatalog/) - Service Catalog allows IT administrators to create, manage, and distribute portfolios of approved products to end users, who can then access the products they need in a personalized portal.

### Security and Identity Services

*   [Certificate Manager](https://aws.amazon.com/certificate-manager/) - Lets you easily provision, manage, and deploy SSL/TLS certificates for use with AWS services.
*   [CloudHSM](https://aws.amazon.com/cloudhsm/) - Helps meet corporate, contractual and regulatory compliance requirements for data security by using dedicated Hardware Security Module (HSM) appliances within the AWS cloud.
*   [Directory Service](https://aws.amazon.com/directoryservice/) - A managed service that allows you to connect your resources with an existing on-premises Microsoft Active Directory or to set up a new, stand-alone directory in the AWS Cloud.
*   [Identity and Access Management (IAM)](https://aws.amazon.com/iam/) - An implicit service, the authentication infrastructure used to authenticate access to the various services.
*   [Inspector](https://aws.amazon.com/inspector/) - An automated security assessment service that helps improve the security and compliance of applications deployed on AWS.
*   [Key Management Service (KMS)](https://aws.amazon.com/kms/) - A managed service that makes it easy for you to create and control the encryption keys used to encrypt your data.
*   [Shield](https://aws.amazon.com/shield/) - Managed DDoS Protection.
*   [WAF](https://aws.amazon.com/waf/) - A web application firewall service that monitors and manages CloudFront distributions.

### Internet of Things Service

*   [IoT](https://aws.amazon.com/iot/) - Enables secure, bi-directional communication between internet-connected things (such as sensors, actuators, embedded devices, or smart appliances) and the AWS cloud over MQTT and HTTP.

### Mobile Services

*   [API Gateway](https://aws.amazon.com/api-gateway/) - Service for publishing, maintaining and securing web service APIs.
*   [Cognito](https://aws.amazon.com/cognito/) - Provides user identity and data synchronization.
*   [Device Farm](https://aws.amazon.com/device-farm/) - App testing service for iOS, Android and Fire OS apps on physical devices.
*   [Mobile Analytics](https://aws.amazon.com/mobileanalytics/) - Service for collecting, visualizing, and understanding app usage data.
*   [Mobile Hub](https://aws.amazon.com/mobile/) - Provides an integrated console that helps you build, test, and monitor your mobile apps.
*   [Pinpoint](https://aws.amazon.com/pinpoint/) - Targeted push notifications for mobile apps.
*   [Simple Notification Service (SNS)](https://aws.amazon.com/sns/) - Provides a hosted multi-protocol "push" messaging for applications.

### Storage and Content Delivery Services

*   [CloudFront](https://aws.amazon.com/cloudfront/) - A content delivery network (CDN) for distributing objects to locations near the requester.
*   [Elastic Block Store (EBS)](https://aws.amazon.com/ebs/) - Provides persistent block-level storage volumes for EC2.
*   [Elastic File System (EFS)](https://aws.amazon.com/efs/) - A file storage service for EC2 instances.
*   [Glacier](https://aws.amazon.com/glacier/) - Provides a low-cost, long-term storage option, intended for archiving data.
*   [Import/Export](https://aws.amazon.com/importexport/) - Accelerates moving large amounts of data into and out of AWS using portable storage devices for transport.
*   [Simple Storage Service (S3)](https://aws.amazon.com/s3/) - Provides Web Service based storage.
*   [Storage Gateway](https://aws.amazon.com/storagegateway/) - An iSCSI block storage virtual appliance with cloud-based backup.

### Databases

*   [Aurora](https://aws.amazon.com/rds/aurora/) - MySQL and PostgreSQL compatible relational database with improved performance.
*   [DynamoDB](https://aws.amazon.com/dynamodb/) - Provides a scalable, low-latency NoSQL online Database Service backed by SSDs.
*   [ElastiCache](https://aws.amazon.com/elasticache/) - Provides in-memory caching for web apps (Memcached, Redis).
*   [Redshift](https://aws.amazon.com/redshift/) - Provides petabyte-scale data warehousing with columnar storage and multi-node compute.
*   [Relational Database Service (RDS)](https://aws.amazon.com/rds/) - Provides a scalable database server with MySQL, Oracle, SQL Server, PostgreSQL, and MariaDB support.
*   [Schema Conversion Tool](https://aws.amazon.com/documentation/SchemaConversionTool/) - App that helps you convert your database schema from an Oracle or Microsoft SQL Server database, to an RDS MySQL DB instance or an Aurora DB cluster.
*   [SimpleDB](https://aws.amazon.com/simpledb/) - Allows developers to run queries on structured data.

### Application Services

*   [API Gateway](https://aws.amazon.com/api-gateway/) - Service for publishing, maintaining and securing web service APIs.
*   [AppStream](https://aws.amazon.com/appstream/) - Flexible, low-latency streaming service for apps and games.
*   [CloudSearch](https://aws.amazon.com/cloudsearch/) - Provides basic full-text search and indexing of textual content.
*   [DevPay](https://aws.amazon.com/devpay/) - Provides billing and account management.
*   [Elastic Transcoder (ETS)](https://aws.amazon.com/elastictranscoder/) - Provides video transcoding of S3 hosted videos.
*   [Flexible Payments Service (FPS)](https://payments.amazon.com/developer) - Provides an interface for micropayments.
*   [Simple Email Service (SES)](https://aws.amazon.com/ses/) - Provides bulk and transactional email sending.
*   [Simple Notification Service (SNS)](https://aws.amazon.com/sns/) - Provides a hosted multi-protocol "push" messaging for applications.
*   [Simple Queue Service (SQS)](https://aws.amazon.com/sqs/) - Provides a hosted message queue for web applications.
*   [Simple Workflow (SWF)](https://aws.amazon.com/swf/) - A workflow service for building scalable, resilient applications.
*   [Step Functions](https://aws.amazon.com/step-functions/) - Coordinate components of distributed applications.

### Developer Tools

*   [CodeBuild](https://aws.amazon.com/codebuild/) - Build and test code.
*   [CodeCommit](https://aws.amazon.com/documentation/codecommit/) - Hosted Git version control service.
*   [CodeDeploy](https://aws.amazon.com/codedeploy/) - Provides automated code deployment to EC2 instances.
*   [CodePipeline](https://aws.amazon.com/documentation/codepipeline/) - Continuous delivery service.
*   [Command Line Interface (CLI)](https://aws.amazon.com/cli/) - Provides a CLI to manage all services.
*   [X-Ray](https://aws.amazon.com/xray/) - Analyze and debug your applications.

### Miscellaneous Services

*   [Fulfillment Web Service](https://aws.amazon.com/about-aws/whats-new/2008/03/19/announcing-amazon-fulfillment-web-service/) - Provides a programmatic web service for sellers to ship items to and from Amazon using Fulfillment by Amazon.
*   [Mechanical Turk](https://www.mturk.com/mturk/welcome) - Manages small units of work distributed among many persons.
*   [Partner Network (APN)](https://aws.amazon.com/partners/) - Provides partners with the technical information and sales and marketing support to increase business opportunities.
*   [Product Advertising API](http://docs.aws.amazon.com/AWSECommerceService/latest/GSG/Welcome.html) - Provides access to product data and electronic commerce functionality.

## Credits

Check out the [Credits page (⭐12k)](https://github.com/donnemartin/awesome-aws/blob/master/CREDITS.md).

## Other Awesome Lists

Other awesome lists can be found in [awesome (⭐254k)](https://github.com/sindresorhus/awesome) and [awesome-awesomeness (⭐30k)](https://github.com/bayandin/awesome-awesomeness).

## Contact Info

Feel free to contact me to discuss any issues, questions, or comments.

My contact info can be found on my [GitHub page](https://github.com/donnemartin).

## License

*I am providing code and resources in this repository to you under an open source license.  Because this is my personal repository, the license you receive to my code and resources is from me and not my employer (Facebook).*

    Copyright 2017 Donne Martin

    Creative Commons Attribution 4.0 International License (CC BY 4.0)

    http://creativecommons.org/licenses/by/4.0/


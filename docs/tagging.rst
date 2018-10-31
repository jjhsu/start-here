AWS Tagging Info
================

currently just a place to collect links and learning


General and high level
----------------------

- https://aws.amazon.com/answers/account-management/aws-tagging-strategies/



Resource Groups
---------------

- https://docs.aws.amazon.com/ARG/latest/userguide/welcome.html
- https://docs.aws.amazon.com/cli/latest/reference/resource-groups/index.html
- https://docs.aws.amazon.com/resourcegroupstagging/latest/APIReference/Welcome.html
- https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resourcegroupstaggingapi.html
- https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/resource-groups.html


Config
------

- https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html
- https://docs.aws.amazon.com/config/index.html?id=docs_gateway#lang/en_us
- https://www.sumologic.com/blog/amazon-web-services/aws-config-rules/

- https://aws.amazon.com/blogs/mt/category/management-tools/aws-config/
- https://aws.amazon.com/blogs/mt/aws-config-best-practices/
- https://aws.amazon.com/blogs/mt/how-to-query-your-aws-resource-configuration-states-using-aws-config-and-amazon-athena/


Billing and Cost Management
---------------------------

You can use tags to organize your resources, and cost allocation tags to track
your AWS costs on a detailed level. After you activate cost allocation tags,
AWS uses the cost allocation tags to organize your resource costs on your cost
allocation report, to make it easier for you to categorize and track your AWS
costs. AWS provides two types of cost allocation tags, an AWS generated tags
and user-defined tags. AWS defines, creates, and applies the AWS generated tags
for you, and you define, create, and apply user-defined tags. You must activate
both types of tags separately before they can appear in Cost Explorer or on a
cost allocation report.

- https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html#allocation-what
- https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/aws-tags.html

listing of tagable services/resources:
- https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/custom-tags.html


IAM
---

authorization based on tags:
- https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_aws-services-that-work-with-iam.html





AWS CLI
-------

aws resourcegroupstaggingapi get-tag-keys
aws resourcegroupstaggingapi get-resources | less
aws resourcegroupstaggingapi get-resources | grep ARN


Vidoes
-----

- https://www.youtube.com/watch?v=AmvMEP_eUck # Video on Billing report and cost allocation tags
- https://www.youtube.com/watch?v=TXzuWMJoei4 # video on resource groups
- https://www.youtube.com/watch?v=BoHJVGzq-58 # Video on AWS Config
- https://www.youtube.com/watch?v=QbA0859qNI8 # AWS - Acheiving continuous Compliance with AWS Config

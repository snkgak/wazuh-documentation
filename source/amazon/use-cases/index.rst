.. _amazon_use-cases:

Use Cases
===========

Wazuh AWS rules focus on providing the desired visibility within the Amazon Web Services platform.

The following sections describe some use cases for IAM, EC2 and VPC services. The structure followed in the document is always the same: You will see the definition of the rule that matches with the log message generated by the AWS event. In addition, for each of the examples, you will see an screenshot of the alerts in Kibana. Remember that an alert is triggered when the log message matches a specific rule if its level is high enough (alert threshold is configurable).

.. note::
    This section of our documentation has not yet been updated. Rules now make use of the manager ability to process JSON data natively (feature included in version 3.0.0), so there is no need to have specific AWS decoders anymore. This feature, in combination with dynamic fields (allowing rules to use variables even in their titles or descriptions), has dramatically decreased the number of rules needed to monitor AWS infrastructures.

.. topic:: Contents

    .. toctree::
       :maxdepth: 2

       iam
       ec2
       vpc

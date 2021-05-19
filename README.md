{
  "AWSTemplateFormatVersion": "2010-09-09",
  "Description": "Create an Elasticsearch Service Role",
  "Parameters": {
    "SysLevel": {
      "Type": "String",
      "Description": "System level of the cluster being created",
      "AllowedValues": [
        "na",
        "eng",
        "test"
      ],
      "Default": "na"
    }
  },
  "Conditions": {
    "isNotEng": {
      "Fn::Not": [
        {
          "Fn::Equals": [
            "eng",
            {"Ref" : "SysLevel"}
          ]
        }
      ]
    }
  },
  "Resources": {
    "AWSServiceRoleForAmazonElasticsearchService" : {
      "Condition" : "isNotEng",
      "Type" : "AWS::IAM::ServiceLinkedRole",
      "Properties" : {
        "AWSServiceName" : "es.amazonaws.com",
        "Description" : "Role for access to VPC"
      }
    }
  },
  "Outputs": {
    "SLRId": {
      "Condition" : "isNotEng",
      "Value": {
        "Ref": "AWSServiceRoleForAmazonElasticsearchService"
      }
    }
  }
}

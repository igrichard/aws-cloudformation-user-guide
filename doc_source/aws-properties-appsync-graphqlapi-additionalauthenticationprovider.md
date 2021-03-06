# AWS::AppSync::GraphQLApi AdditionalAuthenticationProvider<a name="aws-properties-appsync-graphqlapi-additionalauthenticationprovider"></a>

Describes an additional authentication provider\.

## Syntax<a name="aws-properties-appsync-graphqlapi-additionalauthenticationprovider-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-appsync-graphqlapi-additionalauthenticationprovider-syntax.json"></a>

```
{
  "[AuthenticationType](#cfn-appsync-graphqlapi-additionalauthenticationprovider-authenticationtype)" : String,
  "[OpenIDConnectConfig](#cfn-appsync-graphqlapi-additionalauthenticationprovider-openidconnectconfig)" : OpenIDConnectConfig,
  "[UserPoolConfig](#cfn-appsync-graphqlapi-additionalauthenticationprovider-userpoolconfig)" : CognitoUserPoolConfig
}
```

### YAML<a name="aws-properties-appsync-graphqlapi-additionalauthenticationprovider-syntax.yaml"></a>

```
  [AuthenticationType](#cfn-appsync-graphqlapi-additionalauthenticationprovider-authenticationtype): String
  [OpenIDConnectConfig](#cfn-appsync-graphqlapi-additionalauthenticationprovider-openidconnectconfig): 
    OpenIDConnectConfig
  [UserPoolConfig](#cfn-appsync-graphqlapi-additionalauthenticationprovider-userpoolconfig): 
    CognitoUserPoolConfig
```

## Properties<a name="aws-properties-appsync-graphqlapi-additionalauthenticationprovider-properties"></a>

`AuthenticationType`  <a name="cfn-appsync-graphqlapi-additionalauthenticationprovider-authenticationtype"></a>

The authentication type: Allowed values are (API_KEY, AWS_IAM, or AMAZON_COGNITO_USER_POOLS, OPENID_CONNECT)\.

*Required*: Yes  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`OpenIDConnectConfig`  <a name="cfn-appsync-graphqlapi-additionalauthenticationprovider-openidconnectconfig"></a>
The OpenID Connect configuration\.  
*Required*: No  
*Type*: [OpenIDConnectConfig](aws-properties-appsync-graphqlapi-openidconnectconfig.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`UserPoolConfig`  <a name="cfn-appsync-graphqlapi-additionalauthenticationprovider-userpoolconfig"></a>
The Amazon Cognito user pool configuration\.  
*Required*: No  
*Type*: [CognitoUserPoolConfig](aws-properties-appsync-graphqlapi-cognitouserpoolconfig.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

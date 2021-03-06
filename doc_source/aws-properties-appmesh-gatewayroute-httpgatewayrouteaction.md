# AWS::AppMesh::GatewayRoute HttpGatewayRouteAction<a name="aws-properties-appmesh-gatewayroute-httpgatewayrouteaction"></a>

An object that represents the action to take if a match is determined\.

## Syntax<a name="aws-properties-appmesh-gatewayroute-httpgatewayrouteaction-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-appmesh-gatewayroute-httpgatewayrouteaction-syntax.json"></a>

```
{
  "[Target](#cfn-appmesh-gatewayroute-httpgatewayrouteaction-target)" : GatewayRouteTarget
}
```

### YAML<a name="aws-properties-appmesh-gatewayroute-httpgatewayrouteaction-syntax.yaml"></a>

```
  [Target](#cfn-appmesh-gatewayroute-httpgatewayrouteaction-target): 
    GatewayRouteTarget
```

## Properties<a name="aws-properties-appmesh-gatewayroute-httpgatewayrouteaction-properties"></a>

`Target`  <a name="cfn-appmesh-gatewayroute-httpgatewayrouteaction-target"></a>
An object that represents the target that traffic is routed to when a request matches the gateway route\.  
*Required*: Yes  
*Type*: [GatewayRouteTarget](aws-properties-appmesh-gatewayroute-gatewayroutetarget.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)
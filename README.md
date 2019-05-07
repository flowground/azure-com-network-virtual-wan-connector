# ![LOGO](logo.png) VirtualWANAsAServiceManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the VirtualWANAsAServiceManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-virtualWan/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:34+03:00

## API Description

REST API for Azure VirtualWAN As a Service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the P2SVpnGateways in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all the VirtualHubs in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all the VirtualWANs in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all the VpnGateways in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all the VpnSites in a subscription.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version.

### Lists all the P2SVpnGateways in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnGateway.
* `api-version` - _required_ - Client API version.

### Deletes a virtual wan p2s vpn gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a virtual wan p2s vpn gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Updates virtual wan p2s vpn gateway tags.

*Tags:* `P2SVpnGateways`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Creates a virtual wan p2s vpn gateway if it doesn't exist else updates the existing gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Generates VPN profile for P2S client of the P2SVpnGateway in the specified resource group.

*Tags:* `P2SVpnGateways`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `gatewayName` - _required_ - The name of the P2SVpnGateway.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the VirtualHubs in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `api-version` - _required_ - Client API version.

### Deletes a VirtualHub.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `virtualHubName` - _required_ - The name of the VirtualHub.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a VirtualHub.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `virtualHubName` - _required_ - The name of the VirtualHub.
* `api-version` - _required_ - Client API version.

### Updates VirtualHub tags.

*Tags:* `VirtualWANs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `virtualHubName` - _required_ - The name of the VirtualHub.
* `api-version` - _required_ - Client API version.

### Creates a VirtualHub resource if it doesn't exist else updates the existing VirtualHub.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `virtualHubName` - _required_ - The name of the VirtualHub.
* `api-version` - _required_ - Client API version.

### Retrieves the details of all HubVirtualNetworkConnections.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `virtualHubName` - _required_ - The name of the VirtualHub.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a HubVirtualNetworkConnection.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualHub.
* `virtualHubName` - _required_ - The name of the VirtualHub.
* `connectionName` - _required_ - The name of the vpn connection.
* `api-version` - _required_ - Client API version.

### Lists all the VirtualWANs in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `api-version` - _required_ - Client API version.

### Deletes a VirtualWAN.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `VirtualWANName` - _required_ - The name of the VirtualWAN being deleted.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a VirtualWAN.

#### Input Parameters
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `VirtualWANName` - _required_ - The name of the VirtualWAN being retrieved.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Updates a VirtualWAN tags.

*Tags:* `VirtualWANs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `VirtualWANName` - _required_ - The name of the VirtualWAN being updated.
* `api-version` - _required_ - Client API version.

### Creates a VirtualWAN resource if it doesn't exist else updates the existing VirtualWAN.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `VirtualWANName` - _required_ - The name of the VirtualWAN being created or updated.
* `api-version` - _required_ - Client API version.

### Gives the supported security providers for the virtual wan.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name.
* `virtualWANName` - _required_ - The name of the VirtualWAN for which supported security providers are needed.
* `api-version` - _required_ - Client API version.

### Gives the sas-url to download the configurations for vpn-sites in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name.
* `virtualWANName` - _required_ - The name of the VirtualWAN for which configuration of all vpn-sites is needed.
* `api-version` - _required_ - Client API version.

### Retrieves all P2SVpnServerConfigurations for a particular VirtualWan.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `virtualWanName` - _required_ - The name of the VirtualWan.
* `api-version` - _required_ - Client API version.

### Deletes a P2SVpnServerConfiguration.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnServerConfiguration.
* `virtualWanName` - _required_ - The name of the VirtualWan.
* `p2SVpnServerConfigurationName` - _required_ - The name of the P2SVpnServerConfiguration.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a P2SVpnServerConfiguration.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the P2SVpnServerConfiguration.
* `virtualWanName` - _required_ - The name of the VirtualWan.
* `p2SVpnServerConfigurationName` - _required_ - The name of the P2SVpnServerConfiguration.
* `api-version` - _required_ - Client API version.

### Creates a P2SVpnServerConfiguration to associate with a VirtualWan if it doesn't exist else updates the existing P2SVpnServerConfiguration.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VirtualWan.
* `virtualWanName` - _required_ - The name of the VirtualWan.
* `p2SVpnServerConfigurationName` - _required_ - The name of the P2SVpnServerConfiguration.
* `api-version` - _required_ - Client API version.

### Lists all the VpnGateways in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `api-version` - _required_ - Client API version.

### Deletes a virtual wan vpn gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a virtual wan vpn gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Updates virtual wan vpn gateway tags.

*Tags:* `VpnGateways`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Creates a virtual wan vpn gateway if it doesn't exist else updates the existing gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Retrieves all vpn connections for a particular virtual wan vpn gateway.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `api-version` - _required_ - Client API version.

### Deletes a vpn connection.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `connectionName` - _required_ - The name of the connection.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a vpn connection.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `connectionName` - _required_ - The name of the vpn connection.
* `api-version` - _required_ - Client API version.

### Creates a vpn connection to a scalable vpn gateway if it doesn't exist else updates the existing connection.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnGateway.
* `gatewayName` - _required_ - The name of the gateway.
* `connectionName` - _required_ - The name of the connection.
* `api-version` - _required_ - Client API version.

### Lists all the vpnSites in a resource group.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnSite.
* `api-version` - _required_ - Client API version.

### Deletes a VpnSite.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnSite.
* `vpnSiteName` - _required_ - The name of the VpnSite being deleted.
* `api-version` - _required_ - Client API version.

### Retrieves the details of a VPN site.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnSite.
* `vpnSiteName` - _required_ - The name of the VpnSite being retrieved.
* `api-version` - _required_ - Client API version.

### Updates VpnSite tags.

*Tags:* `VpnSites`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnSite.
* `vpnSiteName` - _required_ - The name of the VpnSite being updated.
* `api-version` - _required_ - Client API version.

### Creates a VpnSite resource if it doesn't exist else updates the existing VpnSite.

#### Input Parameters
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group name of the VpnSite.
* `vpnSiteName` - _required_ - The name of the VpnSite being created or updated.
* `api-version` - _required_ - Client API version.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-virtual-wan-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.

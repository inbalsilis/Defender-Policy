Please create New Policy in Azure Policy and copy the JSON to the Policy Rule.

Please give it the relevant name.

Please set Category = Security Center.

Please set the relevant scope and save the policy.

When assigning the policy, please set parameters:

1.workspace region - the region of the Defender for cloud workspace

2.Data Collection Endpoint Resource Id - the resource id from the data collection endpoint to be assigned. You can find it in the data collection endpoint JSON

Note: if you have multiple regions, the policy should be created per region with the relevant dataCollectionEndpointId

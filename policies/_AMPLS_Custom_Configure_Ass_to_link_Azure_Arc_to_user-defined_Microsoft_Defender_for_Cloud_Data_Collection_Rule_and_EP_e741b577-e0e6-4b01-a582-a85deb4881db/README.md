Please create New Policy in Azure Policy and copy the JSON to the Policy Rule. 
Please give it the relevent name. 
Please set the relevent scope and save the policy. 
When assigning the policy, please set parameters: 
1.workspace region - the region of the Dafender for cloud workspace 
2.Data Collection Endpoint Resource Id - the resourde id from the data collection endpoint to be assigned. You can find it in the data collection endpoint JSON

Note: if you have multiple regions, the policy should be created per region with the relevent dataCollectionEndpointId
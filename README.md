# deployment-opcpublisher-filtermodule

When you have a new version of the filter module, visit this link:

`https://portal.azure.com/#@techco-electrics.com/resource/subscriptions/b5ebd17a-d979-4136-b578-f41dd4ad7d4d/resourceGroups/rg_900_431/providers/Microsoft.Devices/IotHubs/iotHUB431001/ConfigurationExplorer`

To create a new deployment, select the latest version and clone it.
In the cloned deployment, update the version of the filtermodule and set a higher priority.
After creating the new deployment with the higher priority, all Edge Devices with the corresponding tags will automatically be updated.
# [Command] _monitor data-collection rule show_

Return the specified data collection rule.

## Versions

### [2022-06-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5pbnNpZ2h0cy9kYXRhY29sbGVjdGlvbnJ1bGVzL3t9/2022-06-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.insights/datacollectionrules/{} 2022-06-01 -->

#### examples

- Get data collection rule
    ```bash
        monitor data-collection rule show --name "myCollectionRule" --resource-group "myResourceGroup"
    ```
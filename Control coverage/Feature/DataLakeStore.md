## Data Lake Storage

| ControlId | Dependent Azure API(s) and Properties | Control spec-let |
|-----------|-------------------------------------|------------------|
| <b>ControlId:</b><br>Azure_DataLakeStore_DP_Encrypt_At_Rest<br><b>DisplayName:</b><br>Data Lake Store sensitive data must be encrypted at rest<br><b>Description: </b><br> Sensitive data must be encrypted at rest | <b> ARM API to get the specified Data Lake Store account: </b> <br> /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}? <br> api-version=2016-11-01 <br><b>Properties:</b><br> properties.encryptionState | <b>Passed: </b><br>Encryption is enabled.<br><b>Failed: </b><br>Encryption is disabled. |


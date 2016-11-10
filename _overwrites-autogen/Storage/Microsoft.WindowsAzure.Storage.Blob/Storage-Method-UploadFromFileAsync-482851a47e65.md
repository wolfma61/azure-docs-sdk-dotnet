---
uid: 
remarks: *content
---
## Remarks  
 Use this method only in single-writer scenarios. Internally, this method uses the append-offset conditional header to avoid duplicate blocks, which may cause problems in multiple-writer scenarios.                     If you have a single-writer scenario, see [Microsoft.WindowsAzure.Storage.Blob](assetId:///N:Microsoft.WindowsAzure.Storage.Blob?qualifyHint=False&autoUpgrade=True) to determine whether setting this flag to `true` is acceptable for your scenario.             To append data to an append blob that already exists, see [AppendFromFileAsync](assetId:///M:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob.AppendFromFileAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)?qualifyHint=False&autoUpgrade=True).
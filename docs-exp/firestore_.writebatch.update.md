<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [WriteBatch](./firestore_.writebatch.md) &gt; [update](./firestore_.writebatch.update.md)

## WriteBatch.update() method

Updates fields in the document referred to by the provided [DocumentReference](./firestore_.documentreference.md)<!-- -->. The update will fail if applied to a document that does not exist.

<b>Signature:</b>

```typescript
update(documentRef: DocumentReference<unknown>, data: UpdateData): WriteBatch;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  documentRef | [DocumentReference](./firestore_.documentreference.md)<!-- -->&lt;unknown&gt; | A reference to the document to be updated. |
|  data | [UpdateData](./firestore_.updatedata.md) | An object containing the fields and values with which to update the document. Fields can contain dots to reference nested fields within the document. |

<b>Returns:</b>

[WriteBatch](./firestore_.writebatch.md)

This `WriteBatch` instance. Used for chaining method calls.


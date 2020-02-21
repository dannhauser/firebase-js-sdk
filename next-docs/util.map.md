<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/util](./util.md) &gt; [map](./util.map.md)

## map() function

<b>Signature:</b>

```typescript
export declare function map<K extends string, V, U>(obj: {
    [key in K]: V;
}, fn: (value: V, key: K, obj: {
    [key in K]: V;
}) => U, contextObj?: unknown): {
    [key in K]: U;
};
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  obj | <code>{</code><br/><code>    [key in K]: V;</code><br/><code>}</code> |  |
|  fn | <code>(value: V, key: K, obj: {</code><br/><code>    [key in K]: V;</code><br/><code>}) =&gt; U</code> |  |
|  contextObj | <code>unknown</code> |  |

<b>Returns:</b>

`{
    [key in K]: U;
}`

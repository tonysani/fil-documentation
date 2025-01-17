# Requesting peer details

**Protocol**: `HTTP`

**Encoding**: `JSON`

**Endpoint**: `/data/api/v1/peer-management/details`

**Method**: `GET`

**Parameters**: —

**Input/request structure**:

A `GET` request to the endpoint.

**Output/response structure**:

::: details Show

```json5
{
  status: {
    code: 0, //integer($int32)
    name: 'string',
    message: 'string'
  },
  data: {
    accountId: 'string',
    domainId: 'string',
    accountMetadata: {
      additionalProp1: {},
      additionalProp2: {},
      additionalProp3: {}
    },
    domainMetadata: {
      additionalProp1: {},
      additionalProp2: {},
      additionalProp3: {}
    }
  }
}
```

:::

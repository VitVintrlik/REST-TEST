##  Query showing VM(s) details

```python
{
  virtualHostList(
    filters: {uuid: {iContains: "schrejos"}}
  ) {
    edges {
      node {
        id
        hostname
        fullname
        healthState
      }
    }
  }
}
```

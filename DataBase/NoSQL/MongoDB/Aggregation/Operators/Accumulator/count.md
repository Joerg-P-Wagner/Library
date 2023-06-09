<sup>[MongoDB Docs $count](https://www.mongodb.com/docs/manual/reference/operator/aggregation/count-accumulator/)</sup>

# Count

```mongoDB
db.<collection>.aggregate([
    {
        <stage>:
        {
            <field>: <expression>,
            <field>: { $count: {} }
        }
    }
])
```

**return**: number of Documents in a group

- accept no parameters
- available in stages:
  - $bucket
  - $bucketAuto
  - $group
  - $setWindowFields

[Examples](https://www.mongodb.com/docs/manual/reference/operator/aggregation/count-accumulator/#examples)

---

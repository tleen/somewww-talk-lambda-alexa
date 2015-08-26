---
order: 3
group: lambda-code
group_order: 0
---

# Lambda Code
JavaScript Node (also Java)

* Similar to a Node Module
* Export the handler function (lambda function)

```
exports.handler = function(event, context) {
  context.succeed('hello world');
};
```


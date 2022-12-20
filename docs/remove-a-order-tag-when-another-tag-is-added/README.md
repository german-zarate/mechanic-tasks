# Remove an order tag when another tag is added

Tags: Orders, Untag, Watch

Does exactly as it says. :)

* View in the task library: [tasks.mechanic.dev/remove-a-order-tag-when-another-tag-is-added](https://tasks.mechanic.dev/remove-a-order-tag-when-another-tag-is-added)
* Task JSON, for direct import: [task.json](../../tasks/remove-a-order-tag-when-another-tag-is-added.json)
* Preview task code: [script.liquid](./script.liquid)

## Default options

```json
{
  "order_tag_to_watch_for__required": "apple",
  "order_tag_to_remove__required": "butter",
  "ignore_tag_case__boolean": true
}
```

[Learn about task options in Mechanic](https://learn.mechanic.dev/core/tasks/options)

## Subscriptions

```liquid
shopify/orders/updated
```

[Learn about event subscriptions in Mechanic](https://learn.mechanic.dev/core/tasks/subscriptions)

## Documentation

Does exactly as it says. :)

## Installing this task

Find this task [in the library at tasks.mechanic.dev](https://tasks.mechanic.dev/remove-a-order-tag-when-another-tag-is-added), and use the "Try this task" button. Or, import [this task's JSON export](../../tasks/remove-a-order-tag-when-another-tag-is-added.json) – see [Importing and exporting tasks](https://learn.mechanic.dev/core/tasks/import-and-export) to learn how imports work.

## Contributions

Found a bug? Got an improvement to add? Start here: [../../CONTRIBUTING.md](../../CONTRIBUTING.md).

## Task requests

Submit your [task requests](https://mechanic.canny.io/task-requests) for consideration by the Mechanic community, and they may be chosen for development and inclusion in the [task library](https://tasks.mechanic.dev/)!
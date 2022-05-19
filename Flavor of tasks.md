# Flavor of tasks

| | Launched by | Launchable from | Lifetime | Cancellation | Inherits from origin
| --- | --- | --- | --- | --- | --- |
| async-let tasks | `async let x` | `async` functions | scoped to statement | automatic | priority, task-local values
| Group tasks | `group.async` | `withTaskGroup` | scoped to task group | automatic | priority, task-local values
| Unstructured tasks | `Task` | anywhere | unscoped | via `Task` | priority, task-local values, actor
| Unstructured tasks | `Task.detached` | anywhere | unscoped | via `Task` | nothing

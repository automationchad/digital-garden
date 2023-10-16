### Permissions/Workspaces in Tray

Granting "contributor access" to a client can be a double-edged sword. On one side, it enables the client to modify workflows, which could be beneficial for small tweaks or quick updates without having to loop in your team. On the flip side, giving them this level of access means they might inadvertently break a workflow, which leads to troubleshooting headaches.

I wish Tray had an extra level of entity like Orgs within an Account that would allow you to further seperate users.

I don't know if Tray would be willing to provision Manobyte separate tray orgs for each client that you want to have editing their workflows.

### Task Usage Calculator in Tray

#### Task ≠ Step

You're correct in noting that a task is not always equivalent to a step in a workflow. Tasks often comprise multiple steps, particularly when data transformation is involved. The amount of data processed can also affect task calculation, making pre-implementation estimates difficult.

#### Task Estimation Challenges

1. **Field Mapping**: It's common in your line of work to lack full field mapping requirements upfront. This makes static task estimation nearly impossible.
2. **Conditional Logic**: Many workflows involve conditional logic, which can dramatically vary the task usage per run.

So last time I heard the calculator was so vague that we just never used it with customers -- it's essentially a spreadsheet with some basic buckets. It doesn't provide definitive answers based on super specific context.
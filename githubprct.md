# ***Github actions***: - is a tehnology that allow us to automate tasks on Github.
# ***Workflows***: is a yaml file(yaml: is format is readable by human.), where tasks and steps to be executed are defined


# ***warkflow*** has triggers, which are those situations that cause the exection of the workflow.
# ***jobs*** is a set of steps that are performed to do a task.
# ***steps*** are the individual units of work within a job. 

GitHub Actions **workflows** can be triggered by schedules, manual runs, or external webhooks.

# External webhooks:
- repository_dispatch (triggered by external HTTP requests)

# Reusable workflows:
- workflow_call (used to trigger one workflow from another)

# Event-based triggers:
- push
- pull_request
- issues
- issue_comment
- fork
- release
- watch
- create
- delete

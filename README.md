1. Firstly we understand what are the GitHub actions, and how these actions are created on the project. ✅
2. Next, we try to uderstand more about the actions workflow(creating more than one workflow, creating a workflow_event dispatch trigger).✅
3. We now need to understand how can we trigger one action to be called after the first trgigger is successful
    a. Both our workflows would need user input that would be different for both the workflows
4. The action was being triggered on being pushed, as well as manually on the workflow dispatch, so we removed the feature to automatically run the workflow on push.
5. Our workflow is working only for the main branch at the moment, but we want to make it available for all the branches.

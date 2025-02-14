1. Firstly we understand what are the GitHub actions, and how these actions are created on the project. ✅
2. Next, we try to uderstand more about the actions workflow(creating more than one workflow, creating a workflow_event dispatch trigger).✅
3. We now need to understand how can we trigger one action to be called after the first trgigger is successful✅
4. Both our workflows would need user input that would be different for both the workflows✅
5. The action was being triggered on being pushed, as well as manually on the workflow dispatch, so we removed the feature to automatically run the workflow on push.✅
6. Our workflow is working only for the main branch at the moment, but we want to make it available for all the branches.✅
7. Next, we wanted completion of one workflow triggering the other workflow's start, which we achieved by correctly copying the "name" of the deployment_workflow in the second workflow ✅
8. The dynamic name in the second workflow should take the imput of its name from the first workflow. 

### Create Data science notebook.

- OCI Console > `Analytics & AI` > `Data Science`
- Click `Create project`.

![](images/ds_project.png)

- Create a `Notebook session`.

![](images/notebook1.png)


### Create a custom logs.
- OCI Console > `Logging` > `Create Log Group`

![](images/create_loggroup.png)

- Under the `Log Group` > `Create custom log`

![](images/create_custom_log.png)
- Skip `Agent configuration` and create the custom log.

### Validate the notebook sessions.

- Go back the `Data science` > `Project`>`Note book` > `Open`

![](images/open_nb.png)

- Use proper credentials and open the notebook.
- Validate that the notebook has `AI quick actions` extension.

![](images/aqua_extension.png)

- Click `Extend` to extend the sessions.

**ℹ️ Information**

```shell
If you have active notebooks created from before the release of AI quick actions, to access AI quick actions from them, deactivate and reactivate them. 
All notebooks created after the release of AI quick actions have AI quick actions available.
```

[⬅️ Policies](policies.md)[🏠 Back to Home](../README.md) [➡️ Deployments](deployments.md)
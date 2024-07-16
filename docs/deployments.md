### Deploy models using OCI AI Quick actions.

Under Models, you can find Model Explorer that shows all the foundation models supported by AI Quick Actions and your fine-tuned models. Under My models are service curated foundation models and models you have registered. Under Fine-tuned models are models you have fine-tuned. Under Ready-to-register models are models you can bring from Object Storage and register in AI Quick Actions.

##### Curated Models
Curated models have been tested by Data Science and the model artifacts are downloaded to a bucket in the service's object storage. They are ready to be used.

##### Ready-to-Register Models
Ready-to-Register models have been tested by Data Science, but the model artifacts must be downloaded to your Object Storage bucket and brought in to AI Quick Actions through the Model Registration process before they can be used.

#### Deploy a Curated model.

- From AI quick actions > `Models` > Click on model card

![](images/cm_deploy.png)

- Refer `README` for more details about the curated model. click `Deploy`

![](images/cm_rm.png)

- Select desired `Compute shape` , `Log group` and `Log name`

![](images/cm_deploy_shape.png)

- you may use `advanced options` to update details and can add parameters according to the inference containers (vLLM,TGI etc)

![](images/cm_deploy_advancedoptions.png)

#### Read more 
[Read more.](https://github.com/oracle-samples/oci-data-science-ai-samples/blob/main/ai-quick-actions/model-deployment-tips.md)


[⬅️ Notebooks](notebook.md)[🏠 Back to Home](../README.md) [➡?](deployments.md)
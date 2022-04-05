Repeat the pre-BCB training provided by Makers, by Josue. Set up a cluster and app using terraform first. Once you can do this reliably, move on to using gitlab and pipelines. Also add tests

Have an app
Make a change
Push to gitlab
Run tests and linting
Throw errors if wrong
Build images
Send images to eg dockerhub
Provision cluster with images, built into container
Specify an env
Trigger slack messages

NETWORKING - how the pods/nodes communicate with each other

One zonal cluster per billing account is free on GKE

Using: https://learn.hashicorp.com/tutorials/terraform/gke


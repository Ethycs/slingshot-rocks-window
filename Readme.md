# Instructions
* Create your environment in conda with `conda create -n slingshot ipykernel ipywidgets notebook -c conda-forge`
* Make sure you run `python -m modal setup` to get an API token on the local system
* wandb.login()


How do I pass secrets with modal? https://modal.com/docs/guide/secrets
Hopefully, we'll actually do parsing by making direct API calls and then send to the 'mainframe'
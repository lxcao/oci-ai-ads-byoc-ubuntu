# oci-ai-ads-byoc-ubuntu

This repository are example scripts following : https://accelerated-data-science.readthedocs.io/en/latest/user_guide/cli/opctl/localdev/jobs.html#test-container-image


you have to manually change the following configuration parameters:

  /*"extensions": [
    "ms-python.python"
  ],*/
  "customizations": {
    "vscode": {
      "settings": {},
      "extensions": ["ms-python.python"]
    }
  },


And actually, we can follow :  https://code.visualstudio.com/docs/devcontainers/create-dev-container to create the .devcontainer.json by dev container extension and avoid the configuration error.





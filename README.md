## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

:books: Same functionality. Better performance for you. :books:

Over the past few months, we've been improving Binder's architecture and infrastructure. We're retiring this repo as it will no longer be actively developed. Future development will occur under the [JupyterHub](https://github.com/jupyterhub/) organization.

* All development of the Binder technology will occur in the [binderhub repo](https://github.com/jupyterhub/binderhub)
* Documentation for *users* will occur in the [jupyterhub binder repo](https://github.com/jupyterhub/binder) 
* All conversations and chat for users will occur in the [jupyterhub binder gitter channel](https://gitter.im/jupyterhub/binder)

Thanks for updating your bookmarked links.

## :dash: :dash: **The Binder Project is moving to a [new repo](https://github.com/jupyterhub/binderhub).** :dash: :dash:

---

# Example Binder with environment.yml

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/binder-project/example-conda-environment)

A Binder-compatibible repo with an `environment.yml` file.

The `environment.yml` file should list all Python libraries that your notebooks depend on, specified as though they were created
using the following conda commands:

```
source activate example-environment
conda env export > environment.yml
```

Note that the only libraries available to you will be the ones specified in the `environment.yml`, so be sure to include everything that you need!

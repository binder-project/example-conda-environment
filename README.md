# Example Binder with environment.yml

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/binder-project/example-conda-environment)

A Binder-compatibible repo with an `environment.yml` file.

The `environment.yml` file should list all Python libraries that your notebooks depend on, specified as though they were created
using the following conda commands:

```
source activate example-environment
conda env export > environment.yml
```

Note that many scientific Python libraries (e.g. `numpy`, `scipy`, `sklearn`, etc.) are included already because the [`base`](https://github.com/binder-project/binder/blob/master/images/base/Dockerfile) image for Binder is built on Anaconda.

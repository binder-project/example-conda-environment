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

# CRUK-CI NextFlow Plugins

A tiny public repository to host a `plugins.json` file for CRUK-CI Nextflow plugins.

To access our plugins in Nextflow workflows, one needs to set the `NXF_PLUGINS_TEST_REPOSITORY`
before launching Nextflow:

```BASH
export NXF_PLUGINS_TEST_REPOSITORY="https://github.com/crukci-bioinformatics/nextflow-plugins/raw/refs/heads/master/plugins.json"
```

Any new plugins or releases of existing ones need to be added to the `plugins.json` file
in this repository to made available for our other pipelines.


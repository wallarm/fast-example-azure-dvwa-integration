# README

This is an example of Wallarm FAST running security tests in the Azure DevOps pipeline. The target application is DVWA.

## How to reproduce example

1. Fork this repository.
2. Create the FAST node and copy a token value by the [link](https://us1.my.wallarm.com/testing/nodes).
3. Create a new pipeline for the forked repository in Azure DevOps.
4. Configure the `WALLARM_API_TOKEN` variable with the copied token value in Azure DevOps.
5. Run the pipeline.

## Useful links

- More about Wallarm FAST: https://wallarm.com/products/fast
- More about Azure DevOps: https://docs.microsoft.com/en-us/azure/devops/
- DVWA application's source code: https://github.com/wallarm/fast-example-dvwa
- Full FAST documentation: https://docs.fast.wallarm.com

Try Wallarm FAST now: https://fast.wallarm.com/signup

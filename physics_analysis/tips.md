# Tips and debugs

## Start a new analysis

#### What if I don't know how to run the framework

If the framework is already setup, but you don't know how to run the code. The first choice is to see the README or tutorial from others. If there is no instructions, you can try to see the "yaml file \(.gitlab-ci.yml\)" and see how the code can be run with the [continuous integration \(CI\)](https://docs.gitlab.com/ee/ci/). GitLab CI aim to automatically run the program to see if the code will run smoothly with your new commits. Therefore, we can hack into this and see how it works, and try to reproduce how we can execute the framework. 

An example of the yaml file will look like [this](https://gitlab.cern.ch/atlas-physics/higgs/hww/HWWAnalysisCode/blob/master/.gitlab-ci.yml). 

#### Find the datasets

The instruction is shown [here](https://indico.cern.ch/event/831761/contributions/3484260/attachments/1931553/3199246/FindingDatasets.pdf). 

## Debug and common issues

### Negative MC events

This might result from the negative mc weight. What we can do is to figure out if there is any weight is negative. 


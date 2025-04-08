# AI Software Template Gitops

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template. The associated source component is available for reference in the **Overview** tab. You can find an example of this reference in the following image.

![Overview Tab](./images/overview-dependency.png)

# Deployed Resources
Based on the input from the AI Software Template, a deployment with the following characterisics was made:

# Model Server
**Model Server:** [detr-resnet-101]( https://github.com/containers/ai-lab-recipes/tree/main/model_servers/object_detection_python)

**Port:** 8000

# Application
An application built from https://github.com/jdubrick-ai/apr8-objdet will be stored in [quay.io/jdubrick-ai/apr8-objdet](https://quay.io/jdubrick-ai/apr8-objdet) and deployed through GitOps. This application is accessible on port **8501**.
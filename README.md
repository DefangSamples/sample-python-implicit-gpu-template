# Python & Implicit & GPU

[![1-click-deploy](https://raw.githubusercontent.com/DefangLabs/defang-assets/main/Logos/Buttons/SVG/deploy-with-defang.svg)](https://portal.defang.dev/redirect?url=https%3A%2F%2Fgithub.com%2Fnew%3Ftemplate_name%3Dsample-python-implicit-gpu-template%26template_owner%3DDefangSamples)

This Music Recommendation API provides artist recommendations based on collaborative filtering using the Alternating Least Squares (ALS) algorithm from the implicit library. The dataset utilized is from Last.fm. Note that alongside your .py file, include a requirements.txt so that the Dockerfile can install the necessary packages with pip. It demonstrates how to use a GPU with Python and the implicit library with Defang.

## Essential Setup Files

1. A [Dockerfile](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/).
2. A [compose file](https://docs.defang.io/docs/concepts/compose) to define and run multi-container Docker applications (this is how Defang identifies services to be deployed). (compose.yaml file)

## Prerequisite

1. Download [Defang CLI](https://github.com/DefangLabs/defang)
2. If you are using [Defang BYOC](https://docs.defang.io/docs/concepts/defang-byoc), make sure you have properly [authenticated your AWS account (optional)](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)

## A Step-by-Step Guide

1. Open the terminal and type `defang login`
2. Type `defang compose up` in the CLI
3. Your app should be up and running with Defang in minutes!

---

Title: Python & Implicit & GPU

Short Description: A Music Recommendation API that provides artist recommendations based on collaborative filtering using the ALS algorithm from the Implicit library, leveraging a GPU.

Tags: Music, Recommendation, API, Collaborative Filtering, Implicit, GPU, Python

Languages: python

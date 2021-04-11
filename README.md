# rating-web

**This repository has been deprecated. Content moved to: https://github.com/MicrosoftDocs/mslearn-aks-workshop-ratings-web**

Container exposes port 8080.
Required configuration via environment variables:

- API: `<set to rating-api endpoint>`. This _does not_ have to be publicly accessible. The application proxies the API requests via the backend to the rating-api endpoint.

# Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

docker login k88workshopregistry.azurecr.io -u 20ec23eb-ac8b-4fb7-aabb-32c21f80656a -p iBkmAg.\_G98Xcz6_U7-8.8ABb1EBf2Dk_F

az login --service-principal --username 20ec23eb-ac8b-4fb7-aabb-32c21f80656a --password iBkmAg.\_G98Xcz6_U7-8.8ABb1EBf2Dk_F --tenant baa53e47-b3a7-490b-a0c1-4cde8617f7cc

baa53e47-b3a7-490b-a0c1-4cde8617f7cc

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

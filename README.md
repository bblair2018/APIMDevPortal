# Azure API Management developer portal

This repository is managed by the [Microsoft Azure API Management](https://aka.ms/apimrocks) team and contains the source code of the developer portal. Refer to the [official Azure documentation](https://aka.ms/apimdocs/portal) for more information and instructions. 

![API Management developer portal](readme/portal.png)

## <a name="releases"></a> Releases

The `master` branch of this repository is used for daily development purposes and may contain unstable version of the software. We recommend using [releases](https://github.com/Azure/api-management-developer-portal/releases) for setting up your portal.

## <a name="feedback"></a> Interactions

You can **report bugs** or **submit feature requests** in [the repository's Issues section](https://github.com/Azure/api-management-developer-portal/issues).

Microsoft Azure Support assistance is limited to managed portals and only the initial setup of self-hosted portals ([documentation](https://aka.ms/apimdocs/selfhostportal)); best effort support is provided for problems that are caused by environmental factors, such as (but not limited to): hosting platform, development environment, network configuration. Other self-hosted portal assistance requests (for example, problem with custom widgets) should be submitted [on Stack Overflow](https://aka.ms/apimso) with the `azure-api-management` tag. **We don't provide support through GitHub Issues**.

We welcome and appreciate [community contributions](CONTRIBUTIONS.md). Refer to the [contribution guidelines](https://aka.ms/apimdocs/portal/contribute) for more information.

## <a name="license"></a> License

The developer portal is published under the [MIT license](license).

## <a name="Updates by John Blair"></a> Updates by John Blair
- Added a page called "Doc" on the main form, when you click on it, widget static html document I added.
- The static page I added is here: https://htmlcontentstorage.blob.core.windows.net/files/sample.html
- I can get this to work locally, but when a do a local publish and push to azure, the static document I added through teh widget is not there.
- Made changes to the following files:
  - constants.ts
  - document-details-runtime.ts
  - apim.deisgn.module.ts
  - apim.publish.module.ts
  - apin-runtime.module.tst

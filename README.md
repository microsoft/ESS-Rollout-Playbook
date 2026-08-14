# ESS Rollout & Adoption Playbook

The ESS Rollout & Adoption Playbook is a public, interactive planning tool for Employee Self-Service deployments. It guides teams from rollout context and priorities to a tailored playbook covering foundation, strategy, execution, adoption, and value realization.

## Use the playbook

Visit [microsoft.github.io/ESS-Rollout-Playbook](https://microsoft.github.io/ESS-Rollout-Playbook/).

The site runs entirely in the browser. Questionnaire responses are not sent to a server or stored by the application. PDF export uses the browser's print dialog.

## Development

The application is self-contained in `index.html`; it has no build step or runtime dependencies. Open the file directly in a browser for basic development, or serve the repository with any static HTTP server for production-equivalent testing.

## Deployment

Pushes to `main` deploy through the GitHub Pages workflow in `.github/workflows/deploy-pages.yml`. The repository must have **Settings > Pages > Build and deployment > Source** set to **GitHub Actions**.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.

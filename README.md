# Yggdrasil Helm Charts

Welcome to the Yggdrasil Helm Charts repository. This repository aims to bridge the gap in the Kubernetes ecosystem by offering a curated collection of Helm charts for open-source applications lacking official support. Each chart is designed to simplify deployments while adhering to the highest standards of quality, reliability, and adaptability.

**Please note that this repository is in its early stages and is very much a work in progress at the moment.**

## Repository Objectives

- **Enhanced Security**: Implement modern security practices to protect Kubernetes deployments.
- **Comprehensive Features**: Deliver charts that are versatile and cater to a wide range of use cases.
- **Community Empowerment**: Support the open-source community with well-maintained and accessible charts.
- **Ease of Use**: Prioritize clarity and simplicity in configurations and documentation.

## Foundation and Inspiration

The charts in this repository draw heavily from the Bitnami Helm charts, which are widely regarded as the gold standard for Helm chart development. By building on this solid foundation, we aim to provide enhancements and adaptations that align with the specific needs of the FOSS applications we support, while maintaining the reliability and consistency that Bitnami charts are known for.

## Repository Structure

- `charts/`: Contains individual Helm charts, organized by application. Each chart includes:
  - `Chart.yaml`: Metadata for the Helm chart.
  - `values.yaml`: Configurable parameters with sensible defaults.
  - `ci/`: Collection of values files for use in CI workflows. Each file must match the pattern `*-values.yaml` and will be treated as a separate test/deployment in the CI environment.
  - `templates/`: Kubernetes templates to facilitate deployments.

## Contribution Guidelines

We welcome contributions from all members of the community. To maintain quality and consistency, please follow these steps:

1. **Fork the Repository**: Create a personal fork to work on your changes.
2. **Use Feature Branches**: Develop in a branch named for your feature or fix.
3. **Run Pre-commit Hooks**: Ensure all hooks pass by executing `pre-commit run --all` locally.
4. **Validate Charts**: Use `helm lint` and test deployments in a Kubernetes environment to verify functionality.
5. **Submit a Pull Request**: Provide a clear description of your changes for review.

## Quality Assurance

- **Rigorous Linting**: Charts undergo thorough linting to detect and resolve issues early.
- **Automated Testing**: Continuous testing ensures reliability and compatibility with Kubernetes standards.
- **Semantic Versioning**: Version numbers reflect the nature and impact of changes, helping users track updates effectively.

## Community Support

For issues, feature requests, or discussions, please open an issue in this repository. Your feedback and suggestions help us improve and expand our chart offerings.

## Acknowledgments

This repository is made possible thanks to the open-source community and Kubernetes ecosystem. Your collaboration and innovation drive the continuous improvement of this project.

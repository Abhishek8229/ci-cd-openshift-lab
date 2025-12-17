# CI/CD with OpenShift Pipelines

This project demonstrates a complete CI/CD pipeline using:

- GitHub Actions
- Tekton Pipelines
- OpenShift
- Python application

The pipeline includes:
- Cleanup
- Git clone
- Linting with flake8
- Unit testing with nose
- Image build using buildah
- Deployment using OpenShift client

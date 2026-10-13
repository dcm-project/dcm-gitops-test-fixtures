# DCM GitOps test fixtures

Public, non-secret manifests used by DCM GitOps E2E tests.

The default test fixture is `catalog-item-instance.yaml` on the `main` branch.
It references the disposable catalog item `dcm-gitops-two-tier-web`, which must
be present in the target DCM deployment before a provisioning test consumes the
manifest.

The repository intentionally contains no credentials, tokens, private URLs, or
environment-specific hostnames.

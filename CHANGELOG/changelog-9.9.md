# Changelog

## [v9.9.1](https://github.com/kubeflow/trainer/releases/tag/v9.9.1) (2026-05-19)

This is Kubeflow Trainer v9.9.1 release.

```bash
kubectl apply --server-side -k "https://github.com/kubeflow/trainer.git/manifests/overlays/manager?ref=v9.9.1"
kubectl apply --server-side -k "https://github.com/kubeflow/trainer.git/manifests/overlays/runtimes?ref=v9.9.1"
```

You can now install controller manager with Helm charts 🚀

```bash
helm install kubeflow-trainer oci://ghcr.io/kubeflow/charts/kubeflow-trainer --version 9.9.1
```

For more information, please see [the Kubeflow Trainer docs](https://www.kubeflow.org/docs/components/trainer/overview/)
### 🚀 Features

- feat: KEP for inject PET envs into init-container ([#3417](https://github.com/kubeflow/trainer/pull/3417) by @panpan0000)
- feat: split changelog by release line (@Krishna Gupta)

### ⚙️ Miscellaneous Tasks

- chore:removed the monoloith CHANGELOG.md (@Krishna Gupta)


### New Contributors
* @panpan0000 made their first contribution in [#3417](https://github.com/kubeflow/trainer/pull/3417)

# Cloud Native GitLab Helm Chart -- Reduced in resource footprint

The `gitlab` chart is the best way to operate GitLab on Kubernetes. It contains
all the required components to get started, and can scale to large deployments.

The disadvantage is that it is very resource intensive for smaller use case deployments. Reducing the resource footprint by:
- Reducing the replica amounts to 1 for all deployments

Source clone: https://gitlab.com/gitlab-org/charts/gitlab.git 

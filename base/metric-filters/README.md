Add any
[metric filters](https://www.spinnaker.io/setup/monitoring/#configuring-metric-filters)
that should be mounted to `/opt/spinnaker-monitoring/filters` in the monitoring
daemon sidecar in this directory. Reference them in the
spinnaker-monitoring-filters `secretGenerator` entry in the root
kustomization.yml.

If migrating from Halyard, these filters belonged in the
`~/.hal/default/profiles/monitoring-daemon/filters`
directory.

# auto-expand-pvc
Expand Kubernetes PVC automatically as it reaches the capacity

The service monitors current PV disk usage with Prometheus query, and grows the PVC storage size value accordingy to the rule.

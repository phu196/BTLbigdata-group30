# Issue

# Set up Minikube

## Problem:
"""
    ❌  Exiting due to K8S_APISERVER_MISSING: wait 6m0s for node: wait for apiserver proc: apiserver process never appeared
"""
## Solution:
"""minikube start --extra-config=apiserver.authorization-mode=RBAC"""

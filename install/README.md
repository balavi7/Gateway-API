Install the gateway API CRDs and ENVOY gateway

Command:

helm install eg oci://docker.io/envoyproxy/gateway-helm --version v1.6.1 -n envoy-gateway-system --create-namespace
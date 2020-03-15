# KubeExtract

Utility to extract and decode all kubernetes secrets from a given namespace or all namespaces.

## Install
* `wget https://raw.githubusercontent.com/AloneShadow/kubeextract/master/kubeextract`
* `sudo mv kubeextract /usr/local/bin`
* `sudo chmod +x /usr/local/bin/kubeextract`

## Run
* `kubeextract` prints all available secrets from all namespaces
* `kubeextract <namespace_1> <namespace_2> ... <namespace_n>` prints secrets from given namespaces

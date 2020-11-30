# non-standard-epmd-port-E3RdkiS7S2A
https://groups.google.com/g/rabbitmq-users/c/E3RdkiS7S2A

# Starting nodes

```
RABBITMQ_CONF_ENV_FILE=/home/lbakken/issues/rabbitmq-users/non-standard-epmd-port-E3RdkiS7S2A/rabbit-1-env.conf RABBITMQ_ALLOW_INPUT=true LOG=debug ./sbin/rabbitmq-server
RABBITMQ_CONF_ENV_FILE=/home/lbakken/issues/rabbitmq-users/non-standard-epmd-port-E3RdkiS7S2A/rabbit-2-env.conf RABBITMQ_ALLOW_INPUT=true LOG=debug ./sbin/rabbitmq-server
```

# Cluster status

```
RABBITMQ_CONF_ENV_FILE=/home/lbakken/issues/rabbitmq-users/non-standard-epmd-port-E3RdkiS7S2A/rabbit-1-env.conf ./sbin/rabbitmqctl cluster_status
```

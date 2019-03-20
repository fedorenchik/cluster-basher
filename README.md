# cluster-basher

Crude cluster manager written in pure Bash script.

# How to use:

1. First setup ssh key based authorization for your cluster

2. Define CB_CLUSTER variable containing all your hosts (with optional user names), e.g. `CB_CLUSTER="user1@host1 user2@192.168.128.225 host3"`. Optionally, add this variable to `.cbrc` file, it will be sourced automatically.

3. Run `./cb <command>`, e.g. `./cb uptime`

% CONSUL(1) Service discovery and configuration tool
% HashiCorp <hello@hashicorp.com>
% 2016

# NAME

Consul - Service discovery and configuration tool

# SYNOPSIS

`consul` [--version] [--help] <command> [<args>]

# DESCRIPTION

Consul is a tool for service discovery and configuration. Consul is distributed, highly available, and extremely scalable. Consul provides several key features:

* Service Discovery - Consul makes it simple for services to register themselves and to discover other services via a DNS or HTTP interface. External services such as SaaS providers can be registered as well.

* Health Checking - Health Checking enables Consul to quickly alert operators about any issues in a cluster. The integration with service discovery prevents routing traffic to unhealthy hosts and enables service level circuit breakers.

* Key/Value Storage - A flexible key/value store enables storing dynamic configuration, feature flagging, coordination, leader election and more. The simple HTTP API makes it easy to use anywhere.

* Multi-Datacenter - Consul is built to be datacenter aware, and can support any number of regions without complex configuration.

# COMMANDS

* `agent`:
  Runs a Consul agent

* `configtest`:
  Validate config file

* `event`:
  Fire a new event

* `exec`:
  Executes a command on Consul nodes

* `force-leave`:
  Forces a member of the cluster to enter the "left" state

* `info`:
  Provides debugging information for operators

* `join`:
  Tell Consul agent to join cluster

* `keygen`:
  Generates a new encryption key

* `keyring`:
  Manages gossip layer encryption keys

* `kv`:
  Interact with the key-value store

* `leave`:
  Gracefully leaves the Consul cluster and shuts down

* `lock`:
  Execute a command holding a lock

* `maint`:
  Controls node or service maintenance mode

* `members`:
  Lists the members of a Consul cluster

* `monitor`:
  Stream logs from a Consul agent

* `operator`:
  Provides cluster-level tools for Consul operators

* `reload`:
  Triggers the agent to reload configuration files

* `rtt`:
  Estimates network round trip time between nodes

* `snapshot`:
  Saves, restores and inspects snapshots of Consul server state

* `version`:
  Prints the Consul version

* `watch`:
  Watch for changes in Consul

# OPTIONS

* `-h`, `--help`:
  Show this help message and exit

* `-v`, `--version`:
  Print Consul version and exit

# COPYRIGHT

Consul is subject to the terms of the Mozilla Public License, v. 2.0. (MPL-2.0)

# SEE ALSO

Consul online documentation is available on this website https://www.consul.io/docs/

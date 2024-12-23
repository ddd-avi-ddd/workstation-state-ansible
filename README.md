# Workstation State Collection System

Ansible-based system for collecting and versioning Windows workstation state information.

## Architecture
- Collects system metrics via WinRM
- Stores state snapshots
- Maintains version history
- Runs as K8s CronJob

## Setup
1. Configure inventory
2. Set credentials in Ansible vault
3. Test connectivity
4. Deploy K8s components

## Development
- Branch from develop
- PR review required
- Tests must pass

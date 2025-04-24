# Network Topologies
This directory contains containerlab topology definitions and initial configurations.

Each topology subdirectory follows this structure:
- `topology.yaml` - The containerlab topology definition
- `config/nodes/` - Initial device configurations
- `intent/` - Directory containing derived network intents

The workflow is:
1. Initial configurations are stored in `config/nodes/`
2. The Intent AI Agent parses these configurations to generate initial intents
3. Future intent changes are applied back to the devices

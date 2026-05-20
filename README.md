# fms-mavlink-agent

Public binary releases for the FMS MAVLink client agent.

`fms-mavlink-agent` connects MAVLink-compatible autopilots to FMS.  
Tested with ArduPilot. The binary inside release archives is named `fms-drone-agent`.

## Downloads

Download builds from GitHub Releases:

https://github.com/rhumb-fms/mavlink-client/releases

Each release contains:

- `manifest.json`
- platform archives, for example `fms-mavlink-agent-v0.2.0-linux-x86_64.tar.gz`
- `.sha256` checksum files

## Linux Example

```bash
tar xzf fms-mavlink-agent-v0.2.0-linux-x86_64.tar.gz
chmod +x fms-drone-agent
./fms-drone-agent --version

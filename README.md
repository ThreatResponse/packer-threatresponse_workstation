# packer-ThreatResponse

This packer file is used to build the publicly available AMIs for ThreatResponse Workstation.

Should you want to build your own you need only a boto profile on the system running packer.

If you're looking for an ansible play though to build a docker-compose host this one works pretty well!

## Running Packer

`packer build packer.json`

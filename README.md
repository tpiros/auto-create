Automatically Virtual Machine creation on an ESXi server

Usage: /bin/sh create.sh options: n <|c|i|r|s|N>


Where n: Name of VM (required), c: Number of virtual CPUs, i: location of an ISO image, r: RAM size in MB, s: Disk size in GB, N: Network name (may be specified multiple times)

Default values are: CPU: 2, RAM: 4096MB, HDD-SIZE: 20GB, no network connection

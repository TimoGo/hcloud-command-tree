# hcloud-command-tree
each hcloud command/subcommand a single directory


hcloud
├── certificate
│   ├── add-label
│   ├── create
│   ├── delete
│   ├── describe
│   ├── list
│   ├── remove-label
│   └── update
├── completion
│   ├── bash
│   ├── fish
│   ├── powershell
│   └── zsh
├── context
│   ├── active
│   ├── create
│   ├── delete
│   ├── list
│   └── use
├── datacenter
│   ├── describe
│   └── list
├── firewall
│   ├── add-label
│   ├── add-rule
│   ├── apply-to-resource
│   ├── create
│   ├── delete
│   ├── delete-rule
│   ├── describe
│   ├── list
│   ├── remove-from-resource
│   ├── remove-labels
│   ├── replace-rules
│   └── update
├── floating-ip
│   ├── add-label
│   ├── assign
│   ├── cloating-ip
│   ├── create
│   ├── delete
│   ├── describe
│   ├── disable-protection
│   ├── enable-protection
│   ├── list
│   ├── remove-label
│   ├── set-rdns
│   ├── unassign
│   └── update
├── help
├── image
│   ├── add-label
│   ├── delete
│   ├── describe
│   ├── disable-protection
│   ├── enable-protection
│   ├── list
│   ├── remove-label
│   └── update
├── iso
│   ├── describe
│   └── list
├── load-balancer
│   ├── add-label
│   ├── add-service
│   ├── add-target
│   ├── attach-to-network
│   ├── change-algorithm
│   ├── change-type
│   ├── create
│   ├── delete
│   ├── delete-service
│   ├── describe
│   ├── detach-from-network
│   ├── disable-protection
│   ├── disable-public-interface
│   ├── list
│   ├── metrics
│   ├── remove-label
│   ├── remove-target
│   ├── update
│   └── update-service
├── load-balancer-type
│   ├── describe
│   └── list
├── location
│   ├── describe
│   └── list
├── network
│   ├── add-label
│   ├── add-route
│   ├── add-subnet
│   ├── change-ip-range
│   ├── create
│   ├── delete
│   ├── describe
│   ├── disable-protection
│   ├── enable-protection
│   ├── list
│   ├── remove-label
│   ├── remove-route
│   ├── remove-subnet
│   └── update
├── server
│   ├── add-label
│   ├── attach-iso
│   ├── attach-to-network
│   ├── change-alias-ips
│   ├── change-type
│   ├── create
│   ├── create-image
│   ├── delete
│   ├── describe
│   ├── detach-from-network
│   ├── detach-iso
│   ├── disable-backup
│   ├── disable-protection
│   ├── disable-rescue
│   ├── enable-backup
│   ├── enable-protection
│   ├── enable-rescue
│   ├── ip
│   ├── list
│   ├── metrics
│   ├── poweroff
│   ├── poweron
│   ├── reboot
│   ├── rebuild
│   ├── remove-label
│   ├── request-console
│   ├── reset
│   ├── reset-password
│   ├── set-rdns
│   ├── shutdown
│   ├── ssh
│   └── update
├── server-type
│   ├── describe
│   └── list
├── ssh-key
│   ├── add-label
│   ├── create
│   ├── delete
│   ├── describe
│   ├── list
│   ├── remove-label
│   └── update
├── version
└── volume
    ├── add-label
    ├── attach
    ├── create
    ├── delete
    ├── describe
    ├── detach
    ├── disable-protection
    ├── enable-protection
    ├── list
    ├── remove-label
    ├── resize
    └── update

161 directories, 0 files

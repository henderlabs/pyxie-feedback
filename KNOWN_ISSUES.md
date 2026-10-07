# Known issues and roadmap

Kept short and updated with releases. Search the [open issues](../../issues) first.

## Known limitations
- Host bridge and VLAN configuration is read-only by design; PyXie only reassigns a workload's NIC VLAN.
- The `acme` certificate mode is a placeholder for a private ACME CA; there is no public Let's Encrypt mode yet.
- The Proxmox VM console clipboard needs `spice-vdagent` installed in the guest.

## Under consideration
- Public Let's Encrypt certificate mode
- Configurable update-check interval
- Re-reading live Proxmox state when building a maintenance plan

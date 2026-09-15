# Anvil Capture Compute Disclosure

Anvil Capture Compute is provided for $0 upfront in exchange for a small amount of unused computer processing capacity.

## What happens after activation

Only after the user explicitly accepts the Compute Agreement, Anvil Capture installs and manages a verified XMRig worker.

The worker mines Monero (XMR) for Anvil Interactive Solutions.

Users do not receive cryptocurrency or mining proceeds.

## Resource usage

Anvil Capture uses an adaptive resource governor.

During normal active computer use, Compute operates at a very low CPU budget.

After the computer remains idle, the permitted contribution may gradually increase, up to the configured maximum.

Compute pauses or reduces activity during demanding workloads.

## Transparency

The Compute worker:

- does not start before explicit consent
- is visible in Windows Task Manager
- does not attempt to bypass antivirus software
- does not install Defender exclusions
- stops when Anvil Capture exits
- can be revoked through Anvil Capture

## Security software

Because the Compute edition uses XMRig, some antivirus or security products may identify or block the Compute worker.

Anvil Capture does not attempt to bypass such security software.

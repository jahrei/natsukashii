# natsukashii
a Windows VM using KVM GPU passthrough, to take a travel to the past.

## Why?
replicating my old OS setup from 2015 with modern elements.
bring the past to the present to shape the future

the goal of _natsukashii_ is to provide compatibility and play older obscure games such as o2jam and other niche rhythm games.
it can, of course, also play more recent games.

## How?
using the power of GPU passthrough via VFIO and KVM, I am able to create a virtual machine passing through the GPU in order to achieve near native baremetal performance.


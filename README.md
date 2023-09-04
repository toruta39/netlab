# netlab

Manage QEMU virtual machine instances for a local lab setup on Macbook with Apple Silicon

## Usage

```sh
# Create a VM named ubuntu
./create ubuntu01

# Start the VM with installation media
./start ubuntu01 -iso images/ubuntu-22.04.3-live-server-arm64.iso

# Start a VM
./start ubuntu01

# Need privilege when using vmnet-shared network
sudo ./start ubuntu01
```

## Further on

[UTM](https://github.com/utmapp/UTM) offers better experience with running and managing QEMU instances on macOS


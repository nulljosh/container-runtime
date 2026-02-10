# Build Your Own Container Runtime

A minimal Linux container runtime — namespaces, cgroups, and filesystem isolation.

## Scope
- Linux namespaces (PID, mount, network, UTS)
- Cgroup resource limits (CPU, memory)
- Filesystem isolation with chroot/pivot_root
- Image unpacking (OCI/tarball)
- Simple CLI: `mycontainer run <image> <cmd>`
- Network setup with veth pairs (stretch goal)

## Learning Goals
- Linux namespaces and what "isolation" really means
- Cgroups v2 for resource control
- Mount namespaces and overlay filesystems
- How Docker/containerd actually work
- Systems programming with unsafe Rust + C FFI
- Security boundaries and capabilities

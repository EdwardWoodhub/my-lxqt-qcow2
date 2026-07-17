# Install Fedoar CoreOS on VPS

```
# 使用上传完毕的fedora-coreos-44.20260621.3.1-openstack.x86_64.qcow2
```


# Rebase to uCore

```
# 跳过;直接rebase到自定义镜像
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/ublue-os/ucore:stable
```

# Rebase to my LXQt blue-build-image

```
sudo rpm-ostree rebase ostree-unverified-registry:ghcr.io/edwardwoodhub/my-lxqt-qcow2:latest

```

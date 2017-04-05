# CentOS 7 Systemd

This is a small docker container image that has a running systemd init system.


[![Docker Repository on Quay](https://quay.io/repository/keaosolutions/centos-systemd/status "Docker Repository on Quay")](https://quay.io/repository/keaosolutions/centos-systemd)

### Note ###

If you need to run boot actions outside of systemd then these should be done by creating an *rc.local* script that has execute permissions and is placed inside /etc/rc.d/

# dnsmasq-munin
A Munin dnsmasq plugin for monitoring forwared, cached and blocked queries.

# How to install
 - Symlink dnsmasq script to your Munin plugin folder `sudo ln -s /home/user/dnsmasq-munin/dnsmasq /etc/munin/plugins/dnsmasq`
 - Restart Munin-node `sudo service munin-node restart`

The default dnsmasq log file location is: `/var/log/dnsmasq.log`
To change this you should edit your Munin plugin configuration override file `/etc/munin/plugin-conf.d/munin-node`

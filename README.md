# pihole-cli

Pihole CLI to add and edit local dns and cname


# Use

## Set Pihole custom list and custom cname path

by default the path to the custom list is: `/etc/pihole/custom.list`
And for custom cname is: `/etc/dnsmasq.d/05-pihole-custom-cname.conf`

Now, you need to set these two paths in two environment variables, `DNS_PATH` for custom list and `CNAME_PATH` for custom cname

```bash
export DNS_PATH='/etc/pihole/custom.list'
export CNAME_PATH='/etc/dnsmasq.d/05-pihole-custom-cname.conf'
```

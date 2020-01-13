# Lark IT Ansible NTP Role

Install and configures ntpd

## Operating Systems
This role is known to work on the following operating systems:
- CentOS 7

## Dependencies
geerlingguy.ntp (https://galaxy.ansible.com/geerlingguy/ntp)

## Variables

| Variable | Default Value | Type | Destcription |
|----------|---------------|------|--------|
| ntp_timeszone | America/Denver | String | NTP Timezone (tz) |
| ntp_manage_config | True | Boolean | whether or not to manage ntpd configuration |
| ntp_area | us | String | [NTP Pool Area](http://support.ntp.org/bin/view/Servers/NTPPoolServers) |
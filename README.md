# Lark IT Ansible NTP Role

Install and configure ntpd

## Operating Systems
This role is known to work on the following operating systems:
- CentOS 7

## Dependencies
This role depends on the following Ansible Galaxy roles:
- geerlingguy.ntp (https://galaxy.ansible.com/geerlingguy/ntp)

## Variables

| Variable | Default Value | Type | Description |
|----------|---------------|------|--------|
| ntp_timeszone | America/Denver | String | NTP Timezone (tz) |
| ntp_manage_config | True | Boolean | Whether or not to manage ntpd configuration |
| ntp_area | us | String | [NTP Pool Area](http://support.ntp.org/bin/view/Servers/NTPPoolServers) |
# ansible-time

Ansible role to configure `systemd-timesyncd.serivce`.

## Role Variables

| Name                      | Default               | Description                                         |
|---------------------------|:---------------------:|-----------------------------------------------------|
| `time_timezone`           | `Etc/UTC`             | Timezone to set (relative to `/usr/share/zoneinfo`) |
| `time_ntp_hosts`          | `{0,1}.pool.ntp.org`  | Array of NTP hosts                                  |
| `time_fallback_ntp_hosts` | `{2,3}.pool.ntp.org`  | Array of fallback NTP hosts                         |

## Other

Adapted from: https://github.com/stuvusIT/systemd-timesyncd

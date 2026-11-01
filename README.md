# PersonalDNSLists

Personal DNS blacklist / whitelist, subscribed by AdGuard Home (home routers and the VPS):

| List | AdGuard Home | URL |
|---|---|---|
| `blacklist.txt` | Filters → DNS blocklists | https://raw.githubusercontent.com/OMGJL/PersonalDNSLists/main/blacklist.txt |
| `whitelist.txt` | Filters → DNS allowlists | https://raw.githubusercontent.com/OMGJL/PersonalDNSLists/main/whitelist.txt |

AdGuard Home re-downloads both every 24 h (Settings → General → filter update interval),
or at once with "Check for updates" on the Filters page.

Router-specific rules (e.g. `$client=` rules tied to a subnet) stay in each router's custom rules.

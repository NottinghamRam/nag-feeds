# nag-feeds

Daily vehicle inventory feeds for Google Merchant Center.

| Store | File | Merchant Center fetch link |
|---|---|---|
| Sulphur Springs Dodge | `ss.tsv` | https://raw.githubusercontent.com/NottinghamRam/nag-feeds/main/ss.tsv |
| Bonham Chrysler | `bon.tsv` | https://raw.githubusercontent.com/NottinghamRam/nag-feeds/main/bon.tsv |

Holds only the public inventory already shown on ssdodge.com and bonhamchrysler.com. No code, no customer data, no passwords.
Built by `feeds/build_feed.py` in the private nag-platform repo and refreshed every morning. `status.txt` shows the last refresh.

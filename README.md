Alpine Tor Client
=================

- Built on alpine 3.2
- Small image size (less than 22MB)
- Auto refreshes IP every 30 seconds
- Makes sure internal clock is up-to-date before starting client


Usage
-----

```bash
docker run --rm -p 9150:9150 chive/tor
```

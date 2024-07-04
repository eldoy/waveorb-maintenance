# waveorb-maintenance
Waveorb maintenance

Find large files and create issue based on that?

`find / -type f -size +200M -exec du -h {} + 2>/dev/null | sort -r -h`

Do logrotate to avoid disk filling up.

`touch /var/mongod/mongod.log`

Created by [Eldøy Projects](https://eldoy.com)

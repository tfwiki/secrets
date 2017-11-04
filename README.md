Team Fortress Wiki Secrets
==========================

This is a [blackbox](https://github.com/StackExchange/blackbox) powered repository used to store senstive data for the Team Fortress Wiki project, such as:

* Passwords
* Service credentials
* API keys

See the blackbox repository for information on encrypting files, editing encrypted files, and managing access control.

## Treat access removals as credential exposure

There is no way to retroactively remove access to encrypted files in the repository's history, and even if there were — those files will still be on others' machines, and may have been copied prior to access removal.

When anybody's access to this repository is revoked, all credentials should be cycled and depending services redeployed ASAP.
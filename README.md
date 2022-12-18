# backup-remote

## Install

1. Clone repo.
2. Edit `backup-remote.conf.json`.
3. Install `jq`.
4. Install [json-conf](https://github.com/shatfel/json-conf).

## Usage

```sh
[debug=0|false|1|true] [cmd="rm-status"] [config=path to config.conf.json|/usr/local/etc/backup-remote.conf.json] backup-remote
```

1. If `debug` not false, print config params used.
2. `cmd="rm-status"` force remove status file.
3. `config` is path to config file or use default `/usr/local/etc/backup-remote.conf.js`.
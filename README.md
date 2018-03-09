This is actually just something I created for my self to quickly, and sort of manually sync/backup vital directories between my dedicated servers.

This script will allow you, after being set up, to rsync from remote to local with a simple command such as "qsync /website /backup/". This would pull the /website directory from the remote server, and put it in /backup on the local server. After completion, it will send you a notification if successful.

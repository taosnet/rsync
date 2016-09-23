## Description

Simple image to allow rysnc on the host. By default, uses "-a /source /dest" as arguments.

## Usage

Run the images as if it were installed on the local machine.
```
docker run --name webbackup --volumes-from=mydomain -v /backup/mydomain:/dest:Z taosnet/rsync -av /var/www/domain /dest
```

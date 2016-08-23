## Description

Simple container to allow rysnc. By default, uses "-a /source /dest" as arguments.

## Usage

  1. Run the container as if it were an rsync command with the appropiate volumes:
         ```
         docker run --name webbackup --volumes-from=mydomain -v /backup/mydomain:/dest:Z taosnet/rsync -av /var/www/domain /dest
         ```

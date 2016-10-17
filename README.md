influx-backup
=========

Simple backup role based on https://github.com/evanrich/influx2S3 script

Role Variables
--------------

```
influx_db_name: database_name
backup_path: '/var/tmp/restore/'
influx_data_dir: "/var/lib/influxdb/data"
influx_meta_dir: "/var/lib/influxdb/meta"
backup_backet: "aws backet"
access_key_id: "your key"
secret_key: "your secret"
upload_folder: "influxdb"
```


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: alekseenkoss77.influx-backup }

License
-------

GPLv2


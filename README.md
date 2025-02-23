Install and configure arrs
=========

The role installs and configures the arrs services on my server.

Role Variables
--------------

The ```arrs_media_owner``` variable is used to set the owner of the media files.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: tychobrouwer.arrs

    - role: tychobrouwer.arrs
      arrs_media_owner: media
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

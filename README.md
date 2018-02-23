protobuf-install
================

Install Google Protocol Buffers compiler.

Requirements
------------

None.

Role Variables
--------------

protoc_checksum: Checksum for Google protocol buffers compiler binary.
protobuf_version: Version of Google protocol buffers to install.

Dependencies
------------

None.

Example Playbook
----------------

None.

    - hosts: servers
      roles:
         - role: lfit.protobuf-install
           protobuf_version: 3.5.1
           protoc_checksum: sha256:cd40f10bcdaff36429ec4652210f2bb8d6c7349e7b78f3a38ef42168401d7285

License
-------

MIT

Author Information
------------------

Linux Foundation Release Engineering

# trusted_facts
example for OID mapping and trusted facts

csr_attributes.yaml
This file would be part of the puppet agent environment upon install. It is placed in the windows agent n the directory as
shown within the repo.. Another option would be to include as command line parameters with the puppet agent install.

custom_trusted_oid_mapping.yaml
This file resides on the puppet master and will be build a map of OID's to a shortname that can be used as part of the
facts and pupept code.

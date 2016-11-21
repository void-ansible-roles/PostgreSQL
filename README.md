PostgreSQL
==========


What is does this role do?
--------------------------

Installs `postgresql`, `python-psycopg2` so PostgreSQL can be managed via Ansible,
and `acl-prog` to allow Ansible to become the `postgres` user 


Meta
----

Files Managed:
  * /etc/sv/postgresql
  * /var/service/postgresql

Defaults Provided:
  * None

Variables Required:
  * None

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None

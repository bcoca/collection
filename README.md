Collection template
-------------------
-------------------

* roles: directory for ansible roles
* plugins: all ansible plugins and modules go here, each in its own subdir
  * modules: ansible modules
  * lookups: lookup plugins
  * filters: Jinja2 filter plugins
  ...
* playbooks: playbooks reside here
* galaxy.yml: source data for the MANIFEST.json that will be part of the collection package

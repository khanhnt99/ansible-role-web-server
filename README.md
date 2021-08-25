# ansible-role-web-server
Tìm hiểu cách cấu hình Role cho web-server

- `defaults`: This directory lets you set default variables for included or dependent roles. Any defaults set here can be overridden in playbooks or inventory files.
- `files`: This directory contains static files and script files thatmight be copied to or executed on a remote server.
- `handlers`: All handlers that were in your playbook previously can nowbe added into this directory.
- `meta`: This directory is reserved for role metadata, typically used fordependency management.. For example, you can define a list of rolesthat must be applied before the current role is invoked.
- `templates`: This directory is reserved for templates that will generatefiles on remote hosts. Templates typically use variables defined onfiles located in the vars directory, and on host information that iscollected at runtime.
- `tasks`: This directory contains one or more files with tasks that wouldnormally be defined in the tasks section of a regular Ansibleplaybook. These tasks can directly reference files and templatescontained in their respective directories within the role, without theneed to provide a full path to the file.
- `vars`: Variables for a role can be specified in files inside thisdirectory and then referenced elsewhere in a role.


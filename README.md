# This Repository is ansible-playbook for the prometheus install.
This Repository include prometheus and node_exporter install playbook.

If you want prometheus install, please run "ansible-playbook main.yml"
Also, you have to change prometheus ip address in prometheus part of hosts file.

And Then If you want node_exporter install on other node, you have to change node_exporter ip address in node_exporter part of hosts file. 
and plz run "ansible-playbook node-exporter-main.yaml"



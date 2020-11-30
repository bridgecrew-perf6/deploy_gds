# Deploy Get Datetime Server

For [https://github.com/jim1406g/get_datetime_server.git](https://github.com/jim1406g/get_datetime_server.git)

1. Install **Docker**
2. Build docker image and install **Get Datetime Server**

You must have **sudo** on the remote host.

Example:

```bash
ansible-playbook -u username -i groups/gds_hosts.yml play/deploy_gds.yml
```
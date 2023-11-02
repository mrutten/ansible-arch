# Example host vars

Below is an example inventory/host_vars/localhost file. Replace with appropriate values for your environment.

```yaml
---
ansible_user: <ANSIBLE_USER>
ansible_ssh_private_key_file: ~/.ssh/<PRIVATE_KEY>
ansible_remote_tmp: <TMP_DIRECTORY>

# Code-OSS
user: <USERNAME>
group: <GROUPNAME>
settings_path: "/home/<USERNAME>/.config/Code - OSS/User/settings.json"
```
## Ansible Tricks and Tips

Make sure target(s) has the public SSH key of the controller (AWX) machine installed + python/python3 installed.

```
ssh root@target
nano ~/.ssh/authorized_keys 
```
Add awx pub key

# hello_world role

This is a demonstration readme file

this role just prints out a debug task

```
---
- name: print hello world
  debug:
    msg: "Hello Ansible Collection!"
```

the role is called `hello_world` and can be included in an Ansible Playbook:

```
- include_role:
    name: hello_world
```

## author

Sean Cavanaugh, seanc@redhat.com

### ping
sh ```
ansible frontends -i hosts -m ping
```

### gather and return "facts" about your target hosts
sh ```
ansible frontend01.example.com -m setup -a "filter=ansible_distribution*"
```

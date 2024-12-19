## Note

* make sure you create the `acme.json` file first and then change the proper permission for it 
```bash 
chmod 600 data/acme.json
```

*** 
On the cloudflare side , you should check the SSL/TLS encryption to be `full` instead of `full(strict)` , otherwise it won't work
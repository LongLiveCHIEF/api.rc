# api.rc
Manage your api accesses using a native system tool

Configure and manage your personal tokens and api access services

## Example

Need to provide your *Digital Ocean* api token to `docker-machine`?  Easy!

```bash
docker-machine create --driver digitalocean --digitalocean-access-token=$(api get --token digitalocean)
```


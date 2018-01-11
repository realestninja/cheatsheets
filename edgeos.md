## Change Config
```
configure
<COMMAND TO EXECUTE 1>
<COMMAND TO EXECUTE 2>
<COMMAND TO EXECUTE 3...>
commit
save
exit
```

## ssh
#### Disable password-based auth
```
set service ssh disable-password-authentication
```

#### Install public key
```
# Copy public key to the router (e.g. in /tmp/blah.pub), then do:
loadkey <USERNAME> <PATH_TO_PUBLIC_KEY>
```

## show
#### List user info
```
show system login user <USERNAME>
```

#### List interfaces
```
show interfaces
```
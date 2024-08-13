# docker-openvpn
docker-compose openvpn

## clone 

```
git clone https://github.com/wachira90/docker-openvpn.git
```

## command control

```
docker-compose up -d

docker-compose ps

docker-compose stop

docker-compose start
```

##  download client config

```
https://localhost
```

## admin manage

```
https://localhost:943
```

## login 

```
user: openvpn 
pass: < find in log >


openvpn-as  | Initializing OpenVPN...
openvpn-as  | Removing Cluster Admin user login...
openvpn-as  | Writing as configuration file...
openvpn-as  | Perform sa init...
openvpn-as  | Wiping any previous userdb...
openvpn-as  | Creating default profile...
openvpn-as  | Modifying default profile...
openvpn-as  | Adding new user to userdb...
openvpn-as  | Modifying new user as superuser in userdb...
openvpn-as  | Auto-generated pass = "OkXQOtK7Ipq2". Setting in db...
openvpn-as  | Getting hostname...
openvpn-as  | Hostname: cfde4b23e18c
openvpn-as  | Preparing web certificates...
openvpn-as  | Getting web user account...
openvpn-as  | Adding web group account...
openvpn-as  | Adding web group...
openvpn-as  | Adjusting license directory ownership...
openvpn-as  | Initializing confdb...
openvpn-as  | Initial version is not set. Setting it to 2.14.0...
openvpn-as  | Generating PAM config for openvpnas ...
openvpn-as  | Enabling service
openvpn-as  | + touch /openvpn/etc/docker-init
openvpn-as  | + exec /usr/local/openvpn_as/scripts/openvpnas --nodaemon
```

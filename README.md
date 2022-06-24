# systemd-services
Custom systemd services for various binaries

## wireguard
### Install
copy wireguard@.service to `/etc/systemd/system/wireguard@.service`

copy wireguard@.path to `/etc/systemd/system/wireguard@.path`

### Usage
```bash
sudo systemctl enable wireguard@wg0.service
sudo systemctl start wireguard@wg0.service
```

Replace wg0 with your wireguard interface of choice, or if you have more than one

```bash
sudo systemctl enable wireguard@wg{0..3}.{service,path}
sudo systemctl start wireguard@wg{0..3}.service
```

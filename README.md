# systemd-services
Custom systemd services for various binaries

## [wireguard@.service](wireguard@.service)
### Install
copy to `/etc/systemd/system/wireguard@.service`

### Usage
```bash
sudo systemctl enable wireguard@wg0.service
sudo systemctl start wireguard@wg0.service
```

Replace wg0 with your wireguard interface of choice

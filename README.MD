### Ansible stuff

run ansible locally

`ansible-playbook -i localhost jumphost.yml`

### after a previous run and need to re-run?

delete stuff:

`rm -rf ./configs`
`rm -rf /etc/wireguard`

recreate wireguard dir otherwise touch error

`mkdir -p /etc/wireguard`

## MOL-MNT

This is the `DN42` part of MolMoe Network.

The DN42 subnet is organized with ZeroTier.

Knowing nothing about DN42? [Read this page.](https://lantian.pub/article/modify-website/dn42-experimental-network-2020.lantian/)

MolMoe Network (DN42) details:

 - ASN: `4242420603`
 - DN42 IPv4: `172.23.7.64/26`, `172.23.7.128/27`
 - DN42 IPv6: `fdcf:fabc:3c41::/48`
 - Domain: `mol.dn42`
 - WireGuard Port: Last 5 digits of your ASN

## Peering

Automatic peering is available on some nodes with ASN which begins with `424242`.

For peering with other nodes, please send the following information to `dn42@mol.moe` or `@TheresaJune(Telegram)`. I will reply immediately after receiving your request and configuring properly.

 - Your DN42 ASN
 - Your node's clearnet IP
 - Your node's DN42 IPv4 addresses (for IPv4 peering)
 - Your node's Link-local address (for IPv6 peering)
 - The node you would like to peer

For Wireguard peering, you may provide the following information additionally:

 - Your node's WireGuard public key

For ZeroTier peering, you may provide the following information additionally:

 - Your ZeroTier Network ID

OpenVPN or other methods are not supported.

## Servers

You may check server status on [MolMoe Network Status Page](https://status.mol.moe/).

### HK02
 - Automatic Peering: [@molmoe42_bot on Telegram](https://t.me/molmoe42_bot)
 - Endpoint: `(hidden):(last 5 digits of your ASN)`
 - Clearnet IPv4: `(hidden)`
 - Clearnet IPv6: `(hidden)`
 - DN42 IPv4: `172.23.7.65`
 - DN42 IPv6: `fdcf:fabc:3c41::1`
 - Link-local IPv6: `fe80::603`
 - WireGuard public key: `wNNbJyoFBrlpq53p61Ur8V2RNfS3U7KADlK7he64qRk=`
 - DN42 Name: `hk02.mol.dn42`

### CER01
 - Automatic Peering: [@molmoe_cer01_bot on Telegram](https://t.me/molmoe_cer01_bot)
 - Endpoint: `(Hidden)`
 - Clearnet IPv6: `(Hidden)`
 - DN42 IPv4: `172.23.7.69`
 - DN42 IPv6: `fdcf:fabc:3c41::12`
 - Link-local IPv6: `fe80::603`
 - WireGuard public key: `7PAPZ0LjGZ0nUu0pCKdtEFjLbeONga8TJUlxhn/45VQ=`
 - DN42 Name: `cer01.mol.dn42`

Peers for CERxx should have a CERNET IPv6 address. IPv4 peering not supported due to NAT.

If you want to peer with this server, send request to me for details.

### SH01 (Private)

Details are hidden.

Due to known issues, this node is not available for initiative peering.

## Services

### httpbin.org

URL: `http://172.23.7.65:8080`

Thanks to `httpbin.org` for their effort.

### E-mail

URL: `https://mail.mol.dn42/`

My E-mail: `i@mol.dn42`

### MTProxy

URL: `https://t.me/proxy?server=mtproxy.mol.dn42&port=8443&secret=fa305a8c5032baf7b3ba6741579556f4`

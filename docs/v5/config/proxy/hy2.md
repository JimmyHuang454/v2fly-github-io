# Hysteria2

## Hysteria2 入站

inbound.hysteria2

无配置

## Hysteria2 出站

outbound.hysteria2

> `address`: string

服务器地址，支持 IP 地址或者域名。

> `port`: number

服务器端口号。

## Hysteria2 兼容

若要使用与[官方版](https://hysteria.network/)兼容的 Hysteria2，请把传输层也设置成 Hysteria2，并设置密码

:::tip
配置 TLS 时，可以使用 allowInsecure 和系统根证书，暂不支持自签证书和 PinnedPeerCertificateChainSha256

若不配置 TLS，则默认使用 allowInsecure
:::

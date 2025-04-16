# SzyOS
Iso: https://gofile.io/d/BPE46x
# setting the network up:
`ip addr add 10.0.2.15/24 dev eth0`
`ip link set eth0 up`
`ip route add default via 10.0.2.2 dev eth0`
# setting the apk.static package manager up:
`apk.static --initdb add`
# to install packages:
` apk.static --allow-untrusted add git/packagename`

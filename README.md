<h1 align="center">Bitcoin Full Node Kurulumu </h1>

<img src="https://media.giphy.com/media/vYMEkIhgfi7ooOFlkA/giphy.gif" width="800" height="400">

# Selamlar, bu repo kısaca bitcoin Full node kurulumu.

## Gereksinimler:

* Bunun hakkında bilgi bulamadım, kendimde test ettim.

```
2 vCPU
2 GB RAM
400 GB SSD
```
## Full node kurmak için:

* Uzun bir rehber yerine bitnodes'in scriptini tercih ettim.
* Altta ki komutu çalıştırarak full node'unuzu kurabilirsiniz.

```
curl https://bitnodes.io/install-full-node.sh | sh
```

## Logları izlemek için:
```
tail -f /root/bitcoin-core/.bitcoin/debug.log
```

![image](https://user-images.githubusercontent.com/101149671/184448757-fd5ef32e-212b-4d94-abdb-6967bd0a1627.png)

## Güncel blok 749,176, kullandığım [Explorer Linki](https://explorer.btc.com/btc/blocks)

## Durdurmak için:
```
cd /root/bitcoin-core/bin && ./stop.sh
```
## Kaldırmak için:
```
./install-full-node.sh -u
```

## Kısa bilgi:

* Aktif node sayısı: 13367
* Full node tutan: 12021
* Prunning yapan nodelar: 1278



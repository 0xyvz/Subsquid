# Subsquid


### Donanım konusu şimdilik [Sentiment](https://github.com/ruesandora/santiment) ile aynı. 

#

> Hala başvurmayanlar için [buradan](https://subsquid.deform.cc/testnetnodeapplication/).

> Sonra [buraya](https://app.subsquid.io/squids/deploy) giriyoruz, mail cüzdan ne varsa başvuru yaparken onu bağlıyoruz.

> Komutlar zaten mevcut ama yinede özetle;

```console
sudo apt update -y && sudo apt upgrade -y
apt install npm
```

> 1- Daha sonra subsquid panelinde ki komutları `sırasıyla` kullanıyorsunuz

> 2- `Set up your squid` kısmına gelince kücük harflerle `isim` belirliyorsunuz

> 3- `Blockchain Type` seçiyorsunuz ve komutu giriyorsunuz. (Type tercihi size bağlı farklılık iyi olabilir idk.)

> 4- `Deploy` ediyoruz ve `sync` oluyoruz.


SYNC SIKINTISI YAŞAYANLAR İÇİN RPC DEĞİŞİMİ
> 1- [Buradan](https://dashboard.alchemy.com/apps) üyelik oluşturuyoruz ve sağ üstte create new app diyip ETH mainnette kendi RPCmizi oluşturuyoruz. Ve RPC linkimizi hazırda tutuyoruz.

> 2- Daha sonra Winscp ile `(deploy adımız)/src/processor.ts` isimli klasörü bulup içerisinde yer alan chain kısmını oluşturduğumuz RPC ile değiştiriyoruz.

> 3- Son olarak terminalde `sqd deploy --org isminiz ./isminiz` kodu ile deploy edin. Ve iki defa Yes diyin. Bu kadar

### Devamı çok yakında..


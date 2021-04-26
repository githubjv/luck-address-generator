# Luck Address Generator

Generated keys and addresses can be used in the Luck Coin Project : [lucknet.club](https://lucknet.club)

**Compilation**
```
javac LuckAddressGenerator.java
```

**Usage**
```
usage : java LuckAddressGenerator [option]
Options :
        -pass : generate address from pass phrase (default)
        -pk : generate address from private key
        -r : generate random 256-bit private key
        -h : print this help
```
**Generate random address**


```
> $ java LuckAddressGenerator -r
> Private Key : aea84b3c90650f3665d5d6f1f6ba83e4bc7263996de4afd0f712e39d2c99df3f
> Luck Address: 0x0af50c8f3604342a386e7bcde52b24789a3301d68fd88fe5fa
```


**Generate address from passphrase**

```
> $ java LuckAddressGenerator -pass
> PassPhrase : this is a password !
> Private Key : 536683a1283d8c2d9367dd9234a190bba1eac7d818ba9dc74691e108755ab67c
> Luck Address: 0xfc33a0e5c718f69ec23685e72271c4e273f409048e4abe4174
```


**Generate address form private key**
```
> $ java LuckAddressGenerator -pk
> Private Key : aea84b3c90650f3665d5d6f1f6ba83e4bc7263996de4afd0f712e39d2c99df3f
> Luck Address: 0x0af50c8f3604342a386e7bcde52b24789a3301d68fd88fe5fa
```


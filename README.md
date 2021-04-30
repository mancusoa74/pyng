# pyng

Tool per inviare un frame ethernet con un payload testuale

## Requisiti

- Linux
- Python 3.6 o superiore

## Utilizzo

### Server

```
sudo ./pyngd <nome interfaccia ethernet di ricezione>
```

### Client

```
sudo ./pyng <indirizzo MAC di destinazione aa:bb:cc:dd:ee:ff:gg> <nome interfacce ethernet di trasmissione> <messaggio testuale>
```

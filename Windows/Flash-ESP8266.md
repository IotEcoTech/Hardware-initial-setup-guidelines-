### Install esptool package first
```
pip install esptool
```

### Etase Fkash memory of the ESP8266
```
esptool erase_flash
```

```
esptool --port COM5 write_flash -fs 4MB -ff 40m -fm dio 0x00000 C:\Users\karth\Downloads\firmware.bin
```

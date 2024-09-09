# rn-usb-serial

This library is for usb serial port communication on android platform.
This module uses the [felHR85/UsbSerial](https://github.com/felHR85/UsbSerial) library.

## Forked from [melihyarikkaya/react-native-serialport](https://github.com/melihyarikkaya/react-native-serialport)

This fork is intended to update the react native version & gradle dependencies to the latest versions.

### Documents

1. [Installation](https://github.com/mbm1607/rn-usb-serial/wiki/Installation)
2. [Auto Connection](https://github.com/mbm1607/rn-usb-serial/wiki/Auto-Connection)
3. [Manual Connection](https://github.com/mbm1607/rn-usb-serial/wiki/Manual-Connection)
4. [Methods](https://github.com/mbm1607/rn-usb-serial/wiki/Methods)
5. [Error Descriptions](https://github.com/mbm1607/rn-usb-serial/wiki/Error-Descriptions)

### Use to write data to port

```javascript
RNSerialport.writeString('HELLO');
RNSerialport.writeBase64('SEVMTE8=');
RNSerialport.writeHexString('48454C4C4F');
```

### DEFAULT DEFINITIONS

| KEY                    | VALUE                                    |
| ---------------------- | ---------------------------------------- |
| RETURNED DATA TYPE     | INT ARRAY (Options: INTARRAY, HEXSTRING) |
| BAUD RATE              | 9600                                     |
| AUTO CONNECT BAUD RATE | 9600                                     |
| PORT INTERFACE         | -1                                       |
| DATA BIT               | 8                                        |
| STOP BIT               | 1                                        |
| PARITY                 | NONE                                     |
| FLOW CONTROL           | OFF                                      |
| DRIVER                 | AUTO                                     |

### Java Package Name

`com.mbm1607.rnserialport`

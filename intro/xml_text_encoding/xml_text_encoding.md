 La diferencia entre un conjunto de caracteres (character set) y la codificación del texto (text enconding) es que el primero hace referencia al conjunto de caracteres que se pueden utilizar, mientras que el segundo hace referencia al manera en la que se guardan estos caracteres en memoria.
 

|  Nombre de archivo |   codificación| byte 1  | byte 2  | byte 3  | byte 4 | byte 5  | byte 6  |byte 7 | byte 8| byte 9| byte 10|byte 11 |byte 12|byte 13|byte 14|
|---|---|---|---|---| --- |---   |---   |-- | --|-- |-- |-- |--|--|--|
|  1.txt | ANSI  | 63  |E1   |F1   |61  |6D   |GF   | | | | | ||||
|  2.txt | UTF-8  | EF  | BB  | BF  | 63 | C3  |A1   | | | | | ||||
|  3.txt | UCS-2 Big Endian  | FE  |FF   | 00  | 63 | 00  |E1   |00|F1 |00 |61 | 00| 6D| 00|6F |
|  4.txt |  UCS-2 Little Endian |  FF |FE   |63   |00  | E1  | 00  |F1 | 00|61 | 00| 6D| 00|6F |00 |
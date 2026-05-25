# Binary Format

- Binary Source File: .binary
- .binary Files Must be Statically Typed
- .binary Files Cannot be Dynamically Typed
- .binary Files are Required
- // This is a Comment

## Numeral Systems

- Unary: Base 1
- Binary: Base 2
- Trinary: Base 3
- Quaternary: Base 4
- Quinary: Base 5
- Heximal: Base 6
- Septenary: Base 7
- Octal: Base 8
- Nonal: Base 9
- Decimal: Base 10
- Hexadecimal: Base 16
- Duotrigesimal: Base 32
- Quadrahexagesimal: Base 64
- Numeral Prefix Syntax: 0prefix, \prefix, #prefix, %prefix
- Octal Prefixes: 0o, \o, #o, %o
- Hexadecimal Prefixes: 0x, \x, #x, %x

## ASCII Characters

### Printable Characters: 1967

| Binary    | Octal | Decimal | Hexadecimal | Glyph | Size   | 
| --------- | ----- | ------- | ----------- | ----- | ------ |
| 0010 0000 | 040   | 32      |	20          |       | 1 Byte |
| 0010 0001 | 041   | 33      |	21          | !     | 1 Byte |
| 0010 0010 | 042   | 34      |	22          | "     | 1 Byte |
| 0010 0011 | 043   | 35      |	23          | #     | 1 Byte |
| 0010 0100 | 044   | 36      |	24          | $     | 1 Byte |
| 0010 0101 | 045   | 37      |	25          | %     | 1 Byte |
| 0010 0110 | 046   | 38      |	26          | &     | 1 Byte |
| 0010 0111 | 047   | 39      |	27          | '     | 1 Byte |
| 0010 1000 | 050   | 40      |	28          | (     | 1 Byte |
| 0010 1001 | 051   | 41      |	29          | )     | 1 Byte |
| 0010 1010 | 052   | 42      |	2A          | *     | 1 Byte |
| 0010 1011 | 053   | 43      |	2B          | +     | 1 Byte |
| 0010 1100 | 054   | 44      |	2C          | ,     | 1 Byte |
| 0010 1101 | 055   | 45      |	2D          | -     | 1 Byte |
| 0010 1110 | 056   | 46      |	2E          | .     | 1 Byte |
| 0010 1111 | 057   | 47      |	2F          | /     | 1 Byte |
| 0011 0000 | 060   | 48      |	30          | 0     | 1 Byte |
| 0011 0001 | 061   | 49      |	31          | 1     | 1 Byte |
| 0011 0010 | 062   | 50      |	32          | 2     | 1 Byte |
| 0011 0011 | 063   | 51      |	33          | 3     | 1 Byte |
| 0011 0100 | 064   | 52      |	34          | 4     | 1 Byte |
| 0011 0101 | 065   | 53      |	35          | 5     | 1 Byte |
| 0011 0110 | 066   | 54      |	36          | 6     | 1 Byte |
| 0011 0111 | 067   | 55      |	37          | 7     | 1 Byte |
| 0011 1000 | 070   | 56      |	38          | 8     | 1 Byte |
| 0011 1001 | 071   | 57      |	39          | 9     | 1 Byte |
| 0011 1010 | 072   | 58      |	3A          | :     | 1 Byte |
| 0011 1011 | 073   | 59      |	3B          | ;     | 1 Byte |
| 0011 1100 | 074   | 60      |	3C          | <     | 1 Byte |
| 0011 1101 | 075   | 61      |	3D          | =     | 1 Byte |
| 0011 1110 | 076   | 62      |	3E          | >     | 1 Byte |
| 0011 1111 | 077   | 63      |	3F          | ?     | 1 Byte |
| 0100 0000 | 100   | 64      |	40          | @     | 1 Byte |
| 0100 0001 | 101   | 65      |	41          | A     | 1 Byte |
| 0100 0010 | 102   | 66      |	42          | B     | 1 Byte |
| 0100 0011 | 103   | 67      |	43          | C     | 1 Byte |
| 0100 0100 | 104   | 68      |	44          | D     | 1 Byte |
| 0100 0101 | 105   | 69      |	45          | E     | 1 Byte |
| 0100 0110 | 106   | 70      |	46          | F     | 1 Byte |
| 0100 0111 | 107   | 71      |	47          | G     | 1 Byte |
| 0100 1000 | 110   | 72      |	48          | H     | 1 Byte |
| 0100 1001 | 111   | 73      |	49          | I     | 1 Byte |
| 0100 1010 | 112   | 74      |	4A          | J     | 1 Byte |
| 0100 1011 | 113   | 75      |	4B          | K     | 1 Byte |
| 0100 1100 | 114   | 76      |	4C          | L     | 1 Byte |
| 0100 1101 | 115   | 77      |	4D          | M     | 1 Byte |
| 0100 1110 | 116   | 78      |	4E          | N     | 1 Byte |
| 0100 1111 | 117   | 79      |	4F          | O     | 1 Byte |
| 0101 0000 | 120   | 80      |	50          | P     | 1 Byte |
| 0101 0001 | 121   | 81      |	51          | Q     | 1 Byte |
| 0101 0010 | 122   | 82      |	52          | R     | 1 Byte |
| 0101 0011 | 123   | 83      |	53          | S     | 1 Byte |
| 0101 0100 | 124   | 84      |	54          | T     | 1 Byte |
| 0101 0101 | 125   | 85      |	55          | U     | 1 Byte |
| 0101 0110 | 126   | 86      |	56          | V     | 1 Byte |
| 0101 0111 | 127   | 87      |	57          | W     | 1 Byte |
| 0101 1000 | 130   | 88      |	58          | X     | 1 Byte |
| 0101 1001 | 131   | 89      |	59          | Y     | 1 Byte |
| 0101 1010 | 132   | 90      |	5A          | Z     | 1 Byte |
| 0101 1011 | 133   | 91      |	5B          | [     | 1 Byte |
| 0101 1100 | 134   | 92      |	5C          | \     | 1 Byte |
| 0101 1101 | 135   | 93      |	5D          | ]     | 1 Byte |
| 0101 1110 | 136   | 94      |	5E          | ^     | 1 Byte |
| 0101 1111 | 137   | 95      |	5F          | _     | 1 Byte |
| 0110 0000 | 140   | 96      |	60          | `     | 1 Byte |
| 0110 0001 | 141   | 97      |	61          | a     | 1 Byte |
| 0110 0010 | 142   | 98      |	62          | b     | 1 Byte |
| 0110 0011 | 143   | 99      |	63          | c     | 1 Byte |
| 0110 0100 | 144   | 100     | 64          | d     | 1 Byte |
| 0110 0101 | 145   | 101     | 65          | e     | 1 Byte |
| 0110 0110 | 146   | 102     | 66          | f     | 1 Byte |
| 0110 0111 | 147   | 103     | 67          | g     | 1 Byte |
| 0110 1000 | 150   | 104     | 68          | h     | 1 Byte |
| 0110 1001 | 151   | 105     | 69          | i     | 1 Byte |
| 0110 1010 | 152   | 106     | 6A          | j     | 1 Byte |
| 0110 1011 | 153   | 107     | 6B          | k     | 1 Byte |
| 0110 1100 | 154   | 108     | 6C          | l     | 1 Byte |
| 0110 1101 | 155   | 109     | 6D          | m     | 1 Byte |
| 0110 1110 | 156   | 110     | 6E          | n     | 1 Byte |
| 0110 1111 | 157   | 111     | 6F          | o     | 1 Byte |
| 0111 0000 | 160   | 112     | 70          | p     | 1 Byte |
| 0111 0001 | 161   | 113     | 71          | q     | 1 Byte |
| 0111 0010 | 162   | 114     | 72          | r     | 1 Byte |
| 0111 0011 | 163   | 115     | 73          | s     | 1 Byte |
| 0111 0100 | 164   | 116     | 74          | t     | 1 Byte |
| 0111 0101 | 165   | 117     | 75          | u     | 1 Byte |
| 0111 0110 | 166   | 118     | 76          | v     | 1 Byte |
| 0111 0111 | 167   | 119     | 77          | w     | 1 Byte |
| 0111 1000 | 170   | 120     | 78          | x     | 1 Byte |
| 0111 1001 | 171   | 121     | 79          | y     | 1 Byte |
| 0111 1010 | 172   | 122     | 7A          | z     | 1 Byte |
| 0111 1011 | 173   | 123     | 7B          | {     | 1 Byte |
| 0111 1100 | 174   | 124     | 7C          | \|    | 1 Byte |
| 0111 1101 | 175   | 125     | 7D          | }     | 1 Byte |
| 0111 1110 | 176   | 126     | 7E          | ~     | 1 Byte |

## Keywords and Primitive Types

### Primitive Types

| symbol   | size    | Binary | Octal | Decimal | Hexadecimal |
| -------- | ------- | ------ | ----- | ------- | ----------- |
| bool     | _ Bytes |        |       |         |             |
| byte     | _ Bytes |        |       |         |             |
| char     | _ Bytes |        |       |         |             |
| float32  | _ Bytes |        |       |         |             |
| float64  | _ Bytes |        |       |         |             |
| float128 | _ Bytes |        |       |         |             |
| isize    | _ Bytes |        |       |         |             |
| int8     | _ Bytes |        |       |         |             |
| int16    | _ Bytes |        |       |         |             |
| int32    | _ Bytes |        |       |         |             |
| int64    | _ Bytes |        |       |         |             |
| int128   | _ Bytes |        |       |         |             |
| map      | _ Bytes |        |       |         |             |
| str      | _ Bytes |        |       |         |             |
| usize    | _ Bytes |        |       |         |             |
| uint8    | _ Bytes |        |       |         |             |
| uint16   | _ Bytes |        |       |         |             |
| uint32   | _ Bytes |        |       |         |             |
| uint64   | _ Bytes |        |       |         |             |
| uint128  | _ Bytes |        |       |         |             |

### Keywords

| symbol   | size    | Binary | Octal | Decimal | Hexadecimal |
| -------- | ------- | ------ | ----- | ------- | ----------- |
| break    | _ Bytes |        |       |         |             |
| case     | _ Bytes |        |       |         |             |
| const    | _ Bytes |        |       |         |             |
| continue | _ Bytes |        |       |         |             |
| default  | _ Bytes |        |       |         |             |
| else     | _ Bytes |        |       |         |             |
| exlcude  | _ Bytes |        |       |         |             |
| export   | _ Bytes |        |       |         |             |
| false    | _ Bytes |        |       |         |             |
| func     | _ Bytes |        |       |         |             |
| if       | _ Bytes |        |       |         |             |
| import   | _ Bytes |        |       |         |             |
| include  | _ Bytes |        |       |         |             |
| return   | _ Bytes |        |       |         |             |
| static   | _ Bytes |        |       |         |             |
| struct   | _ Bytes |        |       |         |             |
| switch   | _ Bytes |        |       |         |             |
| true     | _ Bytes |        |       |         |             |
| var      | _ Bytes |        |       |         |             |
| while    | _ Bytes |        |       |         |             |
| type     | _ Bytes |        |       |         |             |

## Binary Format Syntax

```shell

```


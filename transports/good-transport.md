# Good transport

## Frame format
| Byte 0 | Bytes 1...`N` | Bytes `N`+1 ... 61 | Bytes 62 ... 63 |
|  A     |   B           | Padding (`0x00`)   | C               |

- `A` - parameter A
- `B` - parameter B
- `Padding` - padding
- `C` - parameter C


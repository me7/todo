* python struct to byte array
* golang same as python above
* analyze and print pydobot / protocol
* make golang exe app
* test with dobot magician

``` pyhthon
# test string packing (float will pack using [IEEE-754](https://www.h-schmidt.net/FloatConverter/IEEE754.html) )
from struct import pack
i = pack('f',200.0)
[hex(ord(j)) for j in i]

```


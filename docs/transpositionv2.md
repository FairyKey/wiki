# Transposition detector v2
To add a transposition indicator in a song, simply add it as a single line starting either with `+` or `-` followed by the amount:
```
+2
```
Without specifying, the default transposition is always `0`. Transpositions can be added anywhere between or before notation lines.

Additional formats also [supported](https://github.com/FairyKey/FairyKey/discussions/3#discussioncomment-14650256):
```
Transpose +3
transposition -3
Transposition is -3
Transpose by 3
*No Transposition*
-3 Octave 3 (+9)
-3 (transpose 6)
```

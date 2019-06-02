## 和弦

* 和弦怎么学？
* 和弦的构成
* 不同种类和弦的感情色彩和用法



## 三和弦

* 大三和弦(Major)：大三度 + 小三度。可直接用根音音名来表示，如 **$$C$$**
* 小三和弦(Minor)：小三度 + 大三度。可用根音音名加下标 - 来表示，如 **$$ A_- $$**
* 增三和弦(Augment)：大三度 + 大三度。可用根音音名加上标 + 来表示，如 **$$ G^+ $$**
* 减三和弦(Diminish)：小三度 + 小三度。 可用根音音名加上标 o 来表示。如 **$$ B^o $$**

| 根音 | 大三和弦 | 小三和弦 | 增三和弦 | 减三和弦 |
| :--: |:--: |:--: |:--: |:--: |
|  C   | `C-E-G`    | `C-Eb-G`    | `C-E-G#`    | `C-Eb-Gb`    |
|  G   | `G-B-D`    | `G-Bb-D`    |  `G-B-D#`   |   `G-Bb-Db`  |
|  D   | `D-F#-A`    | `D-F-A`    |   `D-F#-A#`  |   `D-F-Ab`  |
|  A   | `A-C#-E`    | `A-C-E`    |   `A-C#-E#`  |   `A-C-Eb`  |
|  E   | `E-G#-B`    | `E-G-B`    |   `E-G#-B#`  |   `E-G-Bb`  |
|  B   | `B-D#-F#`    | `B-D-F#`    |  `B-D#-F##`   |  `B-D-F`   |
|  F#   | `F#-A#-C#`    | `F#-A-C#`   | `F#-A#-C##`    |  `F#-A-C`   |
|  Db  | `Db-F-Ab`    | `Db-Fb-Ab`    |   `Db-F-A`  |   `Db-Fb-Abb`  |
|  Ab  | `Ab-C-Eb`    | `Ab-Cb-Eb`    |  `Ab-C-E`   |   `Ab-Cb-Ebb`  |
|  Eb  | `Eb-G-Bb`    | `Eb-Gb-Bb`    |   `Eb-G-B`  |  `Eb-Gb-Bbb`   |
|  Bb   | `Bb-D-F`    | `Bb-Db-Fb`    |   `Bb-D-F#`  |  `Bb-Db-Fb`   |
|  F   | `F-A-C`    | `F-Ab-C`     |   `F-A-C#`  |  `F-Ab-Cb`   |



### Q & A
* Q: 老师， 和弦里面的音，描述的时候有没有讲究？ 例如：`Ab` 的小三和弦，应该是 `Ab B Eb` 这三个音，但是三音应该称之为 `Cb` 还是 `B` 呢？
* A: 可以这样推理：
    * `Ab` 的小三度是 `Cb`，`Ab` 的增二度是 `B`。
    * 三和弦是以三度音程关系组成，那 `Ab` 的小三和弦是由 小三度 + 大三度 组成
    * 显然 `A` 和 `Cb` 之间的音程关系是正确的，所以三音应是`Cb`

## 七和弦

| 根音 | 大七和弦 | 小七和弦 | 属七和弦 | 半减七和弦 |
| :--: |:--: |:--: |:--: |:--: |
|  C   | `C-E-G-B`    | `C-Eb-G`    |     `C-E-G-Bb` | `C-Eb-Gb-Bb` |
|  G   | `G-B-D-F#`    | `G-Gb-D`    |    `G-B-D-F` |    `G-Bb-Db-F` |
|  D   | `D-F#-A-C#`    | `D-F-A`    |    `D-F#-A-C` |    `D-F-Ab-C` |
|  A   | `A-C#-E-G#`    | `A-C-E`    |    `A-C#-E-G` |    `A-C-E-G` |
|  E   | `E-G#-B-D#`    | `E-G-B`    |    `E-G#-B-D` |    `E-G-Bb-D` |
|  B   | `B-D#-F#-A#`    | `B-D-F#`    |  `B-D#-F#-A`   |  `B-D-F-A` |
|  F#   | `F#-A#-C#-E#`    | `F#-A-C#`   |`F#-A#-C#-E`     |`F#-A-C-E`     |
|  Db  | `Db-F-Ab-C`    | `Db-Fb-Ab`    |  `Db-F-Ab-Cb`   |  `Db-Fb-Abb-Cb`   |
|  Ab  | `Ab-C-Eb-G`    | `Ab-Cb-Eb`    | `Ab-C-Eb-Gb`    | `Ab-Cb-Ebb-Gb`    |
|  Eb  | `Eb-G-Bb-D`    | `Eb-Gb-Bb`    | `Eb-G-Bb-Db`    | `Eb-Gb-Bbb-Db`    |
|  Bb   | `Bb-D-F-A`    | `Bb-Db-Fb`    | `Bb-D-F-Ab`    | `Bb-Db-Fb-Ab`    |
|  F   | `F-A-C-E`    | `F-Ab-C`     |    `F-A-C-Eb` |    `F-Ab-Cb-Eb` |


## 练习
{%mcq ans="o3", random=true%}
{%title%} C# 的增三和弦是什么?
{%o1%} C#-F-G#
{%o2%} C#-E##-G##
{%o3%} C#-E#-G##
{%o4%} C#-F-A
{%hint%} 增三和弦是 大三度 + 大三度
{%message%} C# 的 三度一定基于 E，大三度就是 E#。虽然 E# 音高上等于 F，但 C# 到 F 之间是一个减四度
{%endmcq%}
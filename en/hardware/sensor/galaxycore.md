Galaxycore
----------
https://en.gcoreinc.com/

### CMOS Image Sensors

| Sensor | I2C  | register:value |  fps |    WxH    | Act. WxH  |    Size |  Pixel |    SNR | Sensitivity |     DR | Technology | References                                                            |
|--------|------|----------------|-----:|:---------:|:---------:|--------:|-------:|-------:|------------:|-------:|------------|-----------------------------------------------------------------------|
| GC0328 | 0x42 | ?:0x9D         | 5~10 |  640x480  |           |         |        |        |             |        |            |                                                                       |
| GC032A | 0x42 | ?:0x23 ?:0x2A  | 5~25 |  640x480  |           |         |        |        |             |        |            |                                                                       |
| GC0308 |      |                |      |           |           |         |        |        |             |        |            |                                                                       |
| GC0309 | 0x42 |                |   30 |  648x488  |  640x480  |  1/9.0" | 2.50µm |        |             |        | CSP        | [DS](docs/GC0309_DS_V1.0_20091228.pdf)                                |
| GC0328 |      |                |      |           |           |         |        |        |             |        |            |                                                                       |
| GC0403 | 0x78 | ?:0x04 ?:0x03  |   60 |  776x584  |  768x576  |  1/3.0" | 6.25µm |   76dB |             |        | CSP        | [DS](docs/GC0403_DS_V1.0_20141204.pdf)                                |
| GC1024 | 0x78 | ?:0x10 ?:0x04  |   60 | 1296x742  | 1280x720  |  1/4.0" | 3.40µm |   41dB | 3.00V/lux.s |        | CSP        | [DS](docs/GC1024_DS_V1.0_20160108.pdf), [T20][t20]                    |
| GC1034 | 0x42 | ?:0x10 ?:0x34  | 5~30 | 1726x903  |           |         |        |        |             |        |            |                                                                       |
| GC1054 | 0x42 | ?:0x10 ?:0x54  |   30 | 1288x728  | 1280x720  |  1/4.0" | 3.00µm | 41.4dB | 1.80V/lux.s | 70.7dB | CSP/PLCC   | [DS](docs/GC1054_DS_V1.0_20171221.pdf)                                |
| GC1064 | 0x78 | ?:0x10 ?:0x24  | 5~25 | 2078x924  |           |         |        |        |             |        |            | [T20][t20]                                                            |
| GC2023 | 0x6E | ?:0x20 ?:0x23  | 5~30 | 2840x1352 |           |  1/2.7" |        |        |             |        | FSI        | [T20][t20], [T30][t30]                                                |
| GC2033 |      |                |      |           |           |         |        |        |             |        |            | [T30][t30]                                                            |
| GC2035 | 0x78 | ?:0x20 ?:0x35  |   15 | 1616x1232 | 1600x1200 |  1/5.0" | 1.75µm |        |             |        | CSP        | [DS](docs/GC2035_DS_v1.0_20120918.pdf)                                |
| GC2053 | 0x6E | ?:0x20 ?:0x53  |   30 | 1928x1088 | 1920x1080 |  1/2.9" | 2.80µm |   38dB | 3.87V/lux.s |   81dB | CSP FSI    | [DS](docs/GC2053_DS_V1.2_20190409.pdf), [T30][t30], [T31][t31]        |
| GC2063 | 0x6E | ?:0x20 ?:0x53! |   30 | 1928x1088 | 1920x1080 |  1/2.9" | 2.80µm |        |             |        | CSP FSI    | [DS](docs/GC2063_DS_V1.0_20180731.pdf)                                |
| GC2083 | 0x6E | ?:0x20 ?:0x83  |   30 | 1928x1088 | 1920x1080 | 1/3.02" | 2.70µm |   37dB | 3.24V/lux.s |   74dB | CSP        | [DS](docs/GC2083_DS_V0.2_20211122.pdf), [T31][t31]                    |
| GC2093 | 0x6E | ?:0x20 ?:0x93  |   60 | 1928x1088 | 1920x1080 |  1/2.9" | 2.80µm |   38dB |  3.9V/lux.s |  105dB | CSP        | [DS](docs/GC2093_DS_Beta0.3_20200221.pdf)                             |
| GC3003 |      |                |      |           |           |  1/2.8" | 2.45µm |        |             |        |            |                                                                       |
| GC4023 | 0x52 | ?:0x40 ?:0x23  |   30 | 2588x1468 | 2560x1440 |  1/2.7" | 2.30µm |   38dB | 2.65V/lux.s |   79dB | CSP        | [DS](docs/GC4023_DS_V1.4_20221229.pdf)                                |
| GC4043 |      |                |      |           |           |         |        |        |             |        |            |                                                                       |
| GC4053 |      |                |      |           |           |         |        |        |             |        |            |                                                                       |
| GC4653 | 0x52 | ?:0x46 ?:0x53  |   30 |           | 2560x1440 |  1/3.0" | 2.00µm |   38dB |  2.4V/lux.s |   81dB | SCP-41     | [DS](docs/GC4653_Brief_DS_VB0.1_20191226.pdf), [T31][t31], [T40][t40] |
| GC4663 |      |                |   60 |           | 2560x1440 |  1/3.0" | 2.00µm |   38dB |  2.4V/lux.s |  105dB | CSP-41 HDR | [DS](docs/GC4663_Brief_DS_V1.2_20210511.pdf)                          |
| GC4C33 | 0x52 | ?:0x46 ?:0xC3  | 5~30 | 2560x1440 |           |         |        |        |             |        |            |                                                                       |
| GC5035 | 0x6E | ?:0x50 ?:0x35  | 5~30 | 1920x1080 |           |         |        |        |             |        |            |                                                                       |
| GC5603 |      |                |      |           |           |         |        |        |             |        |            |                                                                       |
| GC8024 |      |                |      |           | 3264x2448 |  1/4.0" | 1.12µm |        |             |        | TSI        |                                                                       |

Sometimes vendors like Ingenic use single unshifted I2C bus address in their sensor drivers, e.g. `0x37`. 
Left-shifting the address and adding a zero we get the I2C write register `(0x37 << 1 | 0) = 0x6e`, 
while adding 1 we get the I2C read register `(0x37 << 1 | 1) = 0x6f`.

* Question mark after an address (`0x6F?`) means it is not corroborated by a data sheet.
* Exclamation mark after an address (`0x53!`) means the data is probably erroneous.

[t20]: https://github.com/themactep/openingenic/blob/master/kernel/sensors/t20/
[t30]: https://github.com/themactep/openingenic/blob/master/kernel/sensors/t30/
[t31]: https://github.com/themactep/openingenic/blob/master/kernel/sensors/t31/
[t40]: https://github.com/themactep/openingenic/blob/master/kernel/sensors/t40/

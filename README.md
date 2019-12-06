# RS485-Channel
Multi channel RS485 master communication and simple Modbus master aplication layer over RS485.
Work with Modbus IO Module:

1) v.0.1.0: https://photos.app.goo.gl/6iC17XjzNHSULanWA
ATmega128; 32 DI ( isolated ); RS485 ( isolated ); HMI: LED and SPI expander
![Screen Shot](https://lh3.googleusercontent.com/4mU1p0M6xqio6iRIdeuDf61aI3NyapH5sV-aDeyYjHTSwoeZ5dt2IbyUyCZR7bwseF4Pnl5f1bNP7Ahp-OHaXBA7hpdBXHSnsbl9rce77_q0Hbmh-tWIp2-KbMSjECRTO9HDPbnreid1_8DvoqNBV4a1h3KQDCNvL4_a_BRbDb0f_vWctw_LycolGScezvwAfodxkJlSiinfYI-AsCjTQPYUyE4Xx-jLsgRCmmDQb6SF7b8hDiJMqoRt38GXyOjFjYIxxjAGFhN7iLWL3XGTF4US-67HTmAK-JdiVYmeQ8SBqrWtOf2P7yLhuDCJoGBx_PuOsbPbZ8DKwg9zbOtk90wnFCymwxYbqUcPDTVgltC6_5Zj8fVVi-8DLe9ZSqdCrWd6Hn4WiNmrMlNNUlLcC2tM3cfh8jggsMVErz0zIqSPiE5zRlb0OW0r9z6jt4-cCJDbMGB5l5BAXvLwFP-EVEi_p6Bo8x0jgFAtVBDE8nU9Vf9MOuKtm0vpvEaDUSWKSQfiJ6PQ8s5pOT1n9__R_iHcAlemyVjRDLgc5VTtJYmbNuMtmSxaCKCMJ5BGLdIfdbiLICzLCAh6uyXTwmOXO2Q20o_6OhYxOUMyKulWzjh8_7wHXNb0VcrO5VCa6TJ3O056o4_HYxdbODmPD5_QO0m1iQGcae5uO7qeOjadK0ORKzxT-KdZ1MC_AGVXjfWZOdnp-fJR_7wJWQWLu2qPjJLDoCvBIr1FLektTnxUBaBiNtg=w2105-h1184-no)<br>

2) v.0.0.9: https://photos.app.goo.gl/yJJbBFp53oGfpSQh1
ATmega128; 16 DI ( isolated ); 16 DO ( isolated ); RS485 ( isolated ); HMI: LED and SPI expander

![Screen Shot](https://lh3.googleusercontent.com/uVXqWqGqz2rZWhP6_yw_ArZvrsaW2GTMQOX9JqS06ZyMrvv-zfGHFiylNuGf8Ir2k5hXnjIHzQGT04MwYkWtUh14hBQr7EOksngMAVP3-zV4YJzP0Y-Yfg6jfaA1li2h70kWbrCylUFNS88jR7OvD-V3k4CXJXtyMgB7OlbhSwqoYZMGI4uFoBjnv9SsFlhGSj2SGlAJCB2CXiGG6jXKWD4rmzOsqus6fCUrCKM6sRl_RySc1HrfJ1z_6KR_7GhekBvBZYlj6nWsjaaoJR3V2Gf6953s3hNyWLbkFVx0s2E4xkZ-dZqOr6Oy1ZpdC4WvpIUi-g4I_l2osjMxSoUUDA5d2qJHoBFWUycJIMwS66ZGJzTDdzD2ACC8aslCvE7nYVCDOjg2-rsiIqDUgL1Lgbp0dPt1wSCjkRap1Q2Yh8jpgB0ZJUUBlxudavW9eGO8u3NiQWRI63ZYip7bheGs6UbPd8jjSClTqGFhZs3qk4FL_369mPqvHXlWkcDQA3cJhc3RF1RrEc4zHKHMbk5PYEplRpgelsWGiaP7P2YYAVM3jrHVJnab5XuKhyNzJIMWMc6zepT93HbCv9Z5hBx5RurxUlgNJNa-eNJrdVqAI5PRxXkb-dhAE6NCTsU4CmuTq9OMHNwZ9uyckObhvN-LqAwkXhVJZMzuC1_u9MjHnGzhTkbFzi0w-bWfWvRzZsASK57nagyzPEAQyXHAlg=w1560-h878-no)<br>

3) v.0.0.8: https://photos.app.goo.gl/Z9C2jXlDd0mY3kmC3
ATmega128 + 64KB SRAM; Embedded JTAG ( isolated ); 10 DI ( isolated ); 12 DO ( isolated ); 7 AIN ( 12/16 bits - isolated ); 2 AO ( 16 bits - isolated ); RS485; USB->Virtual Serial Port ( isolated )

![Screen Shot](https://lh3.googleusercontent.com/MFSm0rBE19Bkr6n2bQHMvwQDbrM88FVj6mi0oa1zPS12Zd1XVF8ZQhruDUSjj5ge2i3OTbsoyuJ5pJxQHAq7EGBXzrQ4npnA8TN-FYfQfRKF62vvIBu4lyrC2G8nLSsmaurKJ1AL63Wg1E1u6Kg3UWoYp94jPsGx7les2hHFN3h3157JmJn5emWt22zctwKuoiE0V9xlOegWnj1ZXh1caGQrHgmIB71cJP5h5bv6GbUMtQOyog8yz-kyPxy6S1MSCEX3xZZd2DP3gMVxeqpYgEInoQCW46HcGxgobg6J1JtNPG9Mr0FF1X2HbV9_R4C18u7d79Yfyb3AA3Et6dBWuwuHb6t0_V642tU-ff1alBq7FMpWoHSRmcBQUOWKGdH6yLo9GPd5a6_MH5jhhh1k1tBZsirvQleJ-DsP7VeRJrk1xcb6bAeKfSAkZEBqKm1ocxiBcHBjITTk1qyKYHBStECvgf2gY_nwudwcKR1mjJkGn3jowyLHPw2lpwmPAaV01omhRaxvsUOJZVKyXMBjsAh7KeoQ96FOYFMiptYe5jJ_jfvoDCd9T5MqHaiGrkpl_iI-xwXtU2jDASB8Gn-R2UnQ2w_Rtigq0nLZ0SZAssacPhLRZoJIKJGVcrtYlD7ufrOkX--KG2rIyONl5E1QoSHCeUc5887MFwnXQw65MT8F-75f9HV4q8AauVMvqUo2ONeTQtFoZeSWpo4YIw=w1560-h878-no)<br>

4) v.0.0.5: https://goo.gl/photos/QCfDXFoU9WnBnyi77
ATxmega128; 10 DI ( isolated ); 12 DO ( isolated ); 7 AI ( not isolated ); 2 AO ( not isolated )

![Screen Shot](https://lh3.googleusercontent.com/CrdKOV2Exipbm48BkSPXY6QQhLZtKpu2Nv74_5UNym-NVNAPvjKg5PgMn0AcWso0ZyiwsN57_bQ84GkdWwb7Ry0Kp0wBErN_FqKzjVGy-RkI7oBeXEOX3lbk3L_sag4jpUtL6XL_7z4-2A9JB4nJ5N8eDOMvSsk_vyZd-QJAPM5tTXT8s0LB6l4LfTdwNbY4EcXigg_OVyJis-DMLxeYNSsxG71GUVcQLt-kU4s7OCiboMgQa-1HW34-17OXkidpmwVVyQGjMnnico8W84CT-oo5ifHH2OV12lPdnzk2QDA6Ba1MxgiPPNiL1AI4Ddw0ljuSeHRd1PAAe2h5Cw0Efa_bCrpdjatL50HknVmisk_Wq6wLsi8mJ-jFOiaZLpNb5acmandOS_44eTYfF3-8xoIYWwwaDky8cjSWrsGdJf1P9RwySioCeaTY87fkwPZVjsMt1DcwxTHguXf6UCBtERuYttkovSb-Ckyd_fub_5rKGNKd0IgqTBM0CnrZewAAi1zjdYNrlUwyCQrIC86EkA8U6nLzsmn01w6f9noMxi2UR4sf2xdNYlnZcsSEp5dKILmzpsBXSmpW_2QIB7F6HR-KGu1ZCRFI4cNlldwq2drFFrrZwLv2LV2JxLXRwX_oVj0be-cMNpRJQaFIlBKRKDWSeZE7CKjhLEl93wqukypxnhAkh95ftAy5ptpu-THbBEzlBj6zKCZNJKpOcA=w800-h600-no)<br>

5) v.0.0.3: https://goo.gl/photos/ECHeer7ifiq2STHZ8 - Automatic Fish Feeder With PLC ( old PLC board )
https://www.youtube.com/watch?v=zcFjG9XD-4E&list=PLE616v1yP136VSTElJPbgqLRKw9dhneZ0

![Screen Shot](https://lh3.googleusercontent.com/i4vTtbMWcvufEfyPBXmEqtodp0uiaY80SN7nO53SizIuQGnKfskF3hOMWklSdp-E9tZwQFcahZGzqjpb_negQXEel_Ek9y2Q-xKqGe8nZFe8iSiKAYTuJJ7f9EiFlDz4nAfxZh-JwOHoanxEeHOk7S4ZBlITvbNXki2caGARQPg28cYvAEWLrhYlO4jIVNJ1u0FXz1XzlYSx5J1nXS0mtQefo2IzwadqRC1u_vziupT0Fe9qfGVQymvKK7zWInEjUshE4K-GbRTxpQTgDNWyImrhoL-DvrHVt9qu0Y4xG-VIqXxZ6ZS2KfvSQ15kddukfKs1x3Umb0xTVf33TF89o58FlunZHBvR9EITT13Ke3G6lsoOTQucqT8j5edNBI36gCUnRdn_JUaBjpc0gUciYcsNhvxmZmprITA2JZy_EWPfu068hc5PoFiTwgy0iZJXFJSkIwXAnYqA-47TTX1yOKnD8mORU91LtUfaS21BZ6cKBy90R5g3Xqo5Dhas0RXXaBC50P27vzN_nIzyAqwT7hCGoi_vgtFjF9wg21gcbyKm32ok7xzMjWMYUnwNmgpBeP_kCsKuX9ciPE-7k_tFMjQ3KHqqqXUdNO-jP6QrDGqhsa9yDcIrxGYuBZaT6ap04sALycBCSXbvSZi34mFChnCc2Mh-XZ1IBcmd_d-aqqKrzepfpWOf5bohYNa00gZUgcmnZ9ve4pHbMm3vKQ=w1024-h768-no)<br>

![Screen Shot](https://raw.githubusercontent.com/SimeonSimeonovIvanov/DOS-Window-Manager/master/LD_EDIT.jpg)<br><br>

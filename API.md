<details>
<summary>Login APIs</summary>

|                        API                        |Avail|                                      Parameter                                      |Note|
| ------------------------------------------------- | :-: | ----------------------------------------------------------------------------------- | -- |
| xx_eone_zhmmdl                                    | ✅ | STR username STR password \[STR cookies\]                                           |eone账号密码登录，cookies是通过webvpn访问|
| xx_eone_yzmdl_sendsms                             | ✅ | NUM phone \[STR cookies\]                                                           |eone验证码登录发送验证码，cookies是通过webvpn访问|
| xx_eone_yzmdl                                     | ✅ | NUM phone NUM code STR username \[STR cookies\]                                     |eone验证码登录，cookies是通过webvpn访问|
| xx_eone_jwglxtdl                                  | ✅ | STR username STR password \[STR cookies\]                                           |教务系统登录，cookies是通过webvpn访问|
| xx_eone_jxzhptdl                                  | ✅ | STR username STR password \[STR cookies\]                                           |M福医大登录，cookies是通过webvpn访问|
| xx_vpndl                                          | ✅ | STR username STR password                                                           |webvpn登录|
| xx_vpn_ehalldl                                    | ✅ | STR cookies                                                                         |ehall登录，webvpn的cookies|
| xx_ehalldl                                        | ✅ | STR username STR password                                                           |ehall登录|
| xx_ehall_zhcpdl                                   | ✅ | STR cookies \[BOOL intranet\]                                                       |综合测评登录，ehall的cookies|
| xx_ehall_jbxxdl                                   | ✅ | STR cookies \[BOOL intranet\]                                                       |基本信息登录，ehall的cookies|

</details>

<details>
<summary>Data APIs</summary>

|                        API                        |Avail|                                      Parameter                                      |Note|
| ------------------------------------------------- | :-: | ----------------------------------------------------------------------------------- | -- |
| xx_xsfw_jbxx                                      | ❌ |                                                                                     ||
| xx_zxzx_ml                                        | ✅ | STR cookies                                                                         |资讯中心目录，eone的cookies，不支持webvpn访问|
| xx_zxzx_nr                                        | ✅ | STR lk_q STR cookies                                                                |资讯中心内容，eone的cookies，不支持webvpn访问|

</details>

<details>
<summary>Function APIs</summary>

|                        API                        |Avail|                                      Parameter                                      |Note|
| ------------------------------------------------- | :-: | ----------------------------------------------------------------------------------- | -- |
| pdf_exportimg                                     | ✅ | STR url \[STR cookies\] \[STR headers\]                                             |PDF导出为图片|
| qrcode_decode                                     | ✅ | STR url                                                                             |二维码识别|
| qrcode_encode_qrcode                              | ✅ | STR qrcode                                                                          |二维码生成|
| qrcode_encode_text1-bottom1                       | ✅ | STR qrcode \[STR t_bottom\]                                                         |二维码生成，1个底部文字|
| qrcode_encode_text2-bottom2                       | ✅ | STR qrcode \[STR t_bottom1\] \[STR t_bottom2\]                                      |二维码生成，2个底部文字|
| qrcode_encode_text2-top1-middle1                  | ✅ | STR qrcode \[STR t_top\] \[STR t_middle\]                                           |二维码生成，1个顶部文字，1个中部文字|
| qrcode_encode_text3-top1-middle1-bottom1          | ✅ | STR qrcode \[STR t_top\] \[STR t_middle\] \[STR t_bottom\]                          |二维码生成，1个顶部文字，1个中部文字，1个底部文字|

</details>

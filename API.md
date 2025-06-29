<details>
<summary>Login APIs</summary>

|                        API                        |Avail|                                      Parameter                                      |Note|
| ------------------------------------------------- | :-: | ----------------------------------------------------------------------------------- | -- |
| xx_eone_zhmmdl                                    | ✅ | STR username STR password \[BOOL intranet\]                                         |eone账号密码登录，默认webvpn访问|
| xx_eone_yzmdl_sendsms                             | ✅ | NUM phone \[STR cookies\]                                                           |eone验证码登录发送验证码，cookies是通过webvpn访问|
| xx_eone_yzmdl                                     | ✅ | NUM phone NUM code STR username \[STR cookies\]                                     |eone验证码登录，cookies是通过webvpn访问|
| xx_eone_jwglxtdl                                  | ✅ | \[STR username\] \[STR password\] \[STR cookies\] \[BOOL intranet\]                 |教务系统登录，可提交eone账号密码或cookies，默认webvpn访问|
| xx_eone_jxzhptdl                                  | ✅ | \[STR username\] \[STR password\] \[STR cookies\] \[BOOL intranet\]                 |M福医大登录，可提交eone账号密码或cookies，默认webvpn访问|
| xx_vpndl                                          | ✅ | STR username STR password \[BOOL onlyvpncookies\]                                   |webvpn登录|
| xx_vpn_isonline                                   | ✅ | STR cookies                                                                         |webvpn是否在线|
| xx_vpn_ehalldl                                    | ❌ | STR cookies                                                                         |ehall登录，可提交eone账号密码或cookies，webvpn的cookies|
| xx_ehalldl                                        | ❌ | STR username STR password                                                           |ehall登录|
| xx_ehall_zhcpdl                                   | ✅ | \[STR username\] \[STR password\] \[STR cookies\] \[BOOL intranet\]                 |综合测评登录，可提交eone账号密码或cookies，默认webvpn访问|
| xx_ehall_jbxxdl                                   | ✅ | \[STR username\] \[STR password\] \[STR cookies\] \[BOOL intranet\]                 |基本信息登录，可提交eone账号密码或cookies，默认webvpn访问|

</details>

<details>
<summary>Data APIs</summary>

|                        API                        |Avail|                                      Parameter                                      |Note|
| ------------------------------------------------- | :-: | ----------------------------------------------------------------------------------- | -- |
| xx_xsfw_jbxx                                      | ❌ |                                                                                     ||
| xx_eone_self-info                                 | ✅ | STR cookies \[BOOL intranet\]                                                       |一网通办学院学历姓名，eone的cookies，默认webvpn访问|
| xx_eone_person-info                               | ✅ | \[STR username\] \[STR peoplename\] \[STR mail\] STR cookies \[BOOL intranet\]      |一网通办个人信息，eone的cookies，默认webvpn访问|
| xx_zxzx_ml                                        | ✅ | STR cookies \[BOOL intranet\]                                                       |资讯中心目录，eone的cookies，默认webvpn访问|
| xx_zxzx_nr                                        | ✅ | NUM articleid STR cookies \[BOOL intranet\]                                         |资讯中心内容，eone的cookies，默认webvpn访问|
| xx_jwglxt_xskb                                    | ✅ | STR username NUM xnm NUM xqm STR cookies \[BOOL intranet\]                          |教务系统学生课表，jwglxt的cookies，默认webvpn访问|
| xx_jwglxt_xsxk                                    | ✅ | STR username NUM xnm NUM xqm STR cookies \[BOOL intranet\]                          |教务系统学生选课，jwglxt的cookies，默认webvpn访问|
| xx_jwglxt_jxjdb                                   | ✅ | STR jxbid STR cookies \[BOOL intranet\]                                             |教务系统教学进度表，jwglxt的cookies，默认webvpn访问|
| xx_jwglxt_jxzxjh                                  | ✅ | NUM xydm NUM zydm NUM njdm STR cookies \[BOOL intranet\]                            |教务系统教学执行计划，jwglxt的cookies，默认webvpn访问|
| xx_tywsyj_match-exam                              | ✅ | STR username STR kcmc \[STR cookies\]                                               |唐云网上阅卷匹配考试，webvpn的cookies|
| xx_tywsyj_score-overview                          | ✅ | STR username NUM examid \[STR cookies\]                                             |唐云网上阅卷得分概况，webvpn的cookies|
| xx_tywsyj_score-analysis                          | ✅ | STR username NUM examid STR cookies                                                 |唐云网上阅卷得分分析，webvpn的cookies|
| xx_tywsyj_score-point                             | ✅ | NUM examid \[STR cookies\]                                                          |唐云网上阅卷得分点，webvpn的cookies|
| xx_tywsyj_answer-sheet                            | ✅ | STR username NUM examid STR cookies                                                 |唐云网上阅卷答题卡图片，webvpn的cookies|
| xx_zhcp                                           | ✅ | STR username STR cookies \[BOOL intranet\]                                          |综合测评，zhcp的cookies，默认webvpn访问|
| xx_zhcp_rank-szcp                                 | ✅ | \[STR username\] \[NUM zydm\] \[NUM njdm\] STR kch \[STR cookies\]                  |综合测评分项-素质测评排名，附加返回体测达不达标、课程达不达标，jxzxjh的kch，webvpn的cookies|
| xx_zhcp_rank-zhcp                                 | ✅ | \[STR username\] \[NUM zydm\] \[NUM njdm\] \[STR cookies\]                          |综合测评分项-综合测评排名，webvpn的cookies|

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

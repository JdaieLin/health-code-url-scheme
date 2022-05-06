# health-code-url-scheme

微信/支付宝健康码小程序 url scheme 收集

方便大家用于ios快捷指令一键打开/其他app跳转

若有新增/错漏，请提issue

### 微信小程序

需要小程序开发者申请 url scheme 供外部访问。

⚠️由于微信api 4-11日开始调整，永久有效URL scheme将降级为30天有效，只能被一个用户访问，其他用户将无法使用相同的url scheme，所以按字面理解下面两个微信url将在2022-4-11后失效。

[详情参阅](https://developers.weixin.qq.com/miniprogram/dev/framework/open-ability/url-scheme.html)

| 地区 | 健康码别名 | url scheme | 已验证可用 
| - | - | - | - |
| 广东 | 粤康码/穗康码 | weixin://dl/business/?t=QDZVQEO2z9f | ⭕️ 2022-4-11 到期 |
| 四川 | 天府健康通 | weixin://dl/business/?t=Je3MKDRpAWv | ⭕️ 2022-4-11 到期 |


### 支付宝小程序

| 地区 | 健康码别名 | url scheme | 已验证可用 
| ---- | ---- | - | - |
| 安徽 | 安康码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2018081661065647&page=pages%2Fservice%2Fservice%3furl%3dhttps%3a%2f%2fakm.ahzwfw.gov.cn%2fakm-sj-user%2findex.html%3fbelongarea%3d340100%24%2fhome%3fbelongarea%3d340100%26auth%3dct</p></details> | ✅|
| 北京 | 北京健康宝 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001135679870</p></details> | ✅|
| 天津 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=20000067&url=https%3A%2F%2Frender.alipay.com%2Fp%2Fc%2Ftianjin-jkm%2Freport.html%3ForgCode%3D120000-91330106MA27Y4U47R-p0000%26type%3Dtwocode%26needRequestCodeDetail%3DYES%26from%3Doffline%26showChooseCity%3DYES</p></details> | ✅|
| 重庆 | 渝康码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001130674650</p></details> | ✅|
| 福建 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021003125688065&page=pages/index/index</p></details> | ✅|
| 甘肃 | 健康出行码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=20000067&url=https%3A%2F%2Fwx.jkgs.gov.cn%2Fwap%2FhealthPass%2FaliPay%2Faccess</p></details> | ✅|
| 广西 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=68687957&url=%2Fp%2Fc%2F18j5w1jmsiqo%2Freport.html%3ForgCode%3D450000-91330106MA27Y4U47R-p0000%26type%3Dtwocode%26needRequestCodeDetail%3DYES%26from%3Doffline%26showChooseCity%3DYES</p></details> | ✅|
| 贵州 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001135637273</p></details> | ✅|
| 海南 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001155692504&query=action%3Dopen%26tab%3Dcode%26source%3D%E5%9F%8E%E5%B8%82%E5%81%A5%E5%BA%B7%E7%A0%81</p></details> | ✅|
| 河北 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021002100611022&page=pages/index/index</p></details> | ✅|
| 河南 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2019091067186151&query=code%3Dalipays_ysb_jkm%26region%3D410500%26value%3Dhttps%253A%252F%252Frender.alipay.com%252Fp%252Fc%252Fhenan-jkm%252Freport.html%253ForgCode%253D410500-91330106MA27Y4U47R-p0000%2526type%253Dtwocode%2526needRequestCodeDetail%253DYES%2526from%253Doffline</p></details> | ✅|
| 湖北 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001132656455&nbupdate=syncforce&nbversion=0.2.2003261457.6</p></details> | ✅|
| 湖南 | 健康卡 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021002133603718</p></details> | ✅|
| 吉林 | 吉祥码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2019082066328992&page=pages%2Fqrcode%2Fqrcode</p></details> | ✅|
| 江苏 | 苏康码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2018062060350751&page=%2Fpages%2Fweb%2Fweb%3Furl%3Dhttps%3A%2F%2Fjsstm.jszwfw.gov.cn%2FjkmIndex.html</p></details> | ✅|
| 江西 | 赣通码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2018082161130063&page=pages%2Fh5Load%2Fh5Load%3Flightappiduuid%3D6gdemQfv%26appName%3D%E8%B5%A3%E9%80%9A%E7%A0%81%26isneeduserinfo%3D0%26spec%3D5%26lightappurl%3Dhttps%3A%2F%2Fganfutong.jiangxi.gov.cn%2Fjmopen%2Fwebapp%2Fhtml5%2Fgantongma%2Findex.html</p></details> | ✅|
| 内蒙古 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001114655676&page=pages%2fweb-view%2fweb-view%3furl%3dhttps%3a%2f%2fzwfw.nmg.gov.cn%2fapp%2ficity%2fapps%2fareas%2fneimenggu%2fcard-healthcode%2findex.html%26title%3d%e5%81%a5%e5%ba%b7%e7%a0%81%26form%3dexternal</p></details> | ✅|
| 青海 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001143672652&query=healthqrcode</p></details> | ✅|
| 山东 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001136608745</p></details> | ✅|
| 陕西-西安 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021001140645628</p></details> | ✅|
| 上海 | 随申码 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2019072665939857&page=pages%2Fmy-station-type%2Fmy-station-type</p></details> | ✅|
| 四川 | 天府健康通 | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021002116662889</p></details> | ✅|
| 新疆 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2019111269039717&page=pages%2fhealthcode%2fhealthcode_index%2fhealthcode_index</p></details> | ✅|
| 云南 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=2021002139686716</p></details> | ✅|
| 浙江-杭州 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=20000067&url=https://h5.dingtalk.com/healthAct/index.html?source=zfbcsfw0211</p></details> | ✅|
| 全国 | | <details><summary>点击展开</summary><p>alipays://platformapi/startapp?appId=20000067&url=https%3A%2F%2F68687564.h5app.alipay.com%2Fwww%2Findex.html</p></details> | ✅ 需再次点击 |

### 云闪付

云闪付APP内部有健康码总入口，进入后会根据定位跳转至对应地区健康码

| 地区 | 健康码别名 | url scheme | 已验证可用 
| - | - | - | - |
| 全国通用 | | upwallet://applet?encryptAppId=d9a62204ddad59af | ✅ |




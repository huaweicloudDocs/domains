# 查询域名注册信息（WHOIS）<a name="domain_ug_330004"></a>

## 操作场景<a name="section64101024183916"></a>

域名注册成功后，WHOIS平台会记录已注册域名的注册信息。请登录华为云[WHOIS平台](https://www.huaweicloud.com/whois/index.html)，查询域名注册信息。

支持查询的域名注册信息如[表1](#table0848124212012)所示。

**表 1**  已注册域名信息

<a name="table0848124212012"></a>
<table><thead align="left"><tr id="row9848204217209"><th class="cellrowborder" valign="top" width="23.330000000000002%" id="mcps1.2.3.1.1"><p id="p184854242010"><a name="p184854242010"></a><a name="p184854242010"></a>参数</p>
</th>
<th class="cellrowborder" valign="top" width="76.67%" id="mcps1.2.3.1.2"><p id="p484819422204"><a name="p484819422204"></a><a name="p484819422204"></a>参数说明</p>
</th>
</tr>
</thead>
<tbody><tr id="row14153105716221"><td class="cellrowborder" valign="top" width="23.330000000000002%" headers="mcps1.2.3.1.1 "><p id="p1715355712213"><a name="p1715355712213"></a><a name="p1715355712213"></a>域名所有者</p>
</td>
<td class="cellrowborder" rowspan="2" valign="top" width="76.67%" headers="mcps1.2.3.1.2 "><p id="p468510127233"><a name="p468510127233"></a><a name="p468510127233"></a>根据<span>ICANN组织</span>和欧盟合规要求，<span>WHOIS数据库的公开查询结果将不再显示域名注册者的私人信息</span>，请联系当前域名注册商获取。</p>
<a name="ul12407516280"></a><a name="ul12407516280"></a><ul id="ul12407516280"><li><span>ICANN</span><span>（The Internet Corporation for Assigned Names and Numbers，ICANN）</span>：<span>《通用顶级域名注册数据临时政策细则</span><span>》</span><span>（</span><span>Temporary Specification for gTLD Registration Data</span><span>）</span></li><li>欧盟：<span>《通用数据保护条例》</span>（General Data Protection Regulation，简称GDPR）</li></ul>
</td>
</tr>
<tr id="row14745145419220"><td class="cellrowborder" valign="top" headers="mcps1.2.3.1.1 "><p id="p674565422214"><a name="p674565422214"></a><a name="p674565422214"></a>联系邮箱</p>
</td>
</tr>
<tr id="row148489424207"><td class="cellrowborder" valign="top" width="23.330000000000002%" headers="mcps1.2.3.1.1 "><p id="p148481742182018"><a name="p148481742182018"></a><a name="p148481742182018"></a><span>域名注册商</span></p>
</td>
<td class="cellrowborder" valign="top" width="76.67%" headers="mcps1.2.3.1.2 "><p id="p8848164210207"><a name="p8848164210207"></a><a name="p8848164210207"></a>域名当前的注册商。</p>
</td>
</tr>
<tr id="row1784818422206"><td class="cellrowborder" valign="top" width="23.330000000000002%" headers="mcps1.2.3.1.1 "><p id="p16848174216207"><a name="p16848174216207"></a><a name="p16848174216207"></a>注册日期</p>
</td>
<td class="cellrowborder" valign="top" width="76.67%" headers="mcps1.2.3.1.2 "><p id="p118481142122012"><a name="p118481142122012"></a><a name="p118481142122012"></a>域名首次被注册的日期。</p>
<p id="p17471356152715"><a name="p17471356152715"></a><a name="p17471356152715"></a>示例：</p>
<a name="ul155072916148"></a><a name="ul155072916148"></a><ul id="ul155072916148"><li>xxxx-xx-xx：域名example.com第一次被注册。</li><li>yyyy-yy-yy：域名example.com到期后被释放。</li><li>zzzz-zz-zz：域名example.com被其他人购买。该购买人通过WHOIS平台查询，显示的注册日期为域名第一次被注册的日期（xxxx-xx-xx），而不是他购买域名的日期（zzzz-zz-zz）。</li></ul>
</td>
</tr>
<tr id="row138481442102013"><td class="cellrowborder" valign="top" width="23.330000000000002%" headers="mcps1.2.3.1.1 "><p id="p88486422201"><a name="p88486422201"></a><a name="p88486422201"></a>到期日期</p>
</td>
<td class="cellrowborder" valign="top" width="76.67%" headers="mcps1.2.3.1.2 "><p id="p18481442152011"><a name="p18481442152011"></a><a name="p18481442152011"></a>域名到期日期。</p>
<p id="p209171827172415"><a name="p209171827172415"></a><a name="p209171827172415"></a>为确保域名的正常使用，请在域名到期前及时续费，详情请参见<a href="域名续费.md">域名续费</a>。</p>
</td>
</tr>
<tr id="row2084824222016"><td class="cellrowborder" valign="top" width="23.330000000000002%" headers="mcps1.2.3.1.1 "><p id="p1584874282018"><a name="p1584874282018"></a><a name="p1584874282018"></a>域名状态</p>
</td>
<td class="cellrowborder" valign="top" width="76.67%" headers="mcps1.2.3.1.2 "><p id="p1284812422207"><a name="p1284812422207"></a><a name="p1284812422207"></a>了解域名各状态码的含义，请参见<a href="查看域名状态.md">查看域名状态</a>。</p>
</td>
</tr>
<tr id="row128901114102112"><td class="cellrowborder" valign="top" width="23.330000000000002%" headers="mcps1.2.3.1.1 "><p id="p68911014182115"><a name="p68911014182115"></a><a name="p68911014182115"></a>DNS服务器</p>
</td>
<td class="cellrowborder" valign="top" width="76.67%" headers="mcps1.2.3.1.2 "><p id="p1889181482116"><a name="p1889181482116"></a><a name="p1889181482116"></a>域名当前用于解析的权威DNS服务器。</p>
<p id="p14333175023610"><a name="p14333175023610"></a><a name="p14333175023610"></a><span>通过华为云注册成功的域名默认使用华为云DNS进行解析，</span>如需更改，请参见<a href="修改DNS服务器.md">修改DNS服务器</a>。</p>
</td>
</tr>
</tbody>
</table>

## 操作步骤<a name="section4266163831011"></a>

1.  打开[https://www.huaweicloud.com/whois/index.html](https://www.huaweicloud.com/whois/index.html)，进入“域名注册信息查询（WHOIS）”页面。

    **图 1**  域名注册信息查询（WHOIS）<a name="fig13416131921316"></a>  
    ![](figures/域名注册信息查询（WHOIS）.png "域名注册信息查询（WHOIS）")

2.  在输入框中，输入待查询的域名名称，例如“example.com”。
3.  单击“查询”。

    显示域名example.com的注册信息。

    **图 2**  域名example.com注册信息<a name="fig1459943131613"></a>  
    ![](figures/域名example-com注册信息.png "域名example-com注册信息")



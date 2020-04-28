Introduction
============
中国各省/自治区/直辖市、市/自治州/盟/地区、区/县/县级市/旗数据，

包含名称、拼音、拼音首字母、行政代码、区号等数据。


版本说明
============
本数据使用 MySQL 处理，现导出 SQL（基本兼容各主流关系型数据库） 和 CSV 两种数据格式，

以备在使用不同的数据库（包括关系型数据库和非关系数据库）时能正确导入。

* FULL 版 - 完整数据，包括：ID、名称、父 ID、拼音、拼音首字母、拼音首字母集合（如：齐齐哈尔 - qqhe）、附加说明（如：广西壮族自治区 - 壮族）、行政级别（如：广西壮族自治区 - 自治区）、行政代码（基本对应身份证号码前6位）、区号、排序
* STANDARD 版 - 标准数据，包括：ID、名称、父 ID、拼音、拼音首字母、拼音首字母集合（如：齐齐哈尔 - qqhe）、行政级别（如：广西壮族自治区 - 自治区）、行政代码（基本对应身份证号码前6位）、排序
* SIMPLE 版 - 标准数据，包括：ID、名称、父 ID、行政代码（基本对应身份证号码前6位）、排序

特别说明
============
* 最新调整的行政区域，行政代码或区号可能不完善，但不影响常规情况使用
* 由于对台湾行政区划不了解，数据不知做得是否合理

数据来源
============
* 行政区划（ [http://www.xzqh.org/](http://www.xzqh.org/){:target="_blank"} ）
* 中华人民共和国国家统计局《最新县及县以上行政区划代码》（截止2012年10月31日）（ [http://www.stats.gov.cn/tjbz/xzqhdm/t20130118_402867249.htm](http://www.stats.gov.cn/tjbz/xzqhdm/t20130118_402867249.htm){:target="_blank"} ）
* 中华人民共和国民政部2018年行政区划代码（ [http://www.mca.gov.cn/article/sj/xzqh/2018/](http://www.mca.gov.cn/article/sj/xzqh/2018/){:target="_blank"} ）
* 百度百科（ [http://baike.baidu.com/](http://baike.baidu.com/){:target="_blank"} ）
* 民政部2019年7月中华人民共和国县以上行政区划代码（ [http://www.mca.gov.cn/article/sj/xzqh/2019/201908/201908271607.html](http://www.mca.gov.cn/article/sj/xzqh/2019/201908/201908271607.html){:target="_blank"} ）
* 民政部2020年2月中华人民共和国县以上行政区划代码（ [http://www.mca.gov.cn/article/sj/xzqh/2020/2020/202003301019.html](http://www.mca.gov.cn/article/sj/xzqh/2020/2020/202003301019.html){:target="_blank"} ）
* 中华人民共和国二〇一六年县级以上行政区划变更情况（ [http://xzqh.mca.gov.cn/description?dcpid=2016](http://xzqh.mca.gov.cn/description?dcpid=2016){:target="_blank"} ）
* 中华人民共和国二〇一七年县级以上行政区划变更情况（ [http://xzqh.mca.gov.cn/description?dcpid=2017](http://xzqh.mca.gov.cn/description?dcpid=2017){:target="_blank"} ）
* 中华人民共和国二〇一八年县级以上行政区划变更情况（ [http://xzqh.mca.gov.cn/description?dcpid=2018](http://xzqh.mca.gov.cn/description?dcpid=2018){:target="_blank"} ）
* 中华人民共和国二〇一九年县级以上行政区划变更情况（ [http://xzqh.mca.gov.cn/description?dcpid=2019](http://xzqh.mca.gov.cn/description?dcpid=2019){:target="_blank"} ）

错误反馈
============
如果您在使用过程中，发现数据有误、遗漏，或已撤销的行政区域但是本数据库中还存在，请联系本人更新。
* 联系人：腾 勇
* E-mail：webmaster@buession.com
* QQ：251329041
"# lazyload"
使用类选择器,尽量避免使用ID选择器定义样式
ID在一个页面中的唯一性导致了如果以ID为选择器来写CSS,就无法重用.

以字母开头
必须以字母开头命名选择器,这样可保证在所有浏览器下都能兼容;
不允许单个字母的类选择器出现;
允许命名带有广告等英文的单词,例如ad,adv,adver,advertising,已防止该模块被浏览器当成垃圾广告过滤掉.
全小写,并使用 - 连字符
下划线 _ 禁止出现在class命名中,统一使用-连字符
禁止驼峰式命名
不要出现-数字连接

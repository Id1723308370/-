# -
数据库

mysql

oracle


HH是24小时制，hh是12小时制

区别就是：大写的H是二十四小时制的小时数(0-23)，小写的h是十二小时制的小时数(am/pm 1-12)


//24小时制
SimpleDateFormat sdf = new SimpleDateFormat("yyyy-MM-dd HH:mm:ss");
//12小时制
SimpleDateFormat sdf1 = new SimpleDateFormat("yyyy-MM-dd hh:mm:ss");
String date1 = "2017-04-23 16:45:12";
Java里面MM表示月 mm表示分钟 HH表示 24小时制 hh表示12小时制
Oracle里面 mm表示月 mi表示分钟 hh24表示小时

mm与m等，它们的区别为是否有前导零：H,m,s表示非零开始，HH,mm,ss表示从零开始。
比如凌晨1点2分，HH:mm显示为01:02，H:m显示为1:2。

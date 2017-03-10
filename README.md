第一个测试
Pattern p = Pattern.compile("abc");
Matcher m = p.matches("-----abc----");
System.out.println(m.find());//true

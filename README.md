# Period2016-8-26
经期推算的工具类，可以推算月经期、安全期和排卵期；并可以手动设置开始和结束

经期推算的原则：
1、默认按照30推算,遵循前7后8的原则（来月经之前的7天和月经结束后的8天是安全期，其余时间为危险期）；
2、如果经期（月经的相隔天数）小于或者大于30，按照等比例计算；
3、只保留最近一次的设置的推算结果，新的设置会把旧的值替换掉。

开始和结束（按照时间判断推算）：
1、如果超过今天，不显示“月经开始”和“月经结束”的按钮；

2、如果没有设置经期开始和结束，点击日期后显示“月经开始”和“月经结束”的按钮，点击后记录开始或者结束的日期；

3、有开始和结束时间
  3-1、选中的日期为月经开始日，点击“经期开始”只保留经期结束日期，其他变成默认；点击“经期结束”把当前的点击日期变成
  结束日期，其余变成默认；
  3-2、选中的日期为月经结束日，点击“经期开始”只保留经期开始日期，其他变成默认；点击“经期结束”只保留经期开始日期，
  其他变成默认；
  3-3、点击的时间在经期内，修改对应的周期长度和开始结束时间，并推算新的日期；
  3-4、点击的时间在经期的开始的前7天，点击“经期开始”，把经期开始的日期推长，结束日期不变；点击“经期结束”，
  只保留经期结束的日期，其余变成默认；
  3-5、点击的时间在经期结束的后8天，点击“经期结束”，把经期结束的日期推长，开始日期不变；点击“经期开始”，
  只保留经期开始的日期，其余变成默认；

4、只设置了经期开始的时间，显示“月经开始”和“月经结束”的按钮
  4-1、选中时间小于当前日期，点击“月经结束”，提示用户月经结束时间需要大于月经开始时间；点击“月经开始”，把开始的
  时间提前到点击的时间；
  4-2、选中的时间等于当前日期，点击”月经开始“，把当前的日期取消；点击”月经结束“，把经期开始变成经期结束；
  4-3、选中的时间大于当前日期，点击”月经开始“，推迟开始的日期；点击”月经结束“，计算整个周期。

5、只设置了结束时间，显示“月经开始”和“月经结束”的按钮
  5-1、选中的时间小于当前日期，点击”经期开始“，推算整个经期；点击经期结束，把点击的日期设置成经期结束；
  5-2、选中的时间等于当前日期，点击”经期开始“，把点击日期设置成开始日期；点击经期结束，取消选择的日期；
  5-3、选中的时间大于当前日期，点击”经期开始“，提示时间要小于月经结束日期；点击月经结束重新设定经期的日期。





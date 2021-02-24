---
layout: post
title: Introduce
categories: [introduce, dev, diary, recruit, reference]
tags: [소개, ryan, setup]
comments: true
---

**멀티콘셉트**가 되고 싶은 개발자.  

**개발자의 삶이 된 날짜 ** = LocalDate devStartDate = LocalDate.of(2016,12,05);
 

 {% highlight sql %}
SELECT 
	CASE 
		WHEN BETWEEN TO_DATE('2016-12-05', 'YYYY-MM-DD') AND TO_DATE('2018-12-12', 'YYYY-MM-DD') THEN '디지털다임'
		WHEN BETWEEN TO_DATE('2018-12-19', 'YYYY-MM-DD') AND TO_DATE(SYSDATE, 'YYYY-MM-DD') THEN '동원홈푸드'
	ELSE '스터디 하드'
       END AS CAREER
  FROM RYAN
 WHERE NAME = '이승준'
{% endhighlight %}

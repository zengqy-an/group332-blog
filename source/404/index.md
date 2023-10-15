---
title: 404 - RollBack
date: 2023-01-24 19:51:13
comments: false
permalink: /404.html
---

<!-- markdownlint-disable MD039 MD033 -->

## 这是一個不存在的页面

对不起，该页面还木有开始建设哦.......😎

预计将在约 <span id="timeout">10</span> 秒后返回首页。

当然，你也可以 **[点这里](https://www.332.group/)** 直接返回首页。


<script>
let countTime = 10;

function count() {

  document.getElementById('timeout').textContent = countTime;
  countTime -= 1;
  if(countTime === 0){
    location.href = 'https://www.332.group/';
  }
  setTimeout(() => {
    count();
  }, 1000);
}

count();
</script>


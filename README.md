# PerformanceNoticeTool
研究生教务系统出成绩通知的小工具   
这几天开始出期末成绩，异常焦虑，时不时上去看看有木有出新的，太麻烦，正好前段时间学了学Python，就写了这个小工具，既能练手也实用。  

---
## 主流程： 
模拟浏览器登录教务系统->保留会话标记->定时器抓取相应网页并分析出成绩信息->筛选新出的成绩信息->发邮件通知   


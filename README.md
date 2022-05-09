# SpringbootSchoolShop
changed from https://github.com/codingxin/OnlineSchoolShop

## 部署
1. 安装mysql，推荐docker:`docker run --name mysqldemo -e MYSQL_ROOT_PASSWORD=123  -p 3306:3306 mysql`
2. mysql中创建schema:
   ```
   mysql mysql -h 127.0.0.1 -uroot -p
   > create schema db_shopmaster;
   ```
3. 执行patch.sql
4. java执行com.zhang.ssmschoolshop.SpringbootSchoolShopApplication.main

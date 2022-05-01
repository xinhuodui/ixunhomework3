# 三.uml设计
## 3.1 类图
![](https://img2022.cnblogs.com/blog/2836063/202205/2836063-20220501113659910-1589624432.png)

## 3.2 活动图
![](https://img2022.cnblogs.com/blog/2836063/202205/2836063-20220501113720058-1570004835.png)

# 四.接口设计

| 接口名                  | 接口说明 | 请求方法 | 请求数据 | 返回数据 |
| ----------------------- | -------- | -------- | -------- | -------- |
| api/good/losing/add     | 添加寻物 | put      | id       | id       |
| api/good/losing/delete  | 删除寻物 | delete   | id       | id       |
| api/good/seeking/delete | 删除失物 | delete   | id       | id       |
| api/good/seeking/add | 添加寻物 | put      | id       | id       |

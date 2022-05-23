# SaleAppServer
可一键部署的商品销售APP，服务器使用dotnet core 3.1

集合了众多功能：

*商品上传

*商品上架\下架管理

*购物车功能

*支付宝接入

*销售数据统计

*卡包

*会员付费功能

*收藏订阅

*提现功能 <br>

部署方法：

#!/bin/bash <br>
cd ../publish <br>
echo "Pulling from repository..." <br>
sudo sudo git pull <br>
sudo docker stop $(sudo docker ps -aq)&&sudo docker rm $(sudo docker ps -aq)&&sudo docker images <br>
sudo docker image rm publish_web <br>
sudo docker-compose up -d <br>


demo地址

安卓下载

<img src="https://user-images.githubusercontent.com/7734782/167329844-48e13fbe-34c7-421b-b0ad-fda75128342d.png" width="200" />

ios下载

<img src="https://user-images.githubusercontent.com/7734782/167329927-78605bb3-4ebc-42f7-91da-a3d355af9ed6.jpg" width="200" />

APP预览

<img src="https://user-images.githubusercontent.com/7734782/167329360-897dd811-9649-4cb0-acc7-380ab526f817.jpg" width="200" />  <img src="https://user-images.githubusercontent.com/7734782/167329365-c4596a6e-3974-4c5a-959e-0a60a0f0b8c9.jpg" width="200" />  <img src="https://user-images.githubusercontent.com/7734782/167329385-1bc2e2a4-0b45-4bee-838d-a54a2815505c.jpg" width="200" />


<img src="https://user-images.githubusercontent.com/7734782/167329391-f5c4b9e0-41ae-42a1-aeae-54442cc07bf4.jpg" width="200" />  <img src="https://user-images.githubusercontent.com/7734782/167329394-ed4837bb-803a-401d-934e-ad541f016858.jpg" width="200" />  <img src="https://user-images.githubusercontent.com/7734782/167329400-7e28858c-8a53-40d5-aa0b-2c4f629be725.jpg" width="200" />

<img src="https://user-images.githubusercontent.com/7734782/167329403-ed195b05-95c2-49dc-bf15-f7c5f53b913b.jpg" width="200" />  <img src="https://user-images.githubusercontent.com/7734782/167329406-9388cb2e-97fc-469f-91a1-030fde130324.jpg" width="200" />  <img src="https://user-images.githubusercontent.com/7734782/167329415-3c85af9f-97e1-4d88-8b82-c1dd75531963.jpg" width="200" />

合作详询

<img src="https://user-images.githubusercontent.com/7734782/167332304-7535f846-69c5-4bb5-a6ef-19793e23ffb3.jpg" width="200" />



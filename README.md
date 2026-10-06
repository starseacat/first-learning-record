# first-learning-record
blender基础复习
<img width="1280" height="795" alt="image" src="https://github.com/user-attachments/assets/b35f6131-b815-4478-9b84-cc371689f509" />
本项目为blender基础复习练习，已在AI指导下完成山中小屋的初步白模搭建。
此前已跟随B站小狐狸入门教程完成一遍流程学习，因基础操作尚不熟练，现采用“关闭视频教程+AI辅助引导”的方式，重新完整走一遍基础制作流程，巩固知识点。（知识点1：应用缩放物体）
<img width="1051" height="751" alt="image" src="https://github.com/user-attachments/assets/c1ea904d-b780-4b8b-8cdf-f0812bbd1457" />
屋顶：最初两个立方体演变，调试复杂：一个立方体加上倒角再向上移动中间线，建成房顶

窗口、门口：布尔差值加集合法

窗框、门框：最初上下左右四个长方体，调试复杂：平面用内插再删面。所遇问题：调尺寸时物体跟着移动；删平面时尺寸没弄好，导致窗框与窗口不贴合。（知识点2：物体围绕原点进行缩放，设置原点至几何中心）（知识点3：因果关系，果不好改，就改正因；即重新建立方体运用布尔修改窗口、门口大小，具有可修复性）（知识点4：阵列相对偏移））（盲点1：旧版阵列修改器中的物体偏移的旋转不熟练）
<img width="1275" height="797" alt="image" src="https://github.com/user-attachments/assets/35801610-2988-4d8f-b5b9-318a73ebf780" />
（盲点1已解决）物体原点在质心（体积）导致旋转错误，放在物体的一端即可解决

回看了一期小狐狸的视频，记住了实体化和晶格的使用（知识点5：晶格的使用）

<img width="1223" height="768" alt="image" src="https://github.com/user-attachments/assets/5e185ddb-5584-4f7e-a699-8714a568f780" />
增加节点：山体偏黄，与房子不搭，可直接增加“色相/饱和度/明度”节点进行调整，无需重新找材质（知识点6：节点的认识）

<img width="1920" height="1080" alt="清晨" src="https://github.com/user-attachments/assets/2f2b5b9f-5b28-464e-ab51-d47322fe26d1" />
<img width="1920" height="1080" alt="黄昏" src="https://github.com/user-attachments/assets/1e951fa7-6a1a-4542-9b31-37fb7a8e633f" />
<img width="1920" height="1080" alt="傍晚" src="https://github.com/user-attachments/assets/081d335f-1ffb-4c86-80ed-c1f7b2d335f6" />

视图≠渲染：渲染时布尔运算的物体、月亮光太阳光一起出现，只是隐藏物体没有作用，放进集合中，右键、可见性、渲染中禁用，即可解决问题（知识点7：视图≠渲染）

清晨：日光，强度2.42，角度3°，旋转x75°、y0°、z45°；
黄昏：日光，强度2.5，角度8°，旋转x65°、y0°、z45°；
傍晚：日光，强度1.27，角度8.5°，旋转x88°、y0°、z-16°；
各时间段的世界环境颜色、强度也均不同

blender的复习回顾就到这里，明天开始进入正题：UE5的学习！

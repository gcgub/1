<！doctype html>
<超文本标记语言朗="zh-CN">
<头>
<元字符集="UTF-8">
<元姓名="视口" 内容="宽度=设备宽度，初始比例=1.0">
<标题>二月和琪琪</标题>
<风格>
*{ 边缘: 0; 填充: 0; 箱体尺寸: 边框框; }
身体{
宽度：100VW；高度：100VH；
显示：弯曲；justify-content：中心；对齐项目：中心；
背景色：#0a0c18；
字体系列: "微软雅黑", "苹方", 无衬线;
溢出: 隐藏的; 位置: 相对的;
        }
.stars{位置：绝对的；顶端：0；左：0；宽度：100%；高度：100%；Z指数：1；}
.text{
位置：相对的；Z指数：2；
字体大小：夹紧(48px，12VW，72px)；字体粗细：700；
字母间距：8px；
/*蓝紫自动渐变*/
背景：线性梯度(270deg，#96bfff，#8e7fff，#c8c2ff，#96bfff)；
背景尺寸: 400% 400%;
-webkit-background-clip：文本；背景剪辑：文本；颜色：透明的；
动画：梯度8s缓解无限的；
            /*紫系同色描边+蓝紫发光*/
-webkit-text-stroke:1PX#c8c2ff；
文本阴影：0015px RGBA(150,191,255,0.7),
0030px RGBA(142,127,255,0.6),
0045PX RGBA(200,194,255,0.5);
过渡：改变0.5s缓解，文本阴影0.5s缓解；
        }
/*悬浮：放大+轻旋+发光增强 */
.text：盘旋{
改变：规模(1.1)旋转(2deg)；
文本阴影：0010px RGBA(150,191,255,0.9),
0025px RGBA(142,127,255,0.8),
0040px RGBA(200,194,255,0.7),
0060px RGBA(150,191,255,0.5);
        }
@keyframes 梯度{0%{背景位置：0%50%；}50%{背景位置：100%50%；}100%{背景位置：0%50%；}}
@keyframesstarTwinkle{0%，100%{不透明度：0。4；改变：翻译(0，0)规模(1)；}50%{不透明度：1；改变：翻译(6px，-6PX)规模(1.3)；}}
</风格>
</头>
<身体>
<div班级="星星"身份标识="星星"></div>
<div班级="文本">二月和琪琪</div>
<脚本>
常数stars=document.getElementById('stars')；
常数Starcount=90；
for(让i=0；i<Starcount；i++){
常量star=document.createElement('div')；
star.style.position='绝对'；
star.style.top='${Math.random()*100}%'；
star.style.left='${Math.random()*100}%'；
常数大小=math.random()*3+1；
star.style.width='${size}px'；
star.style.height='${size}px'；
star.style.backgroundColor='#c8c2ff'；//紫星光
star.style.borderRadius='50%'；
star.style.opacity='0.4'；
常数持续时间=math.random()*12+8；
常数延迟=math.random()*8；
star.style.animation='starTwinkle${duration}s轻松进出无限${delay}s'；
stars.appendChild(star)；
        }
</脚本>
</身体>
</超文本标记语言>

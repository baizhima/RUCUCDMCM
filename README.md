# MCM2014备战指南

##### 成员：郭安琪(writer)、王绍阳(omnipotent)、卢山(programmer)

**目的： 开心就好，享受比赛过程，得不得奖无所谓，美国大学也不怎么看，主要是借助比赛给大家一点学习新知识的动力.下面介绍的材料数量比较多，也和数学中国这种数学建模论坛上其他“牛人”推荐的差别较大，学多少没有硬性要求。从程序语言的选择到课程的推荐主要都是我的一些认识和思路，也希望你们能完善补充。**

** 口号：数学水平可以没有，逼格不能没有**


1. 团队协同工具使用介绍
	* [够快云库](www.goukuai.cn) URL: www.goukuai.cn
	* 特点：多平台(Mac,PC)兼容的云存储，允许团队合作和版本控制
	* 请接收邮件邀请，下载安装够快云库，查阅团队云库内的资料信息，尝试上传文件和下载文件
	* 云库文件结构
		* 程序、论文、LaTeX三个文件夹，已存放若干学习资料
		* 报名信息.pdf,MCM2014备战指南.pdf

2. 程序部分
	* 程序语言的选择：Matlab, Python(NumPy), R
	* Matlab部分
		* Matlab精于矩阵计算，在图像处理、最优化方面拥有较大优势
		* 预计竞赛用途：数值计算、算法实现、微分方程求解
		* 负责人 王绍阳 协助 卢山
		* 推荐学习材料
			* [Convex Optimization](http://online.stanford.edu/course/convex-optimization-winter-2014) 
				* http://online.stanford.edu/course/convex-optimization-winter-2014
				* 凸优化，介绍最优化方法的课程，开课平台Stanford Online,使用Matlab编写小程序，实现函数最优化.开课时间2014.1.21
			* [Computer Vision](http://vision.stanford.edu/teaching/cs131_fall1314/index.html)
				* http://vision.stanford.edu/teaching/cs131_fall1314/index.html
				* 计算机视觉，介绍图像处理基本算法的课程，Matlab做一些基本图像处理，开课平台Stanford FALL 2013校内课程，lecture notes和programming assignment挂在网页上，很容易自学，开课时间（已过，可以自学）
	* Python部分
		* Python是一门脚本语言，代码优雅美观，写解析文本类、数据提取类程序方便易行，实现速度快
		* 预计竞赛用途：数据格式批量化处理，基本机器学习算法实现
		* 负责人 卢山
		* 推荐学习材料
			* 机器学习实战（云库/程序/机器学习实战英文原版.pdf）
	* R部分
		* R语言是一门偏向统计应用的语言，在经济定量分析、统计回归、绘图等方面有较大优势
		* 预计竞赛用途：绘图（主要用途）、统计分析（次要）
		* 负责人 绘图部分 王绍阳 统计部分 卢山
		* **王绍阳作业 模仿绘图**
			* 模仿绘制学习资料中Statistical Learning的课本中以下图形
				* Fig 2.1 - 2.10
			* 需要提交到云库第一级目录的文件:figure.R
			* 所需数据集 http://www-bcf.usc.edu/~gareth/ISL/data.html
			* 每个图片的样例pdf http://www-bcf.usc.edu/~gareth/ISL/Chapter2/
			* 本作业难度较大，能做多少做多少，至少做出5个
		* 推荐学习材料
			* [R Graphics](https://www.stat.auckland.ac.nz/~paul/RG2e/)
				* https://www.stat.auckland.ac.nz/~paul/RG2e/
				* 课本PDF位置在(云库/程序/R graphics.pdf)LaTeX虽然也有绘图功能，但是应该不方便
			* [Statistical Learning](http://online.stanford.edu/course/statistical-learning-winter-2014) 
				* http://online.stanford.edu/course/statistical-learning-winter-2014
				* 统计学习，介绍比较流行的回归regression和分类classification方法。开课平台Stanford Online,开课时间2014.1.21
				* 课本链接 (云库/程序/An Introduction to Statistical Learning)
				* [课本官网](http://www-bcf.usc.edu/~gareth/ISL/data.html)
					* http://www-bcf.usc.edu/~gareth/ISL/data.html

3. 论文部分
	* 主要是论文的格式，写作的思路方面的学习.这方面我不是很熟悉，主要靠二位去揣摩
	* 我看了一眼去年论文，数学模型完全不会
	* 去年的论文集和官方杂志已经放在(云库/论文)中，各是一个文件夹
	* 负责人 王绍阳 郭安琪
4. LaTeX
	* 负责人 郭安琪
	* 要求 电脑上配置好LaTeX编译环境，能够模仿给定一篇pdf文章样式用LaTeX语言写出来并导出，要求从形式上相似度达到80%以上
	* **郭安琪作业 模仿（云库/论文/2013美国大学生数学建模特等奖论文全集/4_Applied Mathematicians Bake the Best Brownies）中以下页码整页内容**
		* p115(标题页),p118（这一页有个表格）,p120-123(这里有一堆数学公式推导)
		* Due Date 大年三十
		* 需要提交到云库第一级目录的文件
			* brownies.tex(源文件),brownies.pdf(生成文件)
	* 推荐学习资料
		* PDF教程[LaTeX Tutorials A Primer](http://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf)
			* http://www.tug.org/twg/mactex/tutorials/ltxprimer-1.0.pdf
		* 网页教程[Getting Started with LaTeX](http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/)
			* http://www.maths.tcd.ie/~dwilkins/LaTeXPrimer/
		* 快速参考资料[LaTeX Math Symbols](http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html)
			* http://web.ift.uib.no/Teori/KURS/WRK/TeX/symALL.html
	
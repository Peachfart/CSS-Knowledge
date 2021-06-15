## 2.1 CSS基础语法
### 2.1.1 CSS构造规则
		selector{property: value}
		选择符(selector)
			如：<body>、<table>、<p>等
		属性(properties)
		属性值(value)
			如果定义选择符的多个属性，则属性与属性值为一组，组与组之间用分号隔开(;)
				如：selector{property1: value1;property2: value2;...}
### 2.1.2 CSS的注释
		/* 注释内容 */
			如：
				/* body定义 */
				.body{
					text-align:center; margin:0 auto;
				}
## 2.2 CSS的常用选择器
### 2.2.1 标签选择器
		tagName{property: value}
			tagName表示标记名称，如p、h1等HTML标记，property表示CSS属性，value表示CSS属性值。
### 2.2.2 类(class)选择器
		.classValue{property: value}
			classValue是选择器等名称，具体名称由CSS定制者自己命名
### 2.2.3 ID选择器
		#idValue{property: value}
			idValue是选择器名称，可以由CSS定义者自己命名
### 2.2.4 选择器声明
		1、集体声明
			如：h1,h2,h3{
				color: red;
				font_size: 20px
				font-weight: bolder;
			}
		2、嵌套声明
			如；<p>与</p>中包含<a></a>标记时，就可以使用嵌套声明方式
				p a{color: red;font_size: 30px;}
				
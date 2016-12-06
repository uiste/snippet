## 简介

Snippets are smart templates that will insert text for you and adapt it to their context. Snippet 是插入到文本中的智能模板并使这段文本适当当前代码环境. 程序员总是会不断的重写一些简单的代码片段, 这种工作乏味/无聊, 而Snippet的出现会让Code更加高效.


## 简要介绍一下snippet四个组成部分:

`content`:其中必须包含<![CDATA[…]]>,否则无法工作, Type your snippet here用来写你自己的代码片段
`tabTrigger`:用来引发代码片段的字符或者字符串, 比如在以上例子上, 在编辑窗口输入hello然后按下tab就会在编辑器输出Type your snippet here这段代码片段
`scope`: 表示你的代码片段会在那种语言环境下激活, 比如上面代码定义了source.python, 意思是这段代码片段会在python语言环境下激活.
`description` :展示代码片段的描述, 如果不写的话, 默认使用代码片段的文件名作为描述

## snippet环境变量

`$TM_FILENAME`	用户文件名
`$TM_FILEPATH`	用户文件全路径
`$TM_FULLNAME`	用户的用户名
`$TM_LINE_INDEX`	插入多少列, 默认为0
`$TM_LINE_NUMBER`	一个snippet插入多少行
`$TM_SOFT_TABS`	如果设置translate_tabs_to_spaces : true 则为Yes
`$TM_TAB_SIZE`	每个Tab包含几个空格

## 以下个人开发过程常用快捷键

### ThinkPHP

>`uiste`	控制器
`mod`	模型
`pf`	public function index(){}
`ww`	$this->
`suc`	$this->success('处理成功！', U('lst'));
`err`	$this->error('处理失败！');
`ass`	$this->assign('', $data);
`dis`	$this->display();
`ss`	// 
`aa`	/**
`gn`	/**********功能************/
`hh`	header('Content-Type:text/html;charset=utf-8');



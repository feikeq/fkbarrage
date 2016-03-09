FKbarrage
=========
FK_html_JS弹幕效果jQuery插件

/*! FKbarrage v1.2 | FeikeWrold | www.fk68.net */


#初始化
    var barrage =$('#feikeq').fkbarrage({
        ratio:4, //单个文字在屏幕中的占比（ratio:4 幕宽度的 4%）
        style:'border:1px solid red;', //自定义弹幕外层DIV样式
        speed:15000 //从左至右的速度
    });

#使用
	barrage.pusshtxt('<img src="头像" style="width:4vw;height:4vw;border-radius: 4vw;vertical-align: top;">字幕文字','其它CSS样式[可选]');

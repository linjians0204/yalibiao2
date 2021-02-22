

<!DOCTYPE html >
<html lang="en">

<script>
    var jypath = '/chos';
</script>
<script src="/chos/static/js/common/richTexts.js"></script>
<script src="/chos/static/js/common/util.js"></script>
<link type="text/css" rel="stylesheet" href="/chos/static/css/system/system/global.css" />
<head>
	<style>
	div{
		width:96%;
		padding:0 2%;
		height:85px;
		border-bottom:1px solid #999;
	}
	p{
		line-height:85px!important;
		/*font-size:37px!important;*/
        font-size:32px;
		margin:0;
		padding:0;
	}
	p span,
	p span p{
		display:inline-block;
		width:70%;
	}
	p span p font,
	p span p font font,
	p span font font font{
		font-size:32px;
	}
	font{
		margin-right:5%;
	}
	#ggxh font{
		margin-right:0px;
	}
	.overflowSty{
		white-space: nowrap;
	    overflow-x: scroll;
	    display:inline-block;
	    height:80px;
	}
	.addAlignVertical{
		vertical-align: text-bottom;
	}
    .fixedWidth{width:600px;}
	</style>
</head>
<body>  
		<div style="display:none;" id="Dclfw">{"richText":[{"style":{"font":"14.6667px \"Times New Roman\"","foreColor":"rgb(0, 0, 0)","textDecoration":0},"text":"/"}]}</div>
		<div style="display:none;" id="Djltx">{"richText":[{"style":{"font":"16px \"Times New Roman\"","foreColor":"rgb(0, 0, 0)","textDecoration":0},"text":"合格"}]}</div>
		<div style="display:none;" id="Dggxh">{"richText":[{"style":{"font":"14.6667px \"Times New Roman\"","foreColor":"rgb(0, 0, 0)","textDecoration":0},"text":"Y-60/（0～16）bar"}]}</div>
		<div style="display:none;" id="Dypmc">轮胎压力表</div>
		<div style="display:none;" id="jcjg1"></div>
		<div><p><font color="green" class="addAlignVertical">委托单位:</font> <span class="overflowSty">聊城万达机动车检测有限公司</span></p></div>
		<div><p><font color="green" class="addAlignVertical">单位地址:</font> <span class="overflowSty">聊城</span></p></div>
    	<div><p><font color="green" class="addAlignVertical">证书单位:</font> <span class="overflowSty">聊城万达机动车检测有限公司</span></p></div>
    	<div><p><font color="green">联&nbsp;&nbsp;系&nbsp;&nbsp;人:&nbsp;</font>王磊</p></div>
    	<div><p><font color="green">联系电话:</font> 18063558785</p></div>
    	<div><p><font color="green" class="addAlignVertical">样品名称:</font> 轮胎压力表<span id="ypmc" class="overflowSty"></span></p></div>
    	<div><p><font color="green" class="addAlignVertical">条&nbsp;&nbsp;形&nbsp;&nbsp;码:</font><span class="overflowSty fixedWidth">210018251984</span></p></div>
    	<div><p><font color="green" class="addAlignVertical">规格型号:</font> Y-60/(0~16)bar<span id="ggxh" class="overflowSty"></span></p></div>
    	<div><p><font color="green" class="addAlignVertical">出厂编号:</font>/<span class="overflowSty">/</span></p></div>
    	<div><p><font color="green" class="addAlignVertical">测量范围:</font>/<span id="clfw" class="overflowSty"></span></p></div>
    	<div><p><font color="green" class="addAlignVertical">计量特性:</font> 合格<span id="jltx" class="overflowSty"></span></p></div>
    	<div><p><font color="green">强检类型:</font> 非强检</p></div>
    	<div><p><font color="green">检测类型:</font> 校准</p></div>
    	<div><p><font color="green">检&nbsp;&nbsp;定&nbsp;&nbsp;员:</font> 张堂慧</p></div>
    	<div><p><font color="green" class="addAlignVertical">备&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;注:</font> /<span class="overflowSty fixedWidth"></span></p></div>
    	<div><p><font color="green" class="addAlignVertical">证&nbsp;&nbsp;书&nbsp;&nbsp;号:</font> <span class="overflowSty fixedWidth">21000999486</span></p></div>
    	<div><p><font color="green">检测日期:</font> 2021-01-07</p></div>
		
		<div><p><font color="green">检测状态:</font> 已检完</p></div>
		<div><p><font color="green">委托日期:</font> 2021-02-22</p></div>
</body>
<script>

	 window.onload = function () {debugger;
    	var	clfw=document.getElementById("Dclfw").innerHTML;
			clfw=changeBackString(RICHTEXT.JsonToHtml(clfw));
			document.getElementById("clfw").innerHTML=clfw.replace(/<p>/g,"").replace(/<\/p>/g,"");
		var	jltx=document.getElementById("Djltx").innerHTML;
			jltx=changeBackString(RICHTEXT.JsonToHtml(jltx));
			document.getElementById("jltx").innerHTML=jltx.replace(/<p>/g,"").replace(/<\/p>/g,"");
		var	ggxh=document.getElementById("Dggxh").innerHTML;
		 	ggxh=changeBackString(RICHTEXT.JsonToHtml(ggxh))
			document.getElementById("ggxh").innerHTML=ggxh.replace(/<p>/g,"").replace(/<\/p>/g,"");
		var	ypmc=document.getElementById("Dypmc").innerHTML;
		 	ypmc=changeBackString(RICHTEXT.JsonToHtml(ypmc))
			document.getElementById("ypmc").innerHTML=ypmc.replace(/<p>/g,"").replace(/<\/p>/g,"");
		var	jcjg=document.getElementById("jcjg1").innerHTML;
		 	jcjg=changeBackString(RICHTEXT.JsonToHtml(jcjg))
			document.getElementById("jcjg").innerHTML=jcjg.replace(/<p>/g,"").replace(/<\/p>/g,"");
	}; 
</script>

</html>

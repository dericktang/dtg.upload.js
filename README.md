=============

ajax上传文件，支持 jquery.js和zepto.js 

=============

调用方法：

var text = $("#name");
var file = $("#pic");
$.ajaxUpload({data:[text],file:[file],url:'d13/getQuestionList.w',success:function(rs){
		alert(rs);
},error:function(e){
		alert(e);
}});

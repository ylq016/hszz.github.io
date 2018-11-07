<html>
  <head><title>会员查询</title></head>
  <body>
    <h1>仿findmima制作，简单数据库录入与查询</h1>
     <div class="jumbotron">
      <div  style="margin:0 auto;width: 1000px;"><br>
			<div class="h6">
			  <div class="jumbotron search-box">
  <p><span class="input-group">
    
  </span><span class="input-group">
  <select class="btn btn-success" id="match_act" name="match_act">
    <option value="1" selected="">模糊查询</option>
    <option value="2">精确查询</option>
  </select>
 
  <select class="btn btn-primary" id="select_act" name="select_act">
    <option class="btn-group" value="3" selected="">姓名或日期</option>
    <option  class="btn-group" value="1">姓名</option>
    <option class="btn-group" value="2">日期</option>
  </select>
  </span></p>
  <div id="jshint-pitch" class="alert alert-info scan-wait" style="display:none;margin-top:10px;font-size:14px">
   
  </div>
  <div id="scan-result-box" style="font-size:12px;">
    <div class="input-group"><span class="input-group-btn scan-but-span">
      <button type="button" class="btn btn-success" onClick="getdata();">查询</button>
      </span>
      <input value="<?php echo date('Y-m-d');?>"  name="key" class="form-control" id="key" >
    </div>
</div>
</body>
</html>

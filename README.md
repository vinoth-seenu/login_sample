
java148SitePoint MemberMar '122 
I want to make a login page, simple, centralized and professional style. but failed. please see the attached screenshot. how to fix it ?

Thanks

<html>
<head>	
<title>Accounting</title>
</head>
<body>

<div align="center">
${param.errorMsg}
<form action="<c:url value='main.do'/>" method="post">

<div style="margin-top:200px;margin-bottom:10px;">
<span style="width:500px;color:blue;font-size:30px;font-weight:bold;border-bottom:1px solid blue;">Accounting System</span>
</div>
<div style="margin-bottom:5px;">

<span style="width:100px;">Name</span>
<input style="width:150px;" type="text" name="name" id="name" value="Mike">

</div>
<div><span style="width:100px;">password</span><input style="width:150px;" type="password" name="password" id="password" value="">


</div>

 <input type="submit" value="Login"></form>
</div>
</body>
</html>

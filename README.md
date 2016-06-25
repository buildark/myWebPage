# myWebPage
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Lesson 11 - Form Validation and other Future HTML5 Form Enhancements</title>
  <style type="text/css" media="all">
    span {
      width: 175px;
      display:block;
      float:left;
    }
    input {
      float:left;
    }
    p {
      padding-top:10px;
      clear: all;
    }
    h2 {
      padding-top:20px;
      clear: all;
    }
    label {
      padding-right:20px;
    }
  </style>
</head>
<body>

<h1>Creating Forms</h1>

<form method="POST" action="form.aspx">

<p><label><span>Email Input:</span><input type=email  name=emailInput required </label></p>
<p><label><span><span>URL Input:</span></span><input type=url name=urlInput  required </label>This is my urlline</p>

<p><label><span>Step Number:</span><input type=number  step=2 </label>Number mo dapat by 2's</input></p>



<p><button>Submit</button></p>

</form>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<title>Register</title>
	<style type="text/css">
		body {
    margin: 0
}


.page-content {
    width: 65%;
    margin: 0 auto;
    background: #ffffff;
    display: flex;
    display: -webkit-flex;
    justify-content: center;
    -o-justify-content: center;
    -ms-justify-content: center;
    -moz-justify-content: center;
    -webkit-justify-content: center;
    align-items: center;
    -o-align-items: center;
    -ms-align-items: center;
    -moz-align-items: center;
    -webkit-align-items: center;

}

.form-v10-content {
    background: #e2dfdf;
    width: 1100px;
    border-radius: 20px;
    -o-border-radius: 20px;
    -ms-border-radius: 20px;
    -moz-border-radius: 20px;
    -webkit-border-radius: 20px;
    box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.295);
    -o-box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.295);
    -ms-box-shadow: 0 8px 20px 0 rgba(0, 0, 0, 0.295);
    -moz-box-shadow: 0 8px 20px 0 rgba(0,0,0, 0.295);
    -webkit-box-shadow: 0 8px 20px 0 rgba(0,0,0, 0.295);
    margin: 95px 0;
    position: relative;
    font-family: montserrat,sans-serif
}

.form-v10-content .form-detail {
    position: relative;
    width: 100%;
    display: flex;
    display: -webkit-flex
}

.form-v10-content .form-detail h2 {
    font-weight: 500;
    font-size: 25px;
    margin-bottom: 34px;
    padding: 33px 50px 0 60px
}

.form-v10-content .form-detail .form-left {
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
    width: 100%
}

.form-v10-content .form-detail .form-left h2 {
    color: #000000
}

.form-v10-content .form-detail .form-right {
    width: 100%;
    background: #520606;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px
}

.form-v10-content .form-detail .form-right h2 {
    color: #fcc100
}

.form-v10-content .form-detail .form-group {
    display: flex;
    display: -webkit-flex
}

.form-v10-content .form-detail .form-row {
    position: relative;
    margin-bottom: 24px;
    padding-left: 60px;
    padding-right: 50px
}

.form-v10-content .form-detail .form-left .form-group .form-row.form-row-1 {
    width: 50%;
    padding: 0 12px 0 60px
}

.form-v10-content .form-detail .form-left .form-group .form-row.form-row-2 {
    width: 50%;
    padding: 0 50px 0 12px
}

.form-v10-content .form-detail .form-left .form-group .form-row.form-row-3 {
    width: 73%;
    padding: 0 12px 0 60px
}

.form-v10-content .form-detail .form-left .form-group .form-row.form-row-4 {
    width: 50%;
    padding: 0 50px 0 12px
}

.form-v10-content .form-detail .form-right .form-group .form-row.form-row-1 {
    width: 50%;
    padding: 0 12px 0 60px
}

.form-v10-content .form-detail .form-right .form-group .form-row.form-row-2 {
    width: 100%;
    padding: 0 50px 0 12px
}

.form-v10-content .form-detail select,.form-v10-content .form-detail input {
    width: 100%;
    padding: 11.5px 15px 15px;
    border: 1px solid transparent;
    background: 0 0;
    appearance: unset;
    -moz-appearance: unset;
    -webkit-appearance: unset;
    -o-appearance: unset;
    -ms-appearance: unset;
    outline: none;
    -moz-outline: none;
    -webkit-outline: none;
    -o-outline: none;
    -ms-outline: none;
    font-family: montserrat,sans-serif;
    font-size: 16px;
    box-sizing: border-box;
    -moz-box-sizing: border-box;
    -webkit-box-sizing: border-box;
    -o-box-sizing: border-box;
    -ms-box-sizing: border-box
}

.form-v10-content .form-detail select {
    background: 0 0;
    position: relative;
    z-index: 9;
    cursor: pointer
}

.form-v10-content .form-detail .form-left select {
    color: #000000
}

.form-v10-content .form-detail .form-right select {
    color: #000000
}

.form-v10-content .form-detail .select-btn {
    z-index: 0;
    position: absolute;
    top: 30%;
    right: 11.5%;
    font-size: 18px
}

.form-v10-content .form-detail .form-left .select-btn {
    color: #000000
}

.form-v10-content .form-detail .form-right .select-btn {
    color: #000000
}

.form-v10-content .form-detail .form-group .form-row.form-row-4 .select-btn {
    top: 20%;
    right: 26%
}

.form-v10-content .form-detail .form-right .form-group .form-row.form-row-2 .select-btn {
    top: 20%;
    right: 19%
}

.form-v10-content .form-detail .form-left input {
    color: #000
}

.form-v10-content .form-detail .form-right input {
    color: #000000
}

.form-v10-content .form-detail .form-left input,.form-v10-content .form-detail .form-left select {
    border-bottom: 1px solid #000000
}

.form-v10-content .form-detail .form-left input:focus,.form-v10-content .form-detail .form-left select:focus {
    border-bottom: 1px solid #000000
}

.form-v10-content .form-detail .form-right input,.form-v10-content .form-detail .form-right select {
    border-bottom: 1px solid;
    border-bottom-color: rgba(255, 255, 255, 0.3)
}

.form-v10-content .form-detail .form-right input:focus,.form-v10-content .form-detail .form-right select:focus {
    border-bottom: 1px solid #ffffff
}

.form-v10-content .form-detail .form-right select option {
    background: #4835d4
}

.form-v10-content .form-detail .form-checkbox {
    margin-top: 37px;
    padding: 0 50px 0 60px;
    position: relative
}

.form-v10-content .form-detail .form-checkbox input {
    position: absolute;
    opacity: 0
}

.form-v10-content .form-detail .form-checkbox .checkmark {
    position: absolute;
    top: 1px;
    left: 60px;
    height: 15px;
    width: 15px;
    border: 1px solid #fcc100;
    cursor: pointer
}

.form-v10-content .form-detail .form-checkbox .checkmark::after {
    content: "";
    position: absolute;
    left: 5px;
    top: 1px;
    width: 3px;
    height: 8px;
    border: 1px solid #913535;
    border-width: 0 2px 2px 0;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    transform: rotate(45deg);
    display: none
}

.form-v10-content .form-detail .form-checkbox input:checked~.checkmark::after {
    display: block
}

.form-v10-content .form-detail .form-checkbox p {
    margin-left: 34px;
    color: #e5e5e5;
    font-size: 14px;
    font-weight: 400
}

.form-v10-content .form-detail .form-checkbox .text {
    font-weight: 400;
    color: #fcc100;
    text-decoration: underline
}

.form-v10-content .form-detail .form-right .form-row-last {
    padding-left: 60px;
    margin: 44px 0 10px
}

.form-v10-content .form-detail .form-right .register {
    background: #fcc100;
    border-radius: 25px;
    -o-border-radius: 25px;
    -ms-border-radius: 25px;
    -moz-border-radius: 25px;
    -webkit-border-radius: 25px;
    box-shadow: 0 6px 17px 0 rgba(228, 228, 228, 0.15);
    -o-box-shadow: 0 6px 17px 0 rgba(228, 228, 228, 0.15);
    -ms-box-shadow: 0 6px 17px 0 rgba(228, 228, 228, 0.15);
    -moz-box-shadow: 0 6px 17px 0 rgba(228, 228, 228, 0.15);
    -webkit-box-shadow: 0 6px 17px 0 rgba(228, 228, 228, 0.15);
    width: 180px;
    border: none;
    margin: 6px 0 50px 0;
    cursor: pointer;
    color: #000000;
    font-weight: 700;
    font-size: 15px
}

.form-v10-content .form-detail .form-right .register:hover {
    background: #f7c53c
}

.form-v10-content .form-detail .form-right .form-row-last input {
    padding: 12.5px
}

.form-v10-content .form-detail .form-left input::-webkit-input-placeholder {
    color: #666;
    font-size: 16px
}

.form-v10-content .form-detail .form-left input::-moz-placeholder {
    color: #666;
    font-size: 16px
}

.form-v10-content .form-detail .form-left input:-ms-input-placeholder {
    color: #666;
    font-size: 16px
}

.form-v10-content .form-detail .form-left input:-moz-placeholder {
    color: #000000;
    font-size: 16px
}

.form-v10-content .form-detail .form-right input::-webkit-input-placeholder {
    color: #f2f2f2;
    font-size: 16px
}

.form-v10-content .form-detail .form-right input::-moz-placeholder {
    color: #f2f2f2;
    font-size: 16px
}

.form-v10-content .form-detail .form-right input:-ms-input-placeholder {
    color: #f2f2f2;
    font-size: 16px
}

.form-v10-content .form-detail .form-right input:-moz-placeholder {
    color: #f2f2f2;
    font-size: 16px
}

@media screen and (max-width: 1199px) {
    .form-v10-content {
        margin:95px 20px
    }
}

@media screen and (max-width: 991px) and (min-width:768px) {
    .form-v10-content .form-detail .form-group {
        flex-direction:column;
        -o-flex-direction: column;
        -ms-flex-direction: column;
        -moz-flex-direction: column;
        -webkit-flex-direction: column
    }

    .form-v10-content .form-detail .form-left .form-group .form-row.form-row-1,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-2,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-3,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-4,.form-v10-content .form-detail .form-right .form-group .form-row.form-row-1,.form-v10-content .form-detail .form-right .form-group .form-row.form-row-2 {
        width: auto;
        padding: 0 50px 0 60px
    }

    .form-v10-content .form-detail .select-btn,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-4 .select-btn,.form-v10-content .form-detail .form-right .form-group .form-row.form-row-2 .select-btn {
        right: 15%
    }
}

@media screen and (max-width: 767px) {
    .form-v10-content .form-detail {
        flex-direction:column;
        -o-flex-direction: column;
        -ms-flex-direction: column;
        -moz-flex-direction: column;
        -webkit-flex-direction: column
    }

    .form-v10-content .form-detail .form-right {
        border-top-right-radius: 0;
        border-bottom-left-radius: 10px
    }

    .form-v10-content .form-detail .form-left {
        padding-bottom: 50px
    }
}

@media screen and (max-width: 575px) {
    .form-v10-content .form-detail .form-group {
        flex-direction:column;
        -o-flex-direction: column;
        -ms-flex-direction: column;
        -moz-flex-direction: column;
        -webkit-flex-direction: column
    }

    .form-v10-content .form-detail .form-row,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-1,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-2,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-3,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-4,.form-v10-content .form-detail .form-right .form-group .form-row.form-row-1,.form-v10-content .form-detail .form-right .form-group .form-row.form-row-2 {
        width: auto;
        padding: 0 30px
    }

    .form-v10-content .form-detail .select-btn,.form-v10-content .form-detail .form-left .form-group .form-row.form-row-4 .select-btn,.form-v10-content .form-detail .form-right .form-group .form-row.form-row-2 .select-btn {
        right: 15%
    }

    .form-v10-content .form-detail h2 {
        padding: 33px 30px 0
    }

    .form-v10-content .form-detail .form-checkbox {
        padding: 0 30px
    }

    .form-v10-content .form-detail .form-checkbox .checkmark {
        left: 30px
    }

    .form-v10-content .form-detail .form-right .form-row-last {
        padding-left: 0;
        text-align: center;
        margin: 44px 0 30px
    }
}
	</style>
</head>
<body class="form-v10">
	
<div class="page-content">
<div class="form-v10-content">
<form class="form-detail" action="#" method="post" id="myform">
<div class="form-left">
<h2>REGISTER</h2>
<div class="form-row">
<select name="title">
<option class="option" value="title">Position</option>
<option class="option" value="businessman">Students</option>
<option class="option" value="reporter">Instructor</option>
</select>
<span class="select-btn">
<i class="zmdi zmdi-chevron-down"></i>
</span>
</div>
<div class="form-group">
<div class="form-row form-row-1">
<input type="text" name="first_name" id="first_name" class="input-text" placeholder="First Name" required="">
</div>
<div class="form-row form-row-2">
<input type="text" name="last_name" id="last_name" class="input-text" placeholder="Last Name" required="">
</div>

</div>
<div class="form-row">
<select name="position">
<option value="position">Sex</option>
<option value="director">M</option>
<option value="manager">F</option>

</select>

</div>
<div class="form-row">
<select name="position">
<option value="position">Deparment</option>
<option value="director">BSIT</option>
<option value="manager">BSCRIM</option>
<option value="employee">BSOAD</option>
<option value="employee">BSEDUC</option>
<option value="employee">BSHM</option>

</select>

</div>
<div class="form-row">
<select name="position">
<option value="position">Year Level</option>
<option value="director">1st</option>
<option value="manager">2nd</option>
<option value="employee">3rd</option>
<option value="employee">4th</option>
<option value="employee">5th</option>

</select>

</div>
<div class="form-row">
<select name="position">
<option value="position">Block</option>
<option value="director">Block A</option>
<option value="manager">Block B</option>
<option value="employee">Block C</option>
<option value="employee">Block D</option>


</select>


<span class="select-btn">
<i class="zmdi zmdi-chevron-down"></i>
</span>

</div>
<div class="form-row">
<input type="text" name="schoolid" class="schoolid" id="schoolid" placeholder="School ID" required="">
</div>

<div class="form-group">
<div class="form-row form-row-3">

</div>

<div class="form-row form-row-4">

</select>

<span class="select-btn">
<i class="zmdi zmdi-chevron-down"></i>
</span>
</div>
</div>
</div>
<div class="form-right">
<h2>Create Username & Password</h2>
<div class="form-row">
    <input type="text" name="your_email" id="your_email" class="input-text" required="" pattern="[^@]+@[^@]+.[a-zA-Z]{2,6}" placeholder="Your Email">
</div>
<div class="form-row">
<input type="text" name="username" class="username" id="username" placeholder="Create user name" required="">
</div>
<div class="form-row">
    <input type="text" name="password" class="password" id="password" placeholder="Create password" required="">
    </div>
    <div class="form-row">
        <input type="text" name="repeatepassword" class="repeatepassword" id="repeatepassword" placeholder="Reapeat password" required="">
        </div>


<div class="form-group">
<div class="form-row form-row-1">

</div>
<div class="form-row form-row-2">

</select>
<span class="select-btn">
<i class="zmdi zmdi-chevron-down"></i>
</span>
</div>
</div>
<div class="form-row">
</select>
<span class="select-btn">
<i class="zmdi zmdi-chevron-down"></i>
</span>
</div>
<div class="form-group">
<div class="form-row form-row-1">

</div>
<div class="form-row form-row-2">
</div>
</div>
<div class="form-row">

</div>
<div class="form-checkbox">
<label class="container"><p>I do accept the <a href="#" class="text">Terms and Conditions</a> of your site.</p>
<input type="checkbox" name="checkbox">
<span class="checkmark"></span>
</label>
</div>
<div class="form-row-last">
<input type="submit" name="register" class="register" value="Register">
</div>
</div>
</form>
</div>
</div>

</body>
</html>


<?php
if(isset($_GET['submit'])){
$url='https://www.google.com/recaptcha/api/siteverify';
$privatekey="6Lc6rK4UAAAAALgKLMWA_02sEgnBfx2bT-BrDp4x";
$response=file_get_contents($url."?secret=".$privatekey."&response="$POST['g-recaptcha-response']."&remoteip=".$_SERVER['REMOTE_ADDR']);
$data=json_decode($response);
if(isset($data->success) AND $data->success==true){
header('Location:Captcha.php?CaptchaPass=True');
}
else{
header('Location:Captcha.php?CaptchaFail=True');
}

}

?>

<!DOCTYPE html>
<html>
  <head>
    <title>reCAPTCHA demo: Simple page</title>
     <script src="https://www.google.com/recaptcha/api.js"></script>
  </head>
  <body>
    <h1>Captcha</h1>
    <?php if(isset($_GET['CaptchaPass'])){ ?>
    <div>Message Sent</div>
    <?php } ?>
    <?php if(isset($_GET['CaptchaFail'])){ ?>
    <div>Captcha Failed. Please try again!</div>
    <?php } ?>
    <form action="https://apistagingref.developer.vodafone.com/oauth2/authorize?">
  <p>Client ID:</p>
  <input type="text" name="client_id" value="client_id">
  <p>Redirect URI:</p>
  <input type="text" name="redirect_uri" value="redirect_uri">
  <p>Response Type:</p>
  <input type="text" name="response_type" value="response_type">
  <p>State:</p>
  <input type="text" name="state" value="state">
  <p>Scope:</p>
  <input type="text" name="scope" value="scope">
  <p>Acr Values:</p>
  <input type="text" name="acr_values" value="acr_values">
  <p>Login Hint:</p>
  <input type="text" name="login_hint" value="login_hint">
      <div class="g-recaptcha" data-sitekey="6Lc6rK4UAAAAAGqlap8ylhIxYzWgvbSEh1kIqr8M"></div>
  <br>
  <input name="submit" type="submit" value="Submit" style="font-size:150%">
</form> 
  </body>
</html>

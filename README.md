# bootstrap-alerts
Dynamic Bootstrap Alerts with Auto Dismiss feature

<h5> Usage: </h5>
<pre>
<script src="https://github.com/sasidhar678/bootstrap-alerts/blob/master/bs_alerts.js"></script>

$("target_div").BSAlert(title, message, options);
</pre>

<h5> Params </h5>
<pre>
title(required) - Alert title 
mesage(required) - Alert message
options(optional)
</pre>

<h5> options </h5>
<pre>
type - Alert type (success | info | danger | warning)

display( object ) - Control alert display position 
  - position: css position property
  - top, bottom, left, right : css values 

href (object) - Hyper links 
  - link
  - text
  - target (optional)
  
autoClose (boolean) : true | false;
duration (number) : duration in milliseconds 
</pre>

<h5> Example </h5>
<pre>
$("body").BSAlert("Hello World", "This is a test message", 
  {
    type: 'success',
    display: {
      position: 'absolute',
      bottom: '20px';
      right: '20px';
    },
    autoClose: true,
    duration: 2000
  }
);
</pre>

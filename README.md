Alert Shake
===

Alert Shake is a jQuery validation plugin that shakes pieces of a form that did not validate similar to Apple's MacBook login screen.

Demo
---

You can view a demo at [http://www.initanna.com/alert-shake/] (http://www.initanna.com/alert-shake/).

Download
---

[Download Alert Shake] (https://github.com/adrazich/alert-shake-jquery/downloads)

Setup
---

###Javascript
```html
<script type="text/javascript">
  $(document).ready(function(){
    $('#demo').alertShake();
	
	// when someone clicks on .submit, proc the alert
	$('.submit').click(function(){
	  $('#demo').alertShake('start');
	});
	
	// to manually make it stop before it's finished, simply
	$('#demo').alertShake('stop');
  });
</script>
```

###Required Files

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js" type="text/javascript"></script>
<script src="alert-shake/js/jquery.alert-shake.min.js" type="text/javascript"></script>
```

Settings
---

<table>
  <tr>
    <th>Parameter</th><th>Type</th><th>Default Value</th><th>Description</th>
  </tr>
  <tr>
	<td>easing</td><td>string</td><td>'linear'</td><td>Easing for animating. If you use something other than 'linear' make sure you include the easing jquery plugin.</td>
  </tr>
  <tr>
	<td>number</td><td>integer</td><td>8</td><td>Number of times you want it to shake.</td>
  </tr>
  <tr>
  	<td>speed</td><td>integer</td><td>10</td><td>Animation duration.</td>
  </tr>
  <tr>
	<td>amount</td><td>integer</td><td>10</td><td>Amount you want it to move in pixels each shake.</td>
  </tr>
</table>

Browser Support
---
Internet Explorer 7+, Firefox, Chrome, Safari

License
---

Copyright (c) 2012 Anna Drazich

Dual licensed under the [MIT] (https://github.com/adrazich/alert-shake-jquery/blob/master/MIT-License.txt) and [GPL] (https://github.com/adrazich/alert-shake-jquery/blob/master/GPL-License.txt) licenses.

###More information about these licenses
  - [MIT License Wiki] (http://en.wikipedia.org/wiki/MIT_License) 
  - [GPL License Wiki] (http://en.wikipedia.org/wiki/GNU_General_Public_License)
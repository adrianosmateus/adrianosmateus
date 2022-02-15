```php
<?php
	$developer = new Developer();
	$developer->name = 'Adriano M. Santos';
	$developer->created_at = '1995-02-28';
	$developer->city = 'São José do Rio Preto';
	$developer->state = 'SP';
	$developer->country = 'Brasil';
	$developer->languages = ['php', 'javascript', 'SQL'];
	$developer->technologies = ['Amazon Web Services', 'MySQL', 'Docker', 'Laravel framework', 'Nginx', 'Linux'];
	$developer->interests = ['Database', 'DevOPS', 'IA', 'ML', 'Data analysis', 'Big Data'];
	$developer->workingAt = ['epics.com.br', 'ulisite.com'];
	$developer->plans = 'Trabalhar com tecnologia pelo resto da vida';
	
	$developer->follow();
?>

```

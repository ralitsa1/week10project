# week10project
<?php namespace Cart\View; ?>

	
	
<div>
	<h1><?= $heading; ?></h1>
<?php foreach($cart['items'] as $item): ?>
	<?= display('item', ['item' => $item]); ?>
<?php endforeach; ?>
</div>

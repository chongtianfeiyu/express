php快递查询API类
===

####demo
	
	require("Express.class.php");
	$a = new Express();
	$result = $a->getorder("全一快递",111309582915);
	var_dump($result);

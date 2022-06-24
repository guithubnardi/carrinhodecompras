<?php
session_start();
?>
<!DOCTYPE html>

<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Carrinho de compras PHP</title>
	<style type="text/css">
		*{margin: 0;padding: 0;box-sizing: border-box; background-color: whitesmoke ;}
		
		h2.title{
			background-color: #069;
			width: 100%;
			padding: 20px;
			text-align: center;
		}

		.carrinho-container{
			display:flex;
			margin-top: 10px;
		}

		.produto{
			width: 33.3%;
			padding: 0 30px;
		}

		.produto img{
			max-width: 100%;
		}

		.produto a{
			display: block;
			width: 100%;
			padding: 10px;
			color: white;
			background-color: darkgreen;
			text-align: center;
			text-decoration: none;
			margin-top: 10px;

		}
	</style>
</head>
<body>
		<h2 class="title">Carrinho com PHP</h2>
<div class="carrinho-container">

<?php


	$items = array(['nome'=>'Livro 1','imagem' => 'livro1.jpg', 'preco' => '30'],
['nome'=>'Livro 2','imagem' => 'livro2.jpg', 'preco' => '30'],
['nome'=>'Livro 3','imagem' => 'livro3.jpg', 'preco' => '30']);

				foreach ($items as $key => $value) {
?>
				<div class="produto">

						<img src="<?php echo $value['imagem']?>" />
						<a href="?adicionar=<?php echo $key ?>">Adicionar o carrinho!</a>

				</div> <!--produto-->

<?php
				 }
?>
</div> <!--carrinho container-->

<?php
	if(isset($_GET['adicionar'])){
		$idProduto = (int) $_GET['adicionar'];
		if(isset($items[$idProduto])){
			if(isset($_SESSION['carrinho'][$idProduto])){
				$_SESSION['carrinho'][$idProduto]['quantidade']++;
				}else{
					$_SESSION[$idProduto] = array('quantidade'=>1,'nome'=>$items[$idProduto]['nome'],'preco'=>$items[$idProduto]['preco']);
				}
				echo '<script>alert("O item não foi encontrado");</scritp>';
		}else{
			die('Você não pode adicionar um item que não existe');
		} 
	}

?>

<h2 class="title">Carrinho</h2>
<?php
		foreach ($_SESSION['carrinho'] as $key => $value) {
			//nome do produto
			//Quantidade
			//preço
			echo '<p>Nome: '.$value['nome'].' | Quantidade: ' . $value ['quanitdae'].' | Preço ' .($value ['quantidade'] *$value ['preco']).'</p>';

		}
?>

</body>
</html>



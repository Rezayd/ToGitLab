<script>
	let leftlogo = 'logo.png';
</script>

<main>
	<div class="header">
		<a href="#default"><img src="/img/logo.png" alt="Logo">
		</a>
		<input type="text" placeholder="Cari Kebutuhanmu...">
	
	</div>

	<ul>
		<li><a class="active" href="#home">Produk Segar</a></li>
		<li><a href="#news">Makanan</a></li>
		<li><a href="#contact">Minuman</a></li>
	</ul>

	

	
</main>

<style>
	.header {
            overflow: hidden;
            background-color: #3b3755;
        
        }
        .header img{
            float: left;
            padding: 20px 20px
        }
        .header input[type=text] {
            float: left;
            padding: 10px ;
            border: 3px black;
            margin-top: 20px;
            margin-left: 100px;
            font-size: 15px;
            width: 40%;
        }

        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #333;
        }

        li {
            float: left;
        }

        li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-family: "verdana";
        }

        .central {
            background-color: rgb(10, 10, 36);
        }

        .central img{
            padding: 50px 50px;
            width: "100%";
        }

        .centered{
            display: block;
            margin-left: auto;
            margin-right: auto;
            width: 50%;
        }

</style>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
 
    <h3 onclick="document.getElementsByTagName('nav')[0].className = 'menu menu_active'">&lt;menu/></h3>
    <nav class="menu">
        <p onclick="document.getElementsByTagName('nav')[0].className = 'menu'">&lt;close/></p>
        <ol>
            <li class="menu-item"><a href="#0">Quem sou EU</a></li>
                    <!--ABRIR OUTRo link, COM SUA ABA souEU-->
            <li class="menu-item">
                <a href="#0">Projetos {</a>
                <ol class="sub-menu">
                    <li class="menu-item"><a target="_blank" href="https://chef-espetos-nordeste.web.app/">Site Profissional;</a></li>
                    <li class="menu-item"><a target="_blank" href="https://github.com/G-Vale?tab=overview&from=2022-07-01&to=2022-07-31">Estudo Diario;</a></li>
                    <li class="menu-item"><a target="_blank" href="#0">Projetos JavaScript;<h2>}</h2></a></li>
                </ol>
            </li>
            <li class="menu-item">
                <a href="#0">Experiência {</a>
                <ol class="sub-menu">
                    <li class="menu-item"><a> HTML5, CSS3, JavaScript; </a></li>
                    <li class="menu-item"><a> React, Bootstrap, SQL; </a></li>
                    <li class="menu-item"><a> Cursando Full Stack; <h2>}</h2></a></li>
                </ol>
            </li>
            <li class="menu-item">
                <a href="#0">Contato{</a>
                <ol class="sub-menu">
                    <li class="menu-item"><a target="_blank" href="https://github.com/G-Vale">Git Hub;</a></li>
                    <li class="menu-item"><a target="_blank" href="https://www.linkedin.com/in/gabriel-vale-a23a7421a/">Linkedin;</li>
                    <li class="menu-item"><a target="_blank" href="https://api.whatsapp.com/send/?phone=5583993112274&text&type=phone_number&app_absent=0" >WhatsApp;<h2>}</h2></a></li>
            </li>
        </ol>
    </nav>
</body>
</html>

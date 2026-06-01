<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Adão Marcenaria - Móveis Planejados</title>

    <!-- Framework W3.CSS -->
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

    <!-- Font Awesome -->
    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>

        /* Cores da empresa */
        .adao-marrom-escuro {
            background-color: #4E342E !important;
            color: white !important;
        }

        .adao-marrom-claro {
            background-color: #D7CCC8 !important;
            color: #4E342E !important;
        }

        .adao-texto-marrom {
            color: #5D4037 !important;
        }

        /* Espaço para sidebar */
        .conteudo-principal {
            margin-left: 200px;
        }

        @media (max-width:600px) {
            .conteudo-principal {
                margin-left: 0;
            }
        }
    </style>
</head>

<body class="w3-light-grey">

    <!-- SIDEBAR -->
    <nav class="w3-sidebar w3-bar-block w3-card adao-marrom-escuro"
        style="width:200px" id="mySidebar">

        <div class="w3-container w3-center w3-padding-16">

            <img src="imagens/logo.png"
                alt="Logo Adão Marcenaria"
                style="width:80%; max-width:120px"
                class="w3-circle">

            <h5>Adão Marcenaria</h5>
            <a href="https://www.instagram.com/vsmmarcenaria/" target="_blank">@vsmmarcenaria
</a>

        </div>

        <button onclick="switchSection('home')"
            class="w3-bar-item w3-button w3-hover-amber">
            <i class="fa fa-home"></i> HOME
        </button>

        <button onclick="switchSection('parceiros')"
            class="w3-bar-item w3-button w3-hover-amber">
            <i class="fa fa-handshake-o"></i> PARCEIROS
        </button>

        <button onclick="switchSection('faq')"
            class="w3-bar-item w3-button w3-hover-amber">
            <i class="fa fa-question-circle"></i> FAQ
        </button>

    </nav>

    <!-- CONTEÚDO PRINCIPAL -->
    <div class="conteudo-principal">

        <!-- ===================================================== -->
        <!-- HOME -->
        <!-- ===================================================== -->

        <section id="home" class="pagina">

            <header class="w3-container adao-marrom-escuro w3-center w3-padding-32">

                <h1 class="w3-jumbo">Adão Marcenaria</h1>

                <p class="w3-xlarge">
                    <i>Transformamos projetos em sonhos realizados.</i>
                </p>

            </header>

            <main class="w3-content w3-container w3-padding-64" style="max-width:900px">

                <h2 class="w3-center adao-texto-marrom">
                    NOSSA HISTÓRIA
                </h2>

                <p class="w3-justify">
                    A Adão Marcenaria é uma empresa especializada em móveis
                    planejados e projetos sob medida. Atendemos a você cliente final, 
                    arquitetos, engenheiros que zelam por compromisso com qualidade, 
                    acabamento e prazo. Há mais de 30 anos no mercado. Nosso objetivo 
                    é criar ambientes modernos, funcionais e elegantes, sempre
                    valorizando os detalhes, o requinte e a excelência em cada
                    projeto realizado.
                </p>

                <!-- Imagem Principal -->

                <section class="w3-center w3-margin-top">

                    <img src="imagens/foto1.png"
                        alt="Móveis Planejados"
                        class="w3-image w3-round w3-card-4"
                        style="max-width:700px; width:100%;">

                </section>

                <!-- Missão Visão Valores -->

                <section class="w3-row-padding w3-margin-top">

                    <section class="w3-third">

                        <div class="w3-card w3-white w3-padding">

                            <h3 class="adao-texto-marrom">
                                Missão
                            </h3>

                            <p>
                                Produzir móveis planejados de qualidade,
                                atendendo às necessidades de cada cliente.
                            </p>

                        </div>

                    </section>

                    <section class="w3-third">

                        <div class="w3-card w3-white w3-padding">

                            <h3 class="adao-texto-marrom">
                                Visão
                            </h3>

                            <p>
                                Ser referência em móveis planejados,
                                destacando-se pela excelência, cumprimento de prazos e satisfação do cliente.
                            </p>

                        </div>

                    </section>

                    <section class="w3-third">

                        <div class="w3-card w3-white w3-padding">

                            <h3 class="adao-texto-marrom">
                                Valores
                            </h3>

                            <p>
                                Compromisso, honestidade, qualidade,
                                pontualidade e respeito ao cliente.
                            </p>

                        </div>

                    </section>

                </section>

            </main>

            <footer class="w3-container adao-marrom-escuro w3-center w3-padding-32">

                <p>
                    <i class="fa fa-envelope"></i>
                    lopes.35@hotmail.com
                </p>

                <p>
                    <i class="fa fa-phone"></i>
                    (11) 95234-9149
                </p>

                <p>
                    <a href="https://instagram.com/vsmmarcenaria"
                        target="_blank"
                        class="w3-text-white">
                        <i class="fa fa-instagram"></i>
                        @vsmmarcenaria
                    </a>
                </p>

                <p>
                    Desenvolvido por Milena © 2026
                </p>

            </footer>

        </section>

        <!-- ===================================================== -->
        <!-- PARCEIROS -->
        <!-- ===================================================== -->

        <section id="parceiros" class="pagina" style="display:none">

            <header class="w3-container adao-marrom-escuro w3-center w3-padding-32">

                <h1 class="w3-jumbo">Adão Marcenaria</h1>

                <p class="w3-xlarge">
                    <i>Transformamos projetos em sonhos.</i>
                </p>

            </header>

            <main class="w3-container w3-content w3-padding-64">

                <h2 class="w3-center adao-texto-marrom">
                    NOSSOS PARCEIROS
                </h2>

                <section class="w3-row-padding w3-margin-top">

                    <section class="w3-half">

                        <div class="w3-card w3-white w3-padding w3-center">

                            <img src="imagens/leo_parceiro.png"
                                alt="Fornecedor MDF"
                                style="width:150px">

                            <h4>Fornecedor MDF</h4>

                        </div>

                    </section>

                    <section class="w3-half">

                        <div class="w3-card w3-white w3-padding w3-center">

                            <img src="imagens/madeecia_parceiro2.png"
                                alt="Fornecedor Ferragens"
                                style="width:150px">

                            <h4>Fornecedor Ferragens</h4>

                        </div>

                    </section>

                </section>

            </main>

            <footer class="w3-container adao-marrom-escuro w3-center w3-padding-32">

                <p>lopes.35@hotmail.com</p>
                <p>(11) 95234-9149 / (11) 94118-3533</p>
                <p>São Paulo - SP</p>

            </footer>

        </section>

        <!-- ===================================================== -->
        <!-- FAQ -->
        <!-- ===================================================== -->

        <section id="faq" class="pagina" style="display:none">

            <header class="w3-container adao-marrom-escuro w3-center w3-padding-32">

                <h1 class="w3-jumbo">Adão Marcenaria</h1>

                <p class="w3-xlarge">
                    <i>Transformamos projetos em sonhos.</i>
                </p>

            </header>

            <main class="w3-container w3-content w3-padding-64">

                <h2 class="w3-center adao-texto-marrom">
                    PERGUNTAS FREQUENTES
                </h2>

                <div class="w3-card w3-margin-bottom">

                    <header class="w3-container adao-marrom-claro">
                        <h4>Quais locais vocês atendem?</h4>
                    </header>

                    <div class="w3-container">
                        <p>
                            Atendemos principalmente a região de São Paulo, mas estamos abertos a projetos em outras localidades mediante análise.
                        </p>
                    </div>
                    
                    <div class="w3-card w3-margin-bottom">

                    <header class="w3-container adao-marrom-claro">
                        <h4>Qual o prazo de entrega?</h4>
                    </header>

                    <div class="w3-container">
                        <p>
                            O prazo médio varia entre 30 e 45 dias,
                            dependendo do projeto.
                        </p>
                    </div>

                </div>

                <div class="w3-card w3-margin-bottom">

                    <header class="w3-container adao-marrom-claro">
                        <h4>Vocês fazem orçamento?</h4>
                    </header>

                    <div class="w3-container">
                        <p>
                            Sim. O orçamento é realizado após a análise
                            das medidas e necessidades do cliente.
                        </p>
                    </div>

                </div>

                <div class="w3-card w3-margin-bottom">

                    <header class="w3-container adao-marrom-claro">
                        <h4>Quais materiais são utilizados?</h4>
                    </header>

                    <div class="w3-container">
                        <p>
                            Trabalhamos com MDF, lâminados, madeira de lei e outros materiais
                            de alta qualidade para móveis planejados.
                        </p>
                    </div>

                </div>

            </main>

            <footer class="w3-container adao-marrom-escuro w3-center w3-padding-32">

                <p>lopes.35@hotmail.com</p>
                <p>(11) 95234-9149 / (11) 94118-3533</p>
                 <p>São Paulo - SP</p>
            </footer>

        </section>

    </div>

    <!-- JAVASCRIPT -->
    <script>

        function switchSection(secao) {

            let paginas =
                document.querySelectorAll(".pagina");

            paginas.forEach(function(item) {
                item.style.display = "none";
            });

            document.getElementById(secao)
                .style.display = "block";
        }

    </script>

</body>
</html>

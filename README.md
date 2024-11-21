<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Universo dos Gatos</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
 
 #form-gato {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    background: #fff;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 600px;
    margin: 20px auto;
}

#form-gato label {
    font-size: 1rem;
    font-weight: bold;
    color: #555;
    align-self: flex-start;
}

#form-gato input,
#form-gato textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 10px;
    font-size: 1rem;
    box-sizing: border-box;
    transition: border-color 0.3s, box-shadow 0.3s;
}

#form-gato input:focus,
#form-gato textarea:focus {
    border-color: #ff7eb9;
    box-shadow: 0 0 5px rgba(255, 126, 185, 0.5);
    outline: none;
}

#form-gato textarea {
    resize: none;
}

#form-gato {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    background: #fff;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    max-width: 600px;
    margin: 20px auto;
}

#form-gato label {
    font-size: 1rem;
    font-weight: bold;
    color: #555;
    align-self: flex-start;
}

#form-gato input,
#form-gato textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 10px;
    font-size: 1rem;    
    box-sizing: border-box;
    transition: border-color 0.3s, box-shadow 0.3s;
}

#form-gato input:focus,
#form-gato textarea:focus {
    border-color: #ff7eb9;
    box-shadow: 0 0 5px rgba(255, 126, 185, 0.5);
    outline: none;
}

#form-gato textarea {
    resize: none;
}

 
 #curiosity-btn {
    background: linear-gradient(120deg, #ff7eb9, #a64277);
    color: white;
    border: none;
    border-radius: 25px;
    padding: 10px 20px;
    font-size: 1rem;
    font-weight: bold;
    cursor: pointer;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s, box-shadow 0.3s;
}

#curiosity-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 10px rgba(0, 0, 0, 0.3);
}

#curiosity-btn:active {
    transform: translateY(1px);
    box-shadow: 0 3px 5px rgba(0, 0, 0, 0.2);
}


        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(120deg, #fbc2eb, #a6c1ee);
            color: #333;
            margin: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 20px;
            background: #ff7eb9;
            color: white;
        }

        .adoption-area {
    padding: 40px 20px;
    background: #ffe3f3;
    border-radius: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    margin: 20px auto;
    max-width: 800px;
}

.adoption-area h2 {
    font-size: 2rem;
    color: #ff7eb9;
    margin-bottom: 15px;
    text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.2);
}

.adoption-area p {
    font-size: 1.1rem;
    color: #555;
    margin-bottom: 20px;
}

.adoption-btn {
    display: inline-block;
    padding: 15px 30px;
    background: linear-gradient(120deg, #ff7eb9, #a64277);
    color: white;
    font-size: 1.2rem;
    font-weight: bold;
    text-decoration: none;
    border-radius: 30px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    transition: transform 0.3s, box-shadow 0.3s;
}

.adoption-btn:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
}

.adoption-btn:active {
    transform: translateY(2px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

        header h1 {
            margin-bottom: 5px;
        }

        nav {
            background: #ffe3f3;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: #ff7eb9;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #a64277;
        }

        .section {
            padding: 30px;
            background: #fff;
            margin: 20px auto;
            border-radius: 15px;
            max-width: 1200px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .section h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .section p, .section ul {
            font-size: 1rem;
            line-height: 1.6;
        }

        .section ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        .products, .breeds {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .card {
            background: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            padding: 15px;
        }

        .card img, iframe {
            max-width: 100%;
            border-radius: 10px;
        }

        .card h3 {
            margin: 10px 0;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #ff7eb9;
            color: white;
            margin-top: auto;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>🐾 Universo dos Gatos 🐾</h1>
        <p>Seu guia completo sobre cuidados, raças, produtos e mais para os amantes de gatos!</p>
    </header>
    <nav>
        <a href="#gallery">Galeria</a>
        <a href="#products">Produtos</a>
        <a href="#breeds">Raças</a>
        <a href="#food">Rações</a>
        <a href="#medicine">Remédios</a>
        <a href="#videos">Vídeos</a>
        <a href="#tips">Dicas Gerais</a>
    </nav>
    <main>
        <section id="gallery" class="section">
            <h2>Galeria de Gatos</h2>
            <div class="products">
                <div class="card">
                    <img src="https://cdn.discordapp.com/attachments/762020889767182356/1308574937690275870/image.png?ex=673fc261&is=673e70e1&hm=5d4dc2ea905476dabf5ccceda14fe72245684d113ea2f8cdd8a97792c1389f32&" alt="Gato 1">
                    <h3>Magali</h3>
                </div>
                <div class="card">
                    <img src="https://cdn.discordapp.com/attachments/810629421848461413/1308947823416311879/image.png?ex=673fcc28&is=673e7aa8&hm=ce0104b12dbd1d3491c6b9b75a3479351936fc3653e4ecd6496a02a3ce8ad056&" alt="Gato 2">
                    <h3>Wilton</h3>
                </div>
                <div class="card">
                    <img src="https://cdn.discordapp.com/attachments/810629421848461413/1308950250941059174/3f6056a4-92e2-4eee-bdf8-0e7bbd7c0a43.png?ex=673fce6a&is=673e7cea&hm=8f20b2e04b8a703eefedc42c1ec902204534d41d85d01407f594e23255936038&" alt="Gato 3">
                    <h3>Canguru</h3>
                </div>
            </div>
        
        </section>

        <section id="meu-gato" class="section">
            <h2>Meu Gato</h2>
            <p>Esta seção é dedicada ao seu gato! Compartilhe com a gente mais sobre ele.</p>
            
            <!-- Formulário de Envio de Foto -->
            <form id="form-gato" action="#" method="post" enctype="multipart/form-data">
                <label for="nome-gato">Nome do Gato:</label>
                <input type="text" id="nome-gato" name="nome-gato" required><br>
        
                <label for="idade-gato">Idade do Gato:</label>
                <input type="number" id="idade-gato" name="idade-gato" required><br>
        
                <label for="raca-gato">Raça do Gato:</label>
                <input type="text" id="raca-gato" name="raca-gato" required><br>
        
                <label for="cor-gato">Cor do Gato:</label>
                <input type="text" id="cor-gato" name="cor-gato" required><br>
        
                <label for="foto-gato">Foto do Gato:</label>
                <input type="file" id="foto-gato" name="foto-gato" accept="image/*" required><br>
        
                <label for="descricao-gato">Descrição do Gato:</label>
                <textarea id="descricao-gato" name="descricao-gato" rows="4" cols="50" required></textarea><br>
        
                <button type="submit">Enviar Foto</button>
            </form>
        
            <ul>
                <li><strong>Nome:</strong> [Nome do Gato]</li>
                <li><strong>Idade:</strong> [Idade do Gato]</li>
                <li><strong>Raça:</strong> [Raça do Gato]</li>
                <li><strong>Cor:</strong> [Cor do Gato]</li>
                <li><strong>Personalidade:</strong> [Personalidade do Gato]</li>
            </ul>
        </section>          

        <section id="products" class="section">
            <h2>Produtos para Gatos</h2>
            <div class="products">
                <div class="card">
                    <img src="https://agropecuariaimarui.com.br/wp-content/uploads/2020/02/06514.jpg" alt="Arranhador">
                    <h3>Arranhador de Gato</h3>
                    <p>Ideal para manter as unhas saudáveis.</p>
                </div>
                <div class="card">
                    <img src="https://images-americanas.b2w.io/produtos/4826456346/imagens/brinquedo-para-gato-interativo-caca-bolinhas-azul/4826456346_1_large.jpg" alt="Brinquedos">
                    <h3>Brinquedos Interativos</h3>
                    <p>Divertem e estimulam o gatinho.</p>
                </div>
                <div class="card">
                    <img src="https://m.media-amazon.com/images/I/6146aVNsMPL._AC_UF1000,1000_QL80_.jpg" alt="Caminha">
                    <h3>Caminha Confortável</h3>
                    <p>Garantia de noites bem dormidas.</p>
                </div>
            </div>
        </section>

        <section id="vaccination" class="section">
            <h2>Calendário de Vacinação e Cuidados</h2>
            <p>É essencial manter as vacinas e cuidados do seu gato em dia para garantir a saúde e bem-estar do seu amigo felino. Confira abaixo o calendário recomendado:</p>
            <table style="width: 100%; border-collapse: collapse; text-align: left;">
                <thead>
                    <tr style="background-color: #ff7eb9; color: white;">
                        <th style="padding: 10px; border: 1px solid #ddd;">Idade do Gato</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Vacinas</th>
                        <th style="padding: 10px; border: 1px solid #ddd;">Cuidados</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd;">6-8 semanas</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">V3 (Tríplice): Proteção contra rinotraqueíte, calicivirose e panleucopenia.</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Primeiro check-up veterinário; vermífugo.</td>
                    </tr>
                    <tr style="background-color: #f9f9f9;">
                        <td style="padding: 10px; border: 1px solid #ddd;">12 semanas</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">V3 (Refôrço) + Vacina contra Leucemia Felina (se necessário).</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Manter antipulgas e vermífugos em dia.</td>
                    </tr>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd;">16 semanas</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Raiva (obrigatória).</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Check-up veterinário geral.</td>
                    </tr>
                    <tr style="background-color: #f9f9f9;">
                        <td style="padding: 10px; border: 1px solid #ddd;">1 ano</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Refôrço anual da V3 e Raiva.</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Exames gerais e avaliação dental.</td>
                    </tr>
                    <tr>
                        <td style="padding: 10px; border: 1px solid #ddd;">Anualmente</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Refôrço anual de todas as vacinas recomendadas pelo veterinário.</td>
                        <td style="padding: 10px; border: 1px solid #ddd;">Check-up, controle de peso e prevenção de doenças.</td>
                    </tr>
                </tbody>
            </table>
            <p style="margin-top: 20px;">⚠️ Lembre-se: as vacinas e cuidados podem variar conforme a região e estilo de vida do gato. Consulte sempre o veterinário para um plano personalizado!</p>
        </section>        

        <section class="adoption-area">
            <h2>Área de Adoção de Gatos</h2>
            <p>Encontre o local mais próximo para adotar um gatinho.</p>
            <a href="https://www.google.com/maps" target="_blank" class="adoption-btn">
                Clique aqui para ver no Google Maps
            </a>
        </section>        

        <section id="breeds" class="section">
            <h2>Raças de Gatos</h2>
            <div class="breeds">
                <div class="card">
                    <img src="https://royalpets.vteximg.com.br/arquivos/ids/177844/maine-coon-500-500-2.jpg?v=637534890770670000">
                    <h3>Maine Coon</h3>
                    <p>Grande e brincalhão, se dá bem com crianças.</p>
                </div>
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5wA9Hl8tOwMRYafdQC4nxjLdN-sr3cyQemw&s" alt="Gato Persa">
                    <h3>Persa</h3>
                    <p>Tranquilo e afetuoso, ideal para ambientes calmos.</p>
                </div>
                <div class="card">
                    <img src="https://cdn2.thecatapi.com/images/13MkvUreZ.jpg" alt="Gato Siamês">
                    <h3>Siamês</h3>
                    <p>Extrovertido e comunicativo, adora atenção.</p>
                </div>
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSSZ5klQ0whDY_2tQqyFiQQplILxL2DNDYoCQ&s" alt="Gato Bengal">
                    <h3>Bengal</h3>
                    <p>Ativo e curioso, com um padrão de pelagem único.</p>
                </div>
                <div class="card">
                    <img src="https://p2.trrsf.com/image/fget/cf/1200/1600/middle/images.terra.com/2024/02/08/500539162-gato-ragdoll.jpg" alt="Gato Ragdoll">
                    <h3>Ragdoll</h3>
                    <p>Comportamento tranquilo e afetuoso, adora ser acariciado.</p>
                </div>
                <div class="card">
                    <img src="https://premierpet.com.br/wp-content/uploads/2024/08/model-banner-sphynx-mobile-v1-1024x1024.png" alt="Gato Sphynx">
                    <h3>Sphynx</h3>
                    <p>Sem pelos, mas cheio de personalidade.</p>
                </div>
            </div>
        </section>

        <section id="food" class="section">
            <h2>Rações para Gatos</h2>
            <ul>
                <li>Ração Seca: Ajuda na saúde dental e é mais prática.</li>
                <li>Ração Úmida: Hidrata e tem alta palatabilidade.</li>
                <li>Ração Natural: Alternativa sem conservantes e mais saudável.</li>
            </ul>
        </section>

        <section id="medicine" class="section">
            <h2>Remédios e Cuidados</h2>
            <p>Consulte sempre um veterinário antes de medicar seu gato. Alguns exemplos comuns de cuidados incluem:</p>
            <ul>
                <li>Antipulgas: Proteção contra pulgas e carrapatos.</li>
                <li>Vermífugos: Prevenção contra parasitas intestinais.</li>
                <li>Vitaminas: Suplementos para gatos com necessidades específicas.</li>
            </ul>
        </section>

        <section id="tips" class="section">
            <h2>Dicas Gerais</h2>
            <p>Confira dicas importantes para garantir o bem-estar do seu gato:</p>
            <ul>
                <li>Garanta que seu gato tenha um ambiente tranquilo e confortável.</li>
                <li>Mantenha a alimentação balanceada e evite excessos.</li>
                <li>Leve seu gato regularmente ao veterinário para check-ups.</li>
                <li>Mantenha a caixa de areia sempre limpa e em local acessível.</li>
                <li>Ofereça brinquedos interativos para estimular o gato física e mentalmente.</li>
                <li>Remova itens perigosos, como plantas tóxicas ou produtos de limpeza, do alcance do gato.</li>
                <li>Forneça água fresca diariamente e considere usar uma fonte para gatos que preferem água corrente.</li>
                <li>Use produtos antipulgas e vermífugos conforme orientação veterinária.</li>
                <li>Respeite o espaço do gato e não o force a interagir se ele não quiser.</li>
                <li>Ofereça esconderijos e locais altos, como prateleiras ou árvores para gatos, para que ele se sinta seguro.</li>
                <li>Crie uma rotina consistente para alimentação, brincadeiras e descanso.</li>
                <li>Evite alimentos tóxicos, como chocolate, cebola, alho ou uvas.</li>
            </ul>
            <p>Com esses cuidados, seu gato será mais feliz e saudável!</p>
        </section>
        
        <section id="curiosity" class="section">
            <h2>Curiosidade do Dia</h2>
            <p id="curiosity-text">Clique no botão para descobrir uma curiosidade sobre gatos!</p>
            <button id="curiosity-btn">Mostrar Curiosidade</button>
        </section>
        
        <script>
            // Lista de curiosidades
            const curiosities = [
    "Os gatos dormem cerca de 70% do tempo de suas vidas.",
    "O ronronar de um gato pode ter efeitos calmantes em humanos.",
    "Cada gato tem uma impressão nasal única, como as digitais humanas.",
    "Gatos não têm clavículas, o que lhes permite passar por espaços estreitos.",
    "O miado dos gatos é usado principalmente para se comunicar com humanos.",
    "Gatos podem fazer mais de 100 sons diferentes, enquanto os cães fazem cerca de 10.",
    "Os gatos têm uma visão excelente no escuro, 6 vezes melhor que a dos humanos.",
    "Gatos possuem uma excelente audição, podendo ouvir sons em frequências muito mais altas que os humanos.",
    "A cauda dos gatos é uma extensão de sua coluna vertebral e é usada para equilíbrio.",
    "Gatos podem saltar até seis vezes a altura do seu corpo."
];
        
            const curiosityText = document.getElementById("curiosity-text");
            const curiosityBtn = document.getElementById("curiosity-btn");
        
            curiosityBtn.addEventListener("click", () => {
                const randomCuriosity = curiosities[Math.floor(Math.random() * curiosities.length)];
                curiosityText.textContent = randomCuriosity;
            });
        </script>
        
    </main>

    <footer>
        <p>&copy; Informações da minha cabeça😎</p>
    </footer>
</body>
</html>

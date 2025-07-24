<script>
    import './base.css';
    import './initial-page.css';
    import './presentation.css';
    import './studies.css';
    import './languages.css';
    import './courses.css';
    import './projects.css';
    
</script>

<!-- Only my name to scroll -->
<div class="initial-page">
    <div class="text">
        <h1>Kaiky Braga</h1>
        <p>DATA SCIENCE STUDENT</p>
    </div>

    <div class="scroll-indicator">
        <div class="arrows">
            <svg class="arrow-icon" viewBox="0 0 24 24" fill="none">
                <path d="M6 9l6 6 6-6" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </div>
        <div class="text">Scroll Down</div>
    </div>
</div>

<!-- Who I am and Contacts -->
<div class="presentation"> 
    <div class="left-presentation">
        <div class="text-presentation">
            <h1>Olá, eu sou Kaiky Braga!</h1>
            <hr>
            <p><b>Um graduando em Ciência de Dados e Inteligência Artificial pela Fundação Getulio Vargas (FGV)</b>, com grande interesse em Machine Learning, estatística (frequentista e bayesiana) e análise de dados. Estou constantemente em busca de novos aprendizados e desafios que ampliem meu conhecimento técnico e prático.</p>
        </div>

        <div class="social-project-link">
            <!-- E-mail -->
            <b>Contato:</b>
            <a href="mailto:kaiky.braga06221607@gmail.com" class="email-link">
                kaiky.braga06221607@gmail.com
            </a>
            <div class="social-images">
                <!-- Linkedin -->
                <a href="https://www.linkedin.com/in/kaiky-braga-8a84962aa/" target="_blank">
                    <img src="linkedin.png" alt="linkedin">
                </a>

                <!-- GitHub -->
                <a href="https://github.com/KaikyBraga" target="_blank">
                    <img src="github.png" alt="github">
                </a>
            </div>
        </div>
    </div>

    <div class="right-presentation">
        <div class="profile-container">
            <div class="profile-border"></div>
            <img src="kaiky_picture.jpg" alt="Kaiky Braga" class="profile-image">
        </div>
    </div>
</div>

<!-- What I am studying now -->
<div class="studies">    
    <div class="studies-wrapper">
        <h1 class="study-title-principal">CAMPOS DE INTERESSE</h1>

        <div class="study-block">
            <div class="studies-row">
                <div class="studies-col" id="studies-col1">
                    <div class="study-heading">
                        <div class="study-icon"><img src="ai.png" alt="ai"></div>
                        <h2 class="study-title">INTELIGÊNGIA ARTIFICIAL</h2>
                    </div>
                    <div class="study-text">Tenho conhecimento na exploração de técnicas de Machine Learning, incluindo aprendizado supervisionado, não supervisionado e aprendizado por reforço. Já realizei projetos diretamente com automatizações utilizando LLMs. Além disso, desenvolvi e participei de trabalhos voltados para clusterização de dados, para identificar padrões e segmentações relevantes em conjuntos de dados reais.</div>
                </div>
                <div class="studies-col" id="studies-col2">
                    <div class="study-heading">
                        <div class="study-icon"><img src="math.png" alt="math"></div>
                        <h2 class="study-title">MATEMÁTICA</h2>
                    </div>
                    <div class="study-text">Tive a oportunidade de aprofundar conhecimentos em diversas e fundamentais áreas da matemática. Isso incluiu a realização de trabalhos envolvendo Modelos Lineares Generalizados na área de Estatística, a aplicação prática de Álgebra Linear em aplicações com imagens, além do uso integrado de conceitos de probabilidade e estatística, tanto na abordagem Bayesiana quanto na Frequentista, para a resolução de desafios complexos e desenvolvimento de modelos matemáticos robustos.</div>
                </div>
            </div>

            <div class="studies-row">
                <div class="studies-col" id="studies-col3">
                    <div class="study-heading">
                        <div class="study-icon"><img src="analysis.png" alt="analysis"></div>
                        <h2 class="study-title">ANÁLISES EXPLORATÓRIAS</h2>
                    </div>
                    <div class="study-text">Análise e limpeza de dados, bem como a geração de insights por meio de técnicas estatísticas, são pontos centrais do meu conjunto de habilidades. Além disso, tenho me dedicado a transformar dados complexos em narrativas visuais claras e acessíveis por meio de visualizações eficazes, com o objetivo de facilitar a compreensão para públicos diversos, independentemente do nível técnico.</div>
                </div>
                <div class="studies-col" id="studies-col4">
                    <div class="study-heading">
                        <div class="study-icon"><img src="gears.png" alt="gears"></div>
                        <h2 class="study-title">ARQUITETURA DE PROJETOS</h2>
                    </div>
                    <div class="study-text">Tive a oportunidade de aplicar boas práticas de desenvolvimento de software, com foco em otimização de algoritmos, escalabilidade de aplicações e escrita de código limpo e eficiente. Além disso, adquiri conhecimentos em programação em nuvem em nível básico e em modelagem de banco de dados, compreendendo a importância de estruturas bem definidas para garantir desempenho e integridade dos sistemas.</div>
                </div>
            </div>
        </div>
    </div>
</div>


<!-- Programming Languages -->
<div class="languages">
    <div class="languages-title"><h1>EXPERIÊNCIA</h1></div>
    <div class="languages-text"><p>Eu tenho me desenvolvendo na área de Data Science desde 2023, e aqui estão presentes algumas ferramentes que pude ter contato durante meu desenvolvimento profissional.</p></div>
    <div class="languages-imgs">
        <div class="languages-line">
            <img src="./languages/python.png" alt="">
            <img src="./languages/cpp.png" alt="">
            <img src="./languages/r.png" alt="">
            <img src="./languages/scilab.png" alt="">
        </div>

        <div class="languages-line">
            <img src="./languages/html.png" alt="">
            <img src="./languages/css.png" alt="">
            <img src="./languages/js.png" alt="">
            <img src="./languages/postgresql.png" alt="">
        </div>

        <div class="languages-line">
            <img src="languages/git.png" alt="">
            <img src="languages/github.png" alt="">
            <img src="languages/excel.png" alt="">
            <img src="languages/linux.png" alt="">
        </div>
    </div>
</div>

<!-- Courses -->
<div class="courses">    
    <div class="courses-block">
        <div class="courses-title"><h1>Formação Acadêmica</h1></div>

        <div class="couses-container">
            <div class="courses-col1">
                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/etec.png" alt=""></div>
                    <p><b>ETEC:</b> Ensino Técnico Integrado ao Ensino Médio em Administração na ETEC Mário Antônio Verza (2020–2022).</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/fgv.png" alt=""></div>
                    <p><b>FGV:</b> Graduação em Ciência de Dados e Inteligência Artificial pela Fundação Getulio Vargas (2023–2026).</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/pic.jpg" alt=""></div>
                    <p><b>PIC OBMEP:</b> Programa de Iniciação Científica Júnior em Matemática promovido pela OBMEP (2018–2022).</p>
                </div>
            </div>

            <div class="courses-col2">
                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/picme.jpg" alt=""></div>
                    <p><b>PICME:</b> Programa de Iniciação Científica e Mestrado patrocinado pelo CNPq (2023–2025).</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/poti.png" alt=""></div>
                    <p><b>POTI:</b> Polo Olímpico de Treinamento Intensivo em Presidente Prudente – SP, com foco em olimpíadas de Matemática (2021).</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/fgv.png" alt=""></div>
                    <p><b>Curso de Verão FGV:</b> Participação nos cursos de Estruturas Algébricas e Sistemas de Recomendação, oferecidos pela FGV em janeiro de 2023 e janeiro de 2024.</p>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="complementaries">
    <div class="courses-block">
        <div class="courses-title"><h1>Informações Complementares</h1></div>

        <div class="couses-container">
            <div class="courses-col1">
                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/obmep.png" alt=""></div>
                    <p><b>OBMEP:</b> Penta medalhista na Olimpíada Brasileira de Matemática das Escolas Públicas.</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/stolimpiadas.png" alt=""></div>
                    <p><b>Stolimpíadas:</b> Medalhista de prata na olimpíada de Matemática organizada pela AOBM e pela Stone.</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/cdmc.png" alt=""></div>
                    <p><b>FGV CDMC:</b> Bolsista do FGV CDMC, iniciativa voltada à formação de excelência para alunos premiados em olimpíadas científicas. O programa oferece bolsa integral de graduação e auxílio financeiro para despesas pessoais.</p>
                </div>
            </div>

            <div class="courses-col2">
                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/obmep.png" alt=""></div>
                    <p><b>EHH SP:</b> Participação no Encontro do Hotel de Hilbert, evento nacional para os melhores alunos da OBMEP (2019).</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/obmep.png" alt=""></div>
                    <p><b>EHH RN:</b> Participação no Encontro do Hotel de Hilbert, evento nacional para os destaques da OBMEP (2023).</p>
                </div>

                <div class="courses-item">
                    <div class="couses-img"><img src="./courses/amplia.jpg" alt=""></div>
                    <p><b>Amplia FGV:</b> Membro da equipe de Recursos Humanos do projeto Amplia FGV — cursinho pré-vestibular voltado a alunos de baixa renda (2024–2025).</p>
                </div>
            </div>
        </div>
    </div>
</div>


<!-- Projects -->

<div class="projects">
    <!-- <div class="portfolio-logo">
        <i class="fas fa-folder-open"></i>
        Portfólio
    </div> -->
    
    <div class="projects-container">
        <div class="header">
            <h1>PROJETOS DESTACADOS</h1>
            <p>Uma seleção dos meus trabalhos acadêmicos e projetos pessoais desenvolvidos nos últimos tempos.</p>
        </div>

        <div class="projects-grid">
            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-graduation-cap"></i>
                        TCC - Ensino Médio na ETEC
                    </div>
                    <div class="project-institution">Curso Técnico em Administração</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Projeto de conclusão do curso técnico em Administração. O trabalho explorou o papel das teorias administrativas na construção de empresas social e ambientalmente responsáveis.
                    </div>
                    <div class="project-links">
                        <a href="https://www.youtube.com/watch?v=iuaiE0GV9jU" class="project-link" target="_blank">
                            <i class="fas fa-video"></i> Pitch de Apresentação
                        </a>
                        <a href="https://drive.google.com/file/d/1bEPpbGGjmAVH6gLU0nu0sjF-O7_4WOy-/view?usp=sharing" class="project-link" target="_blank">
                            <i class="fas fa-file-alt"></i> TCC
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Pessoal</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-palette"></i>
                        Marvel vs DC – Peça Gráfica
                    </div>
                    <div class="project-institution">Design de Dados com R e Canva</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Peça gráfica usando R e Canva para representar uma batalha fictícia entre personagens das editoras.
                    </div>
                    <div class="project-links">
                        <a href="https://drive.google.com/file/d/1V7ACPGSPLtsNpdY4KaGMgTXPQQfp5XHX/view?usp=sharing" class="project-link" target="_blank">
                            <i class="fas fa-paint-brush"></i> Peça gráfica
                        </a>
                        <a href="https://github.com/KaikyBraga/DC-Comics-vs-Marvel" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-book-open"></i>
                        Storytelling com Processos Gaussianos
                    </div>
                    <div class="project-institution">Visualização Interativa</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Visualização interativa em JavaScript com D3.js para introduzir Processos Gaussianos, combinando machine learning e storytelling de forma acessível.
                    </div>
                    <div class="project-links">
                        <a href="https://fgv-vis-2025.github.io/tarefa-4-gaussian-processes/" class="project-link" target="_blank">
                            <i class="fas fa-globe"></i> Site
                        </a>
                        <a href="https://github.com/LarissaLAfonso/gaussian-processes" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="projects">

    <div class="projects-container">

        <div class="projects-grid">
            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-clock"></i>
                        Linha do Tempo Filosófica
                    </div>
                    <div class="project-institution">Visualização com D3.js e Svelte</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Timeline interativa representando correntes filosóficas, usando D3.js e padrão de projeto Svelte.
                    </div>
                    <div class="project-links">
                        <a href="https://larissalafonso.github.io/history-of-philosophy/" class="project-link" target="_blank">
                            <i class="fas fa-globe"></i> Site
                        </a>
                        <a href="https://github.com/LarissaLAfonso/history-of-philosophy" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-chart-bar"></i>
                        Modelagem com GLMs – Análise Estatística
                    </div>
                    <div class="project-institution">Trabalho com dados de contagem em R</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Modelos de Poisson e Binomial Negativa aplicados a dados da base "Recreation Demand" explorando o problema de excesso de zeros.
                    </div>
                    <div class="project-links">
                        <a href="https://drive.google.com/file/d/1zp-K8iDPlz9EV-vQSTK9EcKOmyyZMeD1/view?usp=sharing" class="project-link" target="_blank">
                            <i class="fas fa-file-alt"></i> Relatório
                        </a>
                        <a href="https://github.com/KaikyBraga/count_glm" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-image"></i>
                        Projeto de Álgebra Linear com Imagens
                    </div>
                    <div class="project-institution">Matemática e Visão Computacional</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Transformações matemáticas aplicadas a filtros em imagens com base em conceitos de Álgebra Linear e Visão Computacional. 
                    </div>
                    <div class="project-links">
                        <a href="https://visualmatrix-oficial.streamlit.app/" class="project-link" target="_blank">
                            <i class="fas fa-globe"></i> Site
                        </a>
                        <a href="https://github.com/samullima/Trabalho_AL" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="projects">
    <div class="projects-container">

        <div class="projects-grid">
            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-chart-area"></i>
                        Visualização Sociopolítica com Bokeh
                    </div>
                    <div class="project-institution">Visual Analytics com Python</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Visualizações interativas com Bokeh e Python para dados sociopolíticos.
                    </div>
                    <div class="project-links">
                        <a href="https://trabalho-icd.netlify.app/" class="project-link" target="_blank">
                            <i class="fas fa-globe"></i> Site
                        </a>
                        <a href="https://github.com/LuuSamp/Trabalho_ICD" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-gamepad"></i>
                        Desenvolvimento de Jogo com Pygame
                    </div>
                    <div class="project-institution">Programação Orientada a Objetos</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Jogo desenvolvido com Pygame em Python, focando no estudo em Programação Orientada a Objetos.
                    </div>
                    <div class="project-links">
                        <a href="https://github.com/KaikyBraga/Trabalho_A2_LP" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-map-signs"></i>
                        Projeto GPS – Algoritmos em Grafos (PAA)
                    </div>
                    <div class="project-institution">Estruturas e Otimização em C++</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Sistema de rotas com algoritmos de grafos em C++, com foco em otimização e complexidade computacional. 
                    </div>
                    <div class="project-links">
                        <a href="https://drive.google.com/file/d/1ieMD0PZBRGTFdCpLfPoo_7f_M8AVRK-2/view?usp=sharing" class="project-link" target="_blank">
                            <i class="fas fa-file-alt"></i> Documentação
                        </a>
                        <a href="#" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

        </div>
    </div>
</div>

<div class="projects">    
    <div class="projects-container">

        <div class="projects-grid">
            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-code-branch"></i>
                        Projeto de Threads – Pipeline Paralelo de Dados
                    </div>
                    <div class="project-institution">C++ e Python Multithreading</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Simulação de um Banco com pipeline de dados paralela em C++ e Python para tratamento e processamento de dados.
                    </div>
                    <div class="project-links">
                        <a href="https://drive.google.com/file/d/1pefYwblinbR3NMHr0Tnb6OTeAM-dm8hI/view?usp=sharing" class="project-link" target="_blank">
                            <i class="fas fa-file-alt"></i> Documentação
                        </a>
                        <a href="https://github.com/AlessandraBello/Comp\_escalavel\_a1" class="project-link" target="_blank">
                            <i class="fab fa-github"></i> Repositório
                        </a>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <span class="category-label">Acadêmico</span>
                <div class="card-header">
                    <div class="project-title">
                        <i class="fas fa-chart-line"></i>
                        Field Project – FGV EMAp
                    </div>
                    <div class="project-institution">Projeto Aplicado de Ciência de Dados</div>
                </div>
                <div class="project-content">
                    <div class="project-desc">
                        Projeto aplicado em parceria com a empresa Rocket.Chat. O objetivo foi identificar padrões de comportamento entre usuários de um tipo específico de plano da plataforma.
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
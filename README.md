# pronep
pronep-inacabado
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=INACABADO&color=red&style=for-the-badge)

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pronep</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-4Q6Gf2aSP4eDXB8Miphtr37CMZZQ5oXLH2yaXMJ2w8e2ZtHTl7GptT4jmndRuHDT" crossorigin="anonymous">
<link rel="stylesheet" href="style.css">

</head>

<body>
    <header class="row">
        <nav class="navbar navbar-expand-lg bg-body-tertiary" data-bs-theme="dark">
            <div class="container">
                <a class="navbar-brand" href="#">
                    <img src="imagens/logotipo-pronep-horizontal.png" class="col-3">
                </a>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">inicio</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">o programa</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">cursos</a>
                        </li>

                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">fale conosco</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- INICIO SEÇAO VIDEO-->
  <section class="row section main-banner" id="top" data-section="section1">
      <video autoplay muted loop id="bg-video">
          <source src="imagens/course-video.mp4" type="video/mp4"/>
      </video>

      <div class="video-overlay header-text" id="logo-video">
          <div class="caption">
              <img src="imagens/logotipo-pronep.png" class="col-12 col-md-4 hidden-sm">
              <!-- <h6>Graduate School of Management</h6> -->
              <h2><em class="text-success">Preparando jovens</em> para os desafios do <em>mercado de trabalho</em></h2>
          </div>
      </div>
  </section>

   <section class="features">
    <div class="container">
      <div class="row">
        <div class="col-lg-4 col-12">
          <div class="features-post">
            <div class="features-content">
              <div class="content-show">
                <h4><i class="fa fa-user"></i>PÚBLICO ALVO</h4>
              </div>
              <div class="content-hide">
                <p>Alunos de escolas públicas com idades entre 16 e 23 anos, selecionados com base em seu desempenho acadêmico e potencial para a área de tecnologia.</p>
                <p class="hidden-sm">Alunos de escolas públicas com idades entre 16 e 23 anos, selecionados com base em seu desempenho acadêmico e potencial para a área de tecnologia.</p>
                <div>
                  <a href="https://api.whatsapp.com/send?phone=558531041414&text=Vi%20o%20seu%20site%20e%20gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20programa%20PRONEP%20e%20como%20posso%20fazer%20pra%20me%20inscrever?" target="_blank">Mais Informações</a>
                </div>
            </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-12">
          <div class="features-post second-features">
            <div class="features-content">
              <div class="content-show">
                <h4><i class="fa fa-book"></i>MATERIAL ATUALIZADO</h4>
              </div>
              <div class="content-hide">
                <p>Material desenvolvido por especialistas das áreas que mais empregam no mercado.</p>
                <p class="hidden-sm">Material desenvolvido por especialistas das áreas que mais empregam no mercado.</p>
                <!-- <div class="scroll-to-section"><a href="#section3">Mais Informações</a></div> -->
                <div>
                  <a href="https://api.whatsapp.com/send?phone=558531041414&text=Vi%20o%20seu%20site%20e%20gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20programa%20PRONEP%20e%20como%20posso%20fazer%20pra%20me%20inscrever?" target="_blank">Mais Informações</a>
                </div>
            </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4 col-12">
          <div class="features-post third-features">
            <div class="features-content">
              <div class="content-show">
                <h4><i class="fa fa-graduation-cap"></i>CERTIFICADO</h4>
              </div>
              <div class="content-hide">
                <p>Certificação reconhecida no mercado para os alunos que concluírem o curso com êxito.</p>
                <p class="hidden-sm">Certificado reconhecido nacionalmente.</p>
                <!-- <div class="scroll-to-section"><a href="#section4">Read More</a></div> -->
                <div>
                  <a href="https://api.whatsapp.com/send?phone=558531041414&text=Vi%20o%20seu%20site%20e%20gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20programa%20PRONEP%20e%20como%20posso%20fazer%20pra%20me%20inscrever?" target="_blank">Mais Informações</a>
                </div>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section why-us" data-section="section2">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-heading">
            <h2>O PROGRAMA</h2>
            <p class="text-light medium">O projeto PRONEP visa não apenas fornecer conhecimento técnico, mas também preparar os jovens para os desafios do mercado de trabalho, promovendo o desenvolvimento de habilidades comportamentais e empreendedoras essenciais para o sucesso na área de tecnologia.</p>
          </div>
        </div>
        <div class="col-md-12">
          <div id='tabs'>
            <ul>
              <li><a href='#tabs-1'>Metodologia</a></li>
              <li><a href='#tabs-2'>Estrutura</a></li>
              <li><a href='#tabs-3'>Impacto Social</a></li>
            </ul>
            <section class='tabs-content'>
              <article id='tabs-1'>
                <div class="row">
                  <div class="col-md-6">
                    <img src="assets/images/laboratorio-02-aniversario-04-anos-da-escola.jpeg" alt="">
                  </div>
                  <div class="col-md-6 mt-5 mt-md-0">
                    <p><strong>Aulas Teóricas:</strong> Abordagem detalhada de conceitos fundamentais e avançados em tecnologia.</p>
                    <p><strong>Aulas Práticas:</strong> Laboratórios equipados com tecnologias de ponta para simulação de cenários reais.</p>
                    <p><strong>Projetos Práticos:</strong> Desenvolvimento de projetos em parceria com empresas do setor para aplicação dos conhecimentos adquiridos.</p>
                    <p><strong>Workshops e Palestras:</strong> Interação com profissionais experientes da indústria tecnológica.</p>
                    <p><strong>Desenvolvimento de Projetos Práticos:</strong> Orientação, incentivo e capacitação para os próprios jovens desenvolvam projetos, que sejam expostos e apresentado para parceiros, para serem acelerados e tragam possibilidade de crescimento pessoal e profissional. </p>
                  </div>
                </div>
              </article>
              <article id='tabs-2'>
                <div class="row">
                  <div class="col-md-6">
                    <img src="assets/images/laboratorio-02-artpix-e-midias-digitais.jpeg" alt="">
                  </div>
                  <div class="col-md-6 mt-5 mt-md-0">
                    <p><strong>Salas de aula modernas</strong> e bem equipadas com laboratórios de informática com computadores de última geração e acesso aos maiores e melhores softwares utilizados no mercado.</p>
                    <p><strong>Material didático atualizado</strong>, incluindo livros, artigos e cursos online.</p>
                    <p>Acesso a oportunidades reais de iniciarem suas carreiras profissionais, sendo encaminhado pelo nosso processo Exclusivo do <strong>programa de Empregabilidade</strong>.</p>
                    <p><strong>Parcerias Estratégicas:</strong> Empresas de tecnologia para oportunidades de estágio e emprego, Instituições educacionais para certificação dos cursos e Organizações de apoio ao jovem e empreendedorismo para suporte adicional.</p>
                  </div>
                </div>
              </article>
              <article id='tabs-3'>
                <div class="row">
                  <div class="col-md-6">
                    <img src="assets/images/laboratorio-03-robotic-arduino.JPG" alt="">
                  </div>
                  <div class="col-md-6 mt-5 mt-md-0">
                    <p>Formação de profissionais qualificados para atender à demanda crescente do mercado de tecnologia e melhoria das perspectivas de emprego para jovens de escolas públicas.</p>
                    <p>Contribuindo para o desenvolvimento socioeconômico por meio da capacitação de jovens e consequentemente a redução da taxa de desemprego juvenil através da promoção da inclusão digital e social, e estímulo ao empreendedorismo tecnológico entre jovens.</p>
                    <p>Além de dispor de bolsas de estudos integrais para alunos selecionados.</p>
                  </div>
                </div>
              </article>
            </section>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section coming-soon" data-section="section3">
    <div class="container">
      <div class="row">
        <div class="col-md-7 col-xs-12">
          <div class="continer centerIt">
            <div>
              <h4>Mais de<em> mil alunos formados</em> e ingressados no <em>mercado de trabalho</em>.
                <br /><br /> 
                Garanta <em> agora </em> a sua <em>bolsa de estudos</em>!</h4>
              <div class="counter">

                <div class="days">
                  <div class="value">00</div>
                  <span>Dias</span>
                </div>

                <div class="hours">
                  <div class="value">00</div>
                  <span>Horas</span>
                </div>

                <div class="minutes">
                  <div class="value">00</div>
                  <span>Minutos</span>
                </div>

                <div class="seconds">
                  <div class="value">00</div>
                  <span class="fontcont">Segundos</span>
                </div>

              </div>
            </div>
          </div>
        </div>
        <div class="col-md-5">
          <div class="right-content">
            <div class="top-content">
              <h6>Envie abaixo os seus dados que um de nossos <em>gestores de carreira</em> entrará em contato:</h6>
            </div>
            <form id="contact" action="enviaform-tornarsealuno.php" method="get">
              <div class="row">
                <div class="col-md-12">
                  <fieldset>
                    <input name="nome" type="text" class="form-control" id="name" placeholder="Digite o seu Nome" required="">
                  </fieldset>
                </div>
                <div class="col-md-12">
                  <fieldset>
                    <input name="email" type="text" class="form-control" id="email" placeholder="Digite o seu E-Mail" required="">
                  </fieldset>
                </div>
                <div class="col-md-12">
                  <fieldset>
                    <input name="whatsapp" type="text" class="form-control" id="Seu Whatsapp" placeholder="Digite o seu whatsapp" required="">
                  </fieldset>
                </div>
                <div class="col-md-12">
                  <fieldset>
                    <button type="submit" id="form-submit" class="button">Enviar</button>
                  </fieldset>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section courses" data-section="section4">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-12">
          <div class="section-heading">
            <h2>Conheça alguns de nossos cursos</h2>
          </div>
        </div>
        <div class="owl-carousel owl-theme">
          <div class="item">
            <img src="assets/images/courses-01.jpg" alt="Course #1">
            <div class="down-content">
              <h4>Administrativo Digital Interativo</h4>
              <p>Formação na área Administrativa com foco em rotinas e tecnologias de controle e organização.</p>
              <div class="author-image">
                <!-- <img src="assets/images/author-01.png" alt="Author 1"> -->
              </div>
              <div class="text-button-free">
                <br />
                <a href="assets/pdf/administrativo-digital-interativo-pronep.pdf" target="_blank">Mais Informações <i class="fa fa-angle-double-right"></i></a>
              </div>
            </div>
          </div>
          <div class="item">
            <img src="assets/images/courses-02.jpg" alt="Course #2">
            <div class="down-content">
              <h4>Design Híbrido Interativo</h4>
              <p>Formação em Design Gráfico e Digital com as melhores e mais usadas ferramentas do mercado.</p>
              <div class="author-image">
                <!-- <img src="assets/images/author-02.png" alt="Author 2"> -->
              </div>
              <div class="text-button-free">
                <br />
                <a href="assets/pdf/design-hibrido-pronep.pdf" target="_blank">Mais Informações <i class="fa fa-angle-double-right"></i></a>
              </div>
            </div>
          </div>
          <div class="item">
            <img src="assets/images/courses-03.jpg" alt="Course #3">
            <div class="down-content">
              <h4>Games Teen Interativo</h4>
              <p>Formação em Criação de Jogos com plataformas 3D e Online para a nova geração de jovens gamers.</p>
              <div class="author-image">
                <!-- <img src="assets/images/author-03.png" alt="Author 3"> -->
              </div>
              <div class="text-button-free">
                <br />
                <a href="assets/pdf/games-teen-interativo-pronep.pdf" target="_blank">Mais Informações <i class="fa fa-angle-double-right"></i></a>
              </div>
            </div>
          </div>
          <div class="item">
            <img src="assets/images/courses-04.jpg" alt="Course #4">
            <div class="down-content">
              <h4>Start Dev Frontend</h4>
              <p>Formação na área de Desenvolvimento com foco na criação de sites usando a linguagem javascript.</p>
              <div class="author-image">
                <!-- <img src="assets/images/author-04.png" alt="Author 4"> -->
              </div>
              <div class="text-button-free">
                <br />
                <a href="https://wa.me/558531041414?text=Ol%C3%A1,%20tudo%20bem?%20Gostaria%20de%20mais%20informa%C3%A7%C3%B5es%20sobre%20o%20curso%20START%20DEV%20-%20FRONTEND." target="_blank">Mais Informações <i class="fa fa-angle-double-right"></i></a>
              </div>
            </div>
          </div>
          <div class="item">
            <img src="assets/images/courses-05.jpg" alt="">
            <div class="down-content">
              <h4>Tecnologia da Informação Int.</h4>
              <p>Formação na área de Tecnologia da Informação com foco em Manutenção e Ambientes Digitais.</p>
              <div class="author-image">
                <!-- <img src="assets/images/author-05.png" alt=""> -->
              </div>
              <div class="text-button-free">
                <br />
                <a href="assets/pdf/tecnologia-da-informacao-interativo-pronep.pdf" target="_blank">Mais Informações <i class="fa fa-angle-double-right"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  

  <section class="section video" data-section="section5">
    <div class="container">
      <div class="row">
        <div class="col-md-6 align-self-center">
          <div class="left-content">
            <span>Parceria Pixels Educação (Sorteio)</span>
            <h4>O Mundo a <em>mil por hora</em>!</h4>
            <p>O programa PRONEP em parceria com a escola Pixels Educação Tecnológica, promoveram uma campanha ao qual foi sorteado um datashow entre as escolas participantes um drone para um aluno da escola participante.</p>
            <p>O ganhador do sorteio Mundo a Mil Por Hora foi o Aluno Kevim Richard, do Centro de Educação Infantil Maria Helenilce Cavalcante Leite Martins!</p>
            <p>Mas não para por aqui, iremos ter mais sorteios e quem sabe você e sua escola podem ser os próximos sorteados!</p>
            <div class="main-button"><a rel="nofollow" href="https://api.whatsapp.com/send?phone=558531041414&text=Ol%C3%A1,%20tudo%20bem?%20Vi%20o%20seu%20site%20e%20gostaria%20de%20saber%20como%20inscrevo%20%20minha%20escola%20no%20programa%20PRONEP." target="_blank">Inscreva a sua escola</a></div>
          </div>
        </div>
        <div class="col-md-6">
          <article class="video-item">
            <div class="video-caption">
              <h4>Confira a entrega do prêmio</h4>
            </div>
            <figure>
              <a href="https://www.youtube.com/watch?v=wmcG2uw-PD8" class="play"><img src="assets/images/main-thumb.jpg"></a>
            </figure>
          </article>
        </div>
      </div>
    </div>
  </section>

  <section class="section courses" data-section="section4">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-12">
          <div class="section-heading">
            <h2>Confira alguns de nossos Parceiros</h2>
          </div>
        </div>
        <div class="owl-carousel owl-theme col-md-8 offset-md-2">
          <a href="https://www.pixelsescola.com" target="_blank" title="Pixels Educação Tecnológica">
            <div class="item">
              <img src="assets/images/pixels-educacao-tecnologica.png" alt="Course #1">
            </div>
          </a>
          <div class="item">
            <img src="assets/images/adep.png" alt="Course #1">
          </div>
          <div class="item">
            <img src="assets/images/academia-pixels.png" alt="Course #1">
          </div>
          <div class="item">
            <img src="assets/images/meta-pixels.png" alt="Course #1">
          </div>
          <a href="https://www.iwtraining.com.br" target="_blank" title="Cursos de Programação em Fortaleza - Aprenda a criar sites, apps e sistemas, desde a concepção do design a programação - Escola iwtraining educação avançada">
            <div class="item">
              <img src="assets/images/iwtraining-educacao-avancada.png" alt="Course #1">
            </div>
          </a>
        </div>
      </div>
    </div>
  </section>

  <section class="section contact" data-section="section6">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="section-heading">
            <h2>Fale Conosco</h2>
          </div>
        </div>
        <div class="col-md-6">
        
        <!-- Do you need a working HTML contact-form script?
                	
                    Please visit https://templatemo.com/contact page -->
                    
          <form id="contact" action="enviaform-faleconosco.php" method="get">
            <div class="row">
              <div class="col-md-6">
                  <fieldset>
                    <input name="nome" type="text" class="form-control" id="name" placeholder="Digite o seu Nome" required="">
                  </fieldset>
                </div>
                <div class="col-md-6">
                  <fieldset>
                    <input name="whatsapp" type="text" class="form-control" id="email" placeholder="Digite o seu Whatsapp" required="">
                  </fieldset>
                </div>
              <div class="col-md-12">
                <fieldset>
                  <textarea name="mensagem" rows="6" class="form-control" id="message" placeholder="Digite a sua mensagem" required=""></textarea>
                </fieldset>
              </div>
              <div class="col-md-12">
                <fieldset>
                  <button type="submit" id="form-submit" class="button">Enviar mensagem</button>
                </fieldset>
              </div>
            </div>
          </form>
        </div>
        <div class="col-md-6">
          <div id="map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3981.271886989727!2d-38.52938422422677!3d-3.7508619432884784!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x7c748dff89fcb7f%3A0x48cd5cb80b80a58e!2sPixels%20%7C%20Escola%20de%20Design%20e%20Tecnologia!5e0!3m2!1spt-BR!2sbr!4v1722954294375!5m2!1spt-BR!2sbr" width="100%" height="422px" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <p>PRONEP <i class="fa fa-copyright"></i> 2024
            <br />
           Customizado por: <a href="https://www.wagnerlima.net" target="_blank" title="Professor de Design e Desenvolvimento Web">wagnerlima.NET</a>
          
          </p>
        </div>
      </div>
    </div>
  </footer>

  <!-- Scripts -->
  <!-- Bootstrap core JavaScript -->
    <script src="vendor/jquery/jquery.min.js"></script>
    <script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

    <script src="assets/js/isotope.min.js"></script>
    <script src="assets/js/owl-carousel.js"></script>
    <script src="assets/js/lightbox.js"></script>
    <script src="assets/js/tabs.js"></script>
    <script src="assets/js/video.js"></script>
    <script src="assets/js/slick-slider.js"></script>
    <script src="assets/js/custom.js"></script>
    <script>
        //according to loftblog tut
        $('.nav li:first').addClass('active');

        var showSection = function showSection(section, isAnimate) {
          var
          direction = section.replace(/#/, ''),
          reqSection = $('.section').filter('[data-section="' + direction + '"]'),
          reqSectionPos = reqSection.offset().top - 0;

          if (isAnimate) {
            $('body, html').animate({
              scrollTop: reqSectionPos },
            800);
          } else {
            $('body, html').scrollTop(reqSectionPos);
          }

        };

        var checkSection = function checkSection() {
          $('.section').each(function () {
            var
            $this = $(this),
            topEdge = $this.offset().top - 80,
            bottomEdge = topEdge + $this.height(),
            wScroll = $(window).scrollTop();
            if (topEdge < wScroll && bottomEdge > wScroll) {
              var
              currentId = $this.data('section'),
              reqLink = $('a').filter('[href*=\\#' + currentId + ']');
              reqLink.closest('li').addClass('active').
              siblings().removeClass('active');
            }
          });
        };

        $('.main-menu, .scroll-to-section').on('click', 'a', function (e) {
          if($(e.target).hasClass('external')) {
            return;
          }
          e.preventDefault();
          $('#menu').removeClass('active');
          showSection($(this).attr('href'), true);
        });

        $(window).scroll(function () {
          checkSection();
        });
    </script>



    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-j1CDi7MgGQ12Z7Qab0qlWQ/Qqz24Gc6BM0thvEMVjHnfYGF0rmFCozFSxQBxwHKO"
        crossorigin="anonymous"></script>
</body>

</html>

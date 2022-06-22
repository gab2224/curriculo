<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>Gabriel Sobral</title>
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700" rel="stylesheet" />
    <script src="https://kit.fontawesome.com/42d5adcbca.js" crossorigin="anonymous"></script>
    <link href="https://demos.creative-tim.com/soft-ui-design-system/assets/css/nucleo-icons.css" rel="stylesheet" />
    <link href="https://demos.creative-tim.com/soft-ui-design-system/assets/css/nucleo-svg.css" rel="stylesheet" />
    <link rel="stylesheet" href="./assets/css/theme.css">
    <link rel="stylesheet" href="./assets/css/loopple/loopple.css">
</head>

<body class="null">
    <header class="">
        <div class="page-header min-vh-75">
            <div class="oblique position-absolute top-0 h-100 d-md-block d-none">
                <div class="oblique-image bg-cover position-absolute fixed-top ms-auto h-100 z-index-0 ms-n8" style="background-image:url(https://demos.creative-tim.com/soft-ui-design-system-pro/assets/img/curved-images/curved11.jpg)"></div>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-lg-6 col-md-7 d-flex justify-content-center flex-column">
                        <h1 class="text-gradient text-primary">Muito Prazer</h1>
                        <h1 class="mb-4">Eu Sou Gabriel Sobral</h1>
                        <p class="lead pe-5 me-5">Seu Novo Contratado</p>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <section class="py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-4 col-10 mx-auto">
                    <div class="p-3 text-center">
                        <p>Atualmente procurando um novo desafio e fazendo Ensino Médio e Curso Técnico de Desenvolvimento de Sistema</p>
                    </div>
                </div>
                <div class="col-md-4 col-10 mx-auto">
                    <div class="p-3 text-center">
                        <p>Bom em Programação e design Digital, Aceito tudo o que vem pela frente</p>
                    </div>
                </div>
                <div class="col-md-4 col-10 mx-auto">
                    <div class="p-3 text-center">
                        <p>E Ai vamos conversar? <br> (14) 98800-1754 </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="https://loopple.s3.eu-west-3.amazonaws.com/soft-ui-design-system/js/core/bootstrap.min.js" type="text/javascript"></script>
    <script src="https://demos.creative-tim.com/soft-ui-design-system/assets/js/soft-design-system.min.js?v=1.0.5" type="text/javascript"></script>
    <script src="https://demos.creative-tim.com/soft-ui-design-system-pro/assets/js/plugins/countup.min.js" type="text/javascript"></script>
    <script src="https://demos.creative-tim.com/soft-ui-design-system-pro/assets/js/plugins/flatpickr.min.js"></script>
    <script>
        if (document.getElementById("state1")) {
                    const countUp = new CountUp("state1", document.getElementById("state1").getAttribute("countTo"));
                    if (!countUp.error) {
                      countUp.start();
                    } else {
                      console.error(countUp.error);
                    }
                  }
                  if (document.getElementById("state2")) {
                    const countUp1 = new CountUp("state2", document.getElementById("state2").getAttribute("countTo"));
                    if (!countUp1.error) {
                      countUp1.start();
                    } else {
                      console.error(countUp1.error);
                    }
                  }
                  if (document.getElementById("state3")) {
                    const countUp2 = new CountUp("state3", document.getElementById("state3").getAttribute("countTo"));
                    if (!countUp2.error) {
                      countUp2.start();
                    } else {
                      console.error(countUp2.error);
                    };
                  }
        
         if (document.querySelector('.datepicker-1')) {
              flatpickr('.datepicker-1', {
              }); // flatpickr
            } 
        
         if (document.querySelector('.datepicker-2')) {
              flatpickr('.datepicker-2', {
              }); // flatpickr
            }
    </script>
    <script src="./assets/js/loopple/loopple.js"></script>
</body>

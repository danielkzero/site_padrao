<template>
    <div class="container marketing">
        <h4 class="featurette-heading fw-normal lh-1 pb-3 my-5 border-bottom">Conheça nossos serviços</h4>
        <div class="row featurette">
            <div class="col-md-7">
                <h2 class="featurette-heading fw-normal lh-1">
                    Produtos injetados
                </h2>
                <p class="lead">
                    <span class="text-body-secondary">
                        Somos especializados em fabricação de componentes injetados especiais.
                        Fabricamos componentes para embalagens metálicas do tipo Rack para transporte de peças
                        automotivas,
                        desenvolvemos soluções inteligentes junto aos nossos clientes, Veja abaixo alguns de nossos
                        produtos mais
                        comum:
                    </span>
                <ul role="list" class="list-group py-2">
                    <li class="list-group-item"><box-icon name="check" color="green" class="pe-2"></box-icon> Cremalheiras de PVC e PP
                        injetadas em alma metálica </li>
                    <li class="list-group-item"><box-icon name="check" color="green" class="pe-2"></box-icon> Separadores de peças
                        Híbridos
                        injetados (PVC/Corpo de aço, PVC/PP, e outros) </li>
                    <li class="list-group-item"><box-icon name="check" color="green" class="pe-2"></box-icon> Brushbar </li>
                    <li class="list-group-item"><box-icon name="check" color="green" class="pe-2"></box-icon> Barras e cantoneiras
                        amortecedoras </li>
                    <li class="list-group-item"><box-icon name="check" color="green" class="pe-2"></box-icon> Réguas de PP Injetado
                    </li>
                </ul>
                </p>
            </div>
            <div class="col-md-5">
                <div :style="{ 'background-image' :  'url(' + require('../assets/imagens/home03.jpg') + ')' }"
                style="
                    background-size: auto 500px;
                    background-repeat: no-repeat;
                    background-position: center center;
                    width: 500px; height: 500px; display: block;
                    ">
                </div>
            </div>
        </div>

        <hr class="featurette-divider" />

        <div class="row featurette">
            <div class="col-md-7 order-md-2">
                <h2 class="featurette-heading fw-normal lh-1">
                    Usinagem de precisão
                </h2>
                <p class="lead">
                    <span class="text-body-secondary">
                        Possuímos máquinas CNC, centro de usinagem e fresadora para fabricação de
                        componentes metálicos e terceirização de serviços. Contamos com mão de obra
                        especializada, desenvolvemos ferramentas próprias.
                    </span>
                </p>
            </div>
            <div class="col-md-5 order-md-1">
                <div 
                :style="{ 'background-image' :  'url(' + require('../assets/imagens/serviços-de-usinagem.png') + ')' }"
                style="
                    background-size: auto 500px;
                    background-repeat: no-repeat;
                    background-position: center center;
                    width: 500px; height: 500px; display: block;
                    ">
                </div>
            </div>
        </div>

        <hr class="featurette-divider" />

        <div class="row featurette">
            <div class="col-md-7">
                <h2 class="featurette-heading fw-normal lh-1">
                    Padronizados
                </h2>
                <p class="lead">
                    <span class="text-body-secondary">
                        Separadores de borracha feitos em PVC rígido, ideal para aplicação em embalagens de movimentação
                        automotiva (racks metálicos). <br />
                        Seu formato anatômico se adapta a qualquer superfície, e quando se fala em acomodação de peças
                        automotivas, ele é a solução ideal.
                    </span>
                </p>
            </div>
            <div class="col-md-5">
                <div 
                :style="{ 'background-image' :  'url(' + require('../assets/imagens/separador-brush-bar.png') + ')' }"
                style="
                    background-size: 500px auto;
                    background-repeat: no-repeat;
                    background-position: center center;
                    width: 500px; height: 500px; display: block;
                    ">
                </div>
            </div>
        </div>
    </div>
</template>
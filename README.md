Street Pet
==========

![Mascote](./streetpet.jpg)

## Objetivo e Apresentação

Um Sistema OpenHardware e OpenSource de Alimentação e tratamento de Cães e Gatos Abandonados, o **objetivo** é colecionar ideias e assim  **desenvolver um sistema que alimente e borrife remêdios** em cães e gatos catalogados e chipados que estejam em situação de abandono. O sistema também visa catalogar os Pets em situação de abandono, cadastrar ONGs e Cuidadores, e analisar o histórico de tais animais oferecendo dados para que sejam processados e analisados por especialistas no ramo de veterinária e zoonoses.

A ideia é que o projeto seja replicado e aplicado pelos participantes em sua região, usando as arquiteturas de software e hadware que melhor lhe atender, portanto foi criado uma [Organziação chamada StreetPET no GitHUB](http://bit.ly/streetpet_org) para agregar todos as propostas conforme arquietura, desde que a API de comunicação seja padrão, permitindo total interoperabilidade.

O Projeto pertence a todos nós, se você acredita que o projeto pode melhorar você é a pessoa que procuramos, assim você pode com seus conhecimentos nos ajudar a melhora-lo. [Visite este link e deixe sua colaboração](http://bit.ly/streetpet_sugestoes), você pode editar qualquer arquivo deste projeto e ampliar a documentação.

## Colaborando e Contribuindo

Antes de tudo é interessante que tome conhecimento de nosso [código de conduta](./codigodeconduta)

[Para colaborar com o projeto veja as instruções clicando aqui](./CONTRIBUTING)

## Mascote do Projeto

Veja a história da [Cachorrinha clicando aqui](http://carlosdelfino.eti.br/projetos/StreetPet/).

## Perguntas Frequentes sobre o Projeto

[Separei neste link algumas perguntas do projeto](./FAQ.md).

## Números do Projeto

[Anotações, estatísticas e conclusões](./numeros.md).

## Monetização do Projeto e com o Projeto

[Regras de monetização do nosso projeto](./monetizacao.md)

## Arquitetura do Sistema

* [API](./API.md)
* [Módulos](./modulos.md)

[![Borrifador Sugerido](motor-bomba-diafragma-30w-12v-25-ah-pulverizador-eletrico.jpg)](https://produto.mercadolivre.com.br/MLB-868267937-motor-bomba-diafragma-12v-22ah-80-psi-pulverizador-eletrico-_JM?quantity=1#reco_item_pos=2&reco_backend=machinalis-seller-items&reco_backend_type=low_level&reco_client=vip-seller_items-above&reco_id=5875c740-a0b0-4bf1-a229-980914c14690)

## Algumas Imagens e Videos do Projeto

Ainda é uma fase inicial e de planejamento não temos equipamentos ou softwares, porém já temos uma referencia de como será o comedouro e o bebedouro usado, já construído como exemplo por "Carlos Delfino", desta base será construído os controladores, o monitoramento e identificação e o borrifador, além do controle de dosagem de alimentação.
 

------------------------------------

![Onde estão as cercas?]({{site.url}}/images/onde_estao_as_cercas.jpg)

{% if site.google.analytics.id %} 
<!-- google analytics -->
<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
 (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
 m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
 })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
ga('create', '{{ site.google.analytics.id }}', '{%if site.google.analytics.domain %}{{ site.google.analytics.domain }}{% else %}auto{% endif %}');
ga('require', 'displayfeatures');
ga('send', 'pageview');
</script>
<!-- fim google analytics -->
{% else %}
<!-- sem google analytics -->
{% endif %}
 

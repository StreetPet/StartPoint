FAQ
===

Abaixo apresento um resumo das perguntas que estão sendo feitas sobre o projeto. Você pode ver mais perguntas e me enviar suas diretamente ou preferivelmente [na seção de sugestões e dúvidas!](http://streetpet_sugestoes).

## O que é o projeto?

Visite o link: http://bit.ly/streetpet_web1, http://bit.ly/streetpet_faq e http://bit.ly/streetpet_sugestoes, e irá encontrar mais perguntas e respostas.

Em resumo o projeto inicialmente é conceitual, visa dar a oportunidade ao pessoal se envolver numa causa e aplicar seus conhecimentos técnicos em Embarcados e IoT, desenvolvendo um sistema de alimentação (comedouro e bebedouro automatizado) e sanitização (aplicação de remédios por pulverização), Cadastro de cães de rua, histórico dos mesmos, cadastro de cuidadores, veterinários e ONGs envolvidas com cuidados de cães de rua.

## Vai ter grupo no Whatsapp ou Facebook?

Bem, eu não pretendia criar grupos, mas percebi que o pessoal está bastante acostumado a usar o Whatsapp e muitos, muitos mesmo não sabem usar o GitHub ou outro SocialCoding.

Então vai ai o link do grupo no Whatsapp: [http://bit.ly/streetpet_zap](http://bit.ly/streetpet_zap)

## Como será montado as equipes no Projeto?

O Sistema StreetPet será dividido em Equipes, que poderão assumir um ou mais projetos, e qualquer um poderá participar delas ao nível de leitura do conteúdo, desde que não sejam dados sensíveis como senhas, códigos de licenças e dados armazenados. 

Qualquer um poderá participar em mais de uma equipe, portanto não se preocupe por qual equipe começar, escolha uma e se integre.

As Equipes estão listadas em: https://github.com/orgs/StreetPet/teams

## Eu já tenho minha equipe de trabalho e queremos nos unir ao projeto

Basta criar um issue em http://bit.ly/streetpet_sugestoes apresentando sua equipe e o que deseja contribuir no sistema, a lista de nomes e ids no Github, que a equipe será criada individualmente na Organização e poderá assim trabalhar em seus projetos integrados ao nosso.

## Os repositórios dos projetos serão de sua propriedade?

Não, cada um pode criar seu próprio repositório em sua conta ou organização e cita que é parte de nosso projeto, basta abrir um [issue](http://bit.ly/streetpet_sugestoes) informando que iniciou um módulo que é parte de nosso projeto, eu irei clona-lo na [Organização principal](http://bit.ly/streetpetorg) e como subtree no repositório principal StreetPet.

## Porque o projeto está no seu usuário enão na organização?

O projeto foi iniciado em meu uusário, não existia a organização e eu não sabia se teria aceitação da comunidade, acabei antecipando a criação da Organização pois percebi que haviam muitas visitas e muitos clones, muito mais do que os que buscam se comunicar comigo, assim, logo que o projeto tomar forma e começar a se movimentar de forma mais autonoma, migro o repositório para sua própria organziação.

## Qual Linguagem será usada?

Não iremos restringir a linguagem, a quele que quiser criar ou recriar na linguagem que se sente a vontade basta criar um projeto no git e sitar nossa ORG como sendo a base do projeto, faremos um fork, e se você quiser seu projeto passa a ser editado apartir de nosso repositório.

O Importante é que a API de intercomunicação seja baseada em REST de forma que haja um padrão quanto ao modelo de dados e procedimetnos remotos. 

Uma solução baseada em Microserviços, desde catalogação de animais, doeçnas e outros dados de forma que possam ser cruzados e gerar informações relevantes ao funcionamento do sistema.

## Porque dividir o projeto em módulos?

O projeto é dividido em módulos exatamente para que cada um possa se deicar o que mais lhe interessa, porém, todos os módulos deverão conversar pelo menos com o  módulo principal que será nossa API, este modúlo usará Rest permitindo assim a troca fácil em qualquer linguagem de programação.

Quando modularizado e fragmentado for o sistema melhor, o importante agora é que cada um se envolva com o que lhe agradar e lhe motivar a estar no projeto. Depois cada módulo poderá e conquistando novos membros e engordar seus recursos, talvez até encampando outros módulos.

É fundamental que todos os módulso usem sempre o mesmo UUID para identficar o objeto principal que trabalha. Veja mais detalhes em [API](./API.md)

## Qual Arquitetura de Hardware será usado nos controladores?

O projeto é conceitual, e aberto a arquitetura de quem vai implementar. Portanto o hardware pode ser controlado com PIC sem problemas, desde que se atinja o objetivo proposto. A ideia é que cada um implemente em sua região conforme tecnologia e recursos que tiver.

## O Equipamento poderá ser roubado

Sim é um problema que cada implantador irá infrentar, por isso sugiro que sejam instalados inicialmente em portas de empresas, ou entidades como Universidades, perto de Cameras de Vigilância assim podem ser monitorado, no futuro o proprio equipamento pode ter seu proprio sistema de filmagem, tanto registrando o comportamento do PET como também o que ocorre na circunvizinhança reduzindo a perda no caso de roubo, (evitar a tentativa de roubo acredito que seja impossível).

## Como detectar os Pets?

A detecção deve ser feita via chip, cada PET cadastado deve receber um chip de RFID que será inserido sobre a pele, prática já adotada por vários cuidadores e entidades de proteção.

Com o desenvolver do projeto pesquisas de identificação podem ser desenvolvidas sobre o de padrão de manchas do pelo.

### Posso usar o ESP-cam?

Sim você pode desenvolver um submodulo para o módulo de detecção para usar o ESP-cam, assim você os recursos bases do módulo para se comunicar com a API central e usa o ESP-cam conforme seu domínio e demanda regional e outros colegas.

## Posso usar o projeto no meu TCC, Dissertação ou Tese?

Claro que pode, e pedimos que faça isso. Assim você pode nos  ajudar a tornar o projeto cada vez melhor.

## Como você vai sustentar o projeto?

O projeto não visa lucro diretamente, portanto para ser executado, cada envolvido terá que arcar com seus custos. Quando ouver uma demanda por terceiros, cada voluntário na região onde será implantado deverá negociar os custos envolvidos.

## Quanto você vai me pagar para trabalhar para você?

Antes de tudo o projeto não é meu e você não vai trabalhar para mim. 

Eu lancei uma semente e algumas pessoas do meu circulo social e profissional gostaram da ideia, então estou doando a comunidade a ideia para que ela seja replicada e executada, apenas estou gerenciando seu acontecimento. E claro fazendo minha parte para que tenha uma replica de tudo aqui na minha região como proponho para outros fazerem na suas regiões.

**Você irá _ganhar_ muito trabalhando neste projeto, irá ganhar _muito conhecimento_, _muita experiência_**, e poderá até ganhar basta fazer seu plano de negocios do projeto e ver as [regras de monetização do nosso projeto](./monetizacao.md).

## Eu posso cobrar pelos meus serviços?

**Sim**, você pode, mas no projeto, você deve trabalhar como voluntário, você pode até copiar o projeto se quiser, mas éticamente deve devolver ao projeto algum recurso em algum formato, seja conhecimento ajudando a resolver algum BUG, seja com projeto de alguma solução eletrica/eletrônica, ou até mesmo doando equipamentos e recursos financeiros.

Eu mesmo cobro de empresas e individuos para instalar pelo os comedouros, e consulorias em projetos, já das ONGs e Cuidadores faço alguns seviços como voluntário e outros negocio os custos.

[Regras de monetização do nosso projeto](./monetizacao.md)

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

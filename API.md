API - Application Programming Interface
=======================================

Antes começar é preciso exclarecer que este projeto sendo um projeto Opensource e que abrange também um contexto educacional, ele terá algumas seções que podem vir a ser repetivas, se não demasiado cansativas para alguns profissionais mais experiêntes, já que irá tratar alguns conceitos de forma detalhada quase minussiosa, como se estivesse ensinando a cada um oque fazer. Precisamos disso para dar espaço aos iniciantes e motiva-los, já que muitos estão convencidos pelos seus cursos que estão preperados, mas infelizmetne se estão lendo tais seções, é sinal que não está. Ou apenas estão fazendo um revisão.

[Qualquer erro que for encontrado deve ser apresentado na seção issues, use este link](http://bit.ly/streetpet_sugestoes).

Já diversos sistemas começar seu desenvolvendo por diversos lugares, pela interface, pela autenticação do usário (quanto tem) e princpalmente pelo banco de dados, existem muitás técnicas de desenvolvimento, algumas dão inicio pelas testes, outras pela arquitetura do domínio da informação envolvida.

No nosso projeto iremos iniciar o desenvolvimento pela API e então definir o domínio de informação desejado. Sugestão como sempre com solução reais são vindas.

De imediado fica sugerido e pré-definido o JSON com formato de troca de mensagens, isso porque se propõe para uso o Rest como método de intercomunicação entre módulos e processos remotos. Seja do cadastro dos PETs, Cuidadores, Veterinários, ao controle das estações de monitoramento e alimentação, tudo passará pelo REST usando assim o JSON para comunicação.

## ID dos sistemas

Todo o sistema será baseado em UUIDs, assim cada objeto tratado terá seu próprio UUID, inclusive os módulos, pode parecer excesso o uso de UUID para os módulos, mas isso irá dar muita flexibilidade ao código, poderemos usar fragmentos destes UUID para identificar intermanete módulos evitando o transito de dados desnecessário.

Para quem não é do ramo pode parecer estranho o uso do termo *Objeto* mas é um linguajar comum na programação, um Veterinário, um Usuário comum, um Pet, um Remédio serão representados por classes de dados, agrupados em domínios e assim instanciados em um objeto, com seu próprio UUID. Lembrando um módulo será uma Classe do Dominio Aplicação que poderá ser estanciada e assim ter seu UUID.

## Geração do UUID

Como inicialmente nosso sistema fica propost por @Carlos Delfino, o uso do Firebase da Google para armazenamento e gerenciamento dos usuários, este também será responsável pela geração de UUIDs, mas o mesmo poderá ser gerado internamente observando as regras padrões para tal geração.

## Banco de Dados

O Banco de dados usado será o oferecido pelo Firebase (Realtime Database), sendo o MongoDB uma alternativa off-line quando o Firebase não for aceitável, e o MySQL como segunda opção e finalmente o NoSQL (ou SQLlite) como armazenamento em casos de memória muito restrita.

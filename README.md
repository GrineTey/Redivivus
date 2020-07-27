# Redivivus
Esse é o projeto que vai ter um sistema de coleta de lixo seletiva, ajudando e contribuindo com o meio ambiente.
A coleta seletiva é método que otimiza os processos de destinação do lixo
Vale a pena ressaltar que "lixo" é uma palavra geral para designar as palavras "resíduo" (os descartes que ainda têm alguma utilização possível por meio da reciclagem ou reutilização) e "rejeito" (aqueles que já não podem ser utilizados novamente).

A importância da coleta seletiva é justamente a redução dos impactos ambientais do consumo. Quando separamos o lixo (ou o que sobrou do que consumimos), facilitamos muito o seu tratamento e diminuímos as chances de impactos nocivos para o ambiente e para a saúde da vida no planeta, incluindo a vida humana. Praticar a coleta seletiva é um dos pilares do consumo sustentável.

## A importância da coleta seletiva

A coleta seletiva exige que os descartes sejam separados em úmidos, secos, recicláveis e orgânicos. E dentro dessas categorias há subcategorias. Os recicláveis, por exemplo, abrangem o alumínio, o papel, o papelão e alguns tipos de plástico, entre outros. Quando os materiais recicláveis são coletados e chegam às cooperativas, eles são separados minuciosamente para serem reaproveitados. O que não é reaproveitado é levado para aterros sanitários.

Todo esse caminho tem muita importância, pois o lixo descartado incorretamente pode causar impactos socioambientais significativos. Nas áreas urbanas, o lixo descartado incorretamente pode se acumular em locais inadequados formando focos de proliferação de mosquitos e de outros vetores de doenças. O vento e a chuva podem transportar o descarte para mares e rios. E o lixo plástico que não passou pela coleta seletiva pode entrar para a cadeia alimentar. Nesse caso, até mesmo o lixo descartado corretamente pode ser transportado pelo vento e pela chuva e parar no oceano, mas os descartes incorretos têm mais chances de serem transportados dessa forma (pelo vento e pela chuva)

## O que a Redivivus pode Contribuir com essa coleta ?



# Alguns Recursos que vão ajudar 

Uma instalação padrão do CI4 possui 6 diretórios:

/application
/system
/public
/writable
/tests
/docs
application

Este diretório é onde todo o código da sua aplicação fica. Ele vem com uma estrutura padrão de diretórios que funcionará muito bem para a maioria as aplicações.

## system

Este diretório armazena os arquivos que permitem que o framework funcione. Enquanto você possui bastante flexibilidade na maneira de usar o diretório application, os arquivos no diretório system nunca devem ser modificados.

Em vez disto, você poderia estender as classes, ou criar novas, para conseguir a funcionalidade desejada.

Todos os arquivos neste diretório ficam sob o namespace CodeIgniter

## public

A pasta public trata da parte que é pública na sua aplicação, prevenindo acesso ao seu código fonte. Ela contém o principal .htaccess, index.php e qualquer outra inclusão que você deseja usar, como CSS, JavaScript ou imagens.

Esta é para ser a pasta “web root” do seu site, e seu servidor deverá ser configurado para apontar para ela.

## writable

Este diretório trata de todos os diretórios que precisam de permissões de escrita enquanto sua aplicação está rodando. Ela inclui diretórios para armazenamento de arquivos de cache, logs e qualquer tipo de atualização que um usuário pode enviar a você.

Se você precisar criar novos diretórios para a sua aplicação que precisam de permissões de escrita, eles devem ser criados aqui dentro.

Isto permite que você mantenha seus outros diretórios principais sem permissões de escrita, adicionando, assim, mais uma camada de proteção à sua aplicação.

## tests

Este diretório está configurado para gerenciar seus arquivos de testes. O diretório _support gerencia várias classes de exemplo e outros utilitários que você pode usar enquanto você faz seus testes.

Este diretório não precisa ser transferido para o seu servidor de produção.

## docs

Este diretório armazena a documentação do CodeIgniter. A pasta user_guide contém uma cópia local do guia do usuário, e a pasta api_docs contém uma cópia local dos componentes da API do CodeIgniter.

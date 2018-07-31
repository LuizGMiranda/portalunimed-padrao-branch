# Novo Processo de Utilização do GIT

## Portal Unimed - Nucleo 1
Criado em 2002, o **Portal Unimed** nasceu de uma formação societária constituída por 11 Unimeds. O objetivo era gerenciar o endereço nacional do Sistema Unimed ([www.unimed.coop.br](http://www.unimed.coop.br/)) e desenvolver soluções em web voltadas para as **Federações e Singulares**.

Direcionando seu foco para a inovação na comunicação digital, em julho de 2018, o Portal Unimed passou por uma reestruturação. As mudanças tiveram como finalidade fortalecer, impulsionar e tornar o Portal Unimed cada vez mais sustentável, para atender com excelência a  **todo o Sistema Unimed**. Dessa maneira, a partir de então, todas as Federações e Singulares podem utilizar o portfólio de produtos e serviços disponíveis no Portal.

Os serviços desenvolvidos são importantes para fortalecer a imagem positiva da marca Unimed perante seus públicos, unificar a comunicação digital de todo o Sistema, gerar ainda mais credibilidade com o mercado e os consumidores e, por fim, auxiliar no crescimento sustentável de todas as cooperativas.

> Link: https://www.portalunimed.com.br/quem-somos

### Núcleo 1 - Institucional
 Núcleo responsavel pelo produtos institucionais como:
 
 - Site Institucional
 - PCT
 - AGI - Ambiente de Gerenciamento Integrado
 - Guia Médico (versão web)

**Equipe:**
[Luiz Gustavo Miranda](https://github.com/LuizGMiranda/) (*Front-end*)
[Felipe Grah](https://github.com/felipegrah) (*Full-stack*)
Fernando Santos (*Back-end*)
Domaris(*Back-end e ScrumMaster*)
Vivian (*Tester*)
Matheus (*Tester*)
Thayse (*Full-stack*)

## Por que mudar?
Mudamos nossa forma de utilização de ramos, pois estava ocorrendo diversos erros no processo de integração de ramos para liberação para demais areas.

## Como irá funcionar?
Após o desenvolvedor pegar a atividade pai (estoria) deve criar um novo ramo a partir do ramo desenv, e desse ramo criar o ramo de sua atividade (back/front/web). Assim que finalizar sua atividade deve fazer o commit das alterações (~~com padrão de commit~~) e tambem o *pull request* para o ramo da estoria. Feito isso a equipe de teste ira rodar o *pipeline* e realizar o teste no ambiente de testes, se reprovado, o time de desenvolvimento deve fazer as devidas correções, se aprovado a atividade passa para o próximo passo. Quando o analista pegar a atividade para fazer a homologação ~~(e o teste de integração)~~, caso encontre erros deve ser aberta uma atividade de bug fix, para o time de desenvolvimento fazer a correção com a **máxima urgencia**. Em seguida, caso aprovado, as alterações são salvas no ramo da master, e gerado uma tag. (~~com versionamento semantico~~).
Podemos visualizar na imagem.
![imagem-visao-geral.png](img1)

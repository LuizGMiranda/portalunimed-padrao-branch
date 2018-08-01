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
 - Intranet
 - Central da Marca

## Por que mudar?
Mudamos nossa forma de utilização de ramos, pois estava ocorrendo diversos erros no processo de liberação das atividades para as demais areas.
 
## Como irá funcionar?
Após o desenvolvedor pegar a atividade pai (estoria) deve criar um novo ramo a partir da *desenv*, e apartir criar o ramo de sua atividade (*back/front/web*). Assim que finalizar a atividade deve fazer o commit das alterações (~~[com padrão de commit](https://conventionalcommits.org/)~~), tambem o *pull request* para o ramo da estoria e ao finalizar todas as atividades filhas deve ser feito o *pull request* para *desenv*. Feito isso a equipe de teste ira rodar o *pipeline* e realizar os testes, caso reprovado, o time de desenvolvimento deve fazer as devidas correções, se aprovado a atividade passa para o próximo passo. Quando o analista pegar a atividade para fazer a homologação ~~(e o teste de integração)~~, caso encontre erros deve ser aberta uma atividade de bug fix, para o time de desenvolvimento fazer a correção, feito a atividade, volta para a etapa de testes. Se aprovado, as alterações são salvas no ramo da master, e gerado uma tag. (~~[com versionamento semantico](https://semver.org/)~~).  

## Overview fluxo geral 
![Visão geral do projeto](https://github.com/LuizGMiranda/portalunimed-padrao-branch/blob/master/imagem-visao-geral.png)

## Overview fluxo atividade
![Visão geral atividade](https://github.com/LuizGMiranda/portalunimed-padrao-branch/blob/master/imagem-visao-atividade.png)

## Papeis
- Desenvolvedor: responsavel pela solução e documentação da atividade
- Tester: responsavel em realizar testes manuais e automatizados
- Analista: responsavel por descrever a atividade e realizar o teste de aceitação
- Scrum Master: responsavel por fazer aceitar o *merge request*
  
  

**Equipe:**  
Domaris Campos(*Back-end e ScrumMaster*)  
Fernando Santos (*Back-end*)  
Thayse (*Full-stack*)  
Natália Bortolás (*Web*)  
Felipe Silva (*Full-stack*)  
Luiz Miranda (*Front-end*)  
Vivian Nygard(*Tester*)  
Matheus Melo (*Tester*)  
# Prova-conceito-Delphi-CadastroCli
Projeto explorando criacao de cadastro de cliente, preenchimento automatico de endereco pelo CEP, JSON, Envio email


  Prova de Conceito de programa para cadastrar um cliente
  com busca de endereco pelo CEP no  https:viacep.com.br/
  consumo formato JSON

  Um arquivo XML e gerado no diretorio onde esta instalado o programa
  com dados informado apos clique no botao SALVAR
  O arquivo e gerado com o nome Cliente.XML

  Obs:
  - Versao utizando DELPHI 7 que nao trata caracteres UNICODE, portanto
    nao apresenta corretamente strings com acentuação
  - Inicialmente o teste de envio de email foi feito em uma aplicação construida
    no Delphi 5 que usava componentes da paleta Fastnet. No Delphi 7 Fastnet foi
    substituida pelo Indyan e nao foi possivel fazer o teste de envio de email
  - Para utilizar componentes do Indyan foi necessário reinstalar os componentes
    e atualizar as duas dlls: libeay32.dll e ssleay32.dll que devem ficar no
    diretorio do programa
  - Para tratamento no formato JSON esta sendo usada Unit uJSON
    criada por Fabio Almeida ( fabiorecife@yahoo.com.br )

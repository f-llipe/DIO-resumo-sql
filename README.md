# DIO-resumo-sql
Repositório criado para documentar a criação de um banco de dados SQL na Azure

**1.** Acesse o portal [Azure](https://portal.azure.com/);\
**2.** No canto superior esquerdo, clique nas **três linhas** e, em seguida, clique em **Criar Recurso**;\
**3.** Na tela de opções, procure por **Banco de dados SQL** e clique em **Criar**;
  - Agora, vamos dividir o processo agora por cada uma das telas de configuração:

## Tela Básico:
  - Assinatura;
  - Grupo de Recursos;
  - Nome do banco;
  - Servidor em que o banco ficará alocado;
> [!NOTE]
> Caso não tenha criado um **Grupo de Recursos** ou um **Servidor** antes, poderá criá-los durante o processo.
  - Ambiente de carga;
  - Computação e armazenamento (para o desempenho do BD);
  - Redundância do backup.

## Tela Rede
- Método de conexão: Endpoint Público (permitindo o acesso RDP);
- Permissão de acesso dos recursos  da Azure ao servidor;
- Adicionar o IP do nosso computador à lista de acessos ao servidor;

## Tela Segurança
  -Habilitar ou não o uso do Microsoft Defender para SQL (irá gerar um custo adicional caso opte por sim).

## Tela Configurações adicionais
  - Fonte de dados: se iremos querer iniciar com um banco vazio ou popular com alguma base que possuímos;
  - Ordenação do banco de dados: definimos a maneira que queremos que o banco ordene e classifique as informações;

## Tela Marcas
  -Definimos TAGs para classificar os recursos e exibir a cobrança relacionada a um grupo de recuros.

## Tela Revisar+Criar
  - Ao acessar essa tela, a plataforma valida as configurações das telas anteriores e aponta erros, caso existam.
  - Caso não haja nenhum erro, Clique em **Criar** e aguarde a finalização do processo.

# UrbanGuard

Protótipo funcional da **UrbanGuard**, uma plataforma de inteligência de riscos urbanos (alagamentos, calor extremo e interrupções de energia, água e transporte). Trabalho da Global Solution 2026.2 da FIAP, disciplina de Engenharia de Software, turma 3ECR.

> Protótipo acadêmico. Todos os dados exibidos são simulados e não representam ocorrências reais.

**Acesse online:** https://gabrielyeshuapasqualigarcia.github.io/GS_ENGSOFT_FIAP_3ECR/

**Repositório:** https://github.com/GabrielYeshuaPasqualiGarcia/GS_ENGSOFT_FIAP_3ECR

## Integrantes

| Nome | RM |
|---|---|
| Gabriel Pasquali | RM558273 |
| Millena Queiroz | RM558825 |
| Nicolas Alvares | RM557271 |

## Como executar

O protótipo é um único arquivo HTML, sem dependências nem instalação.

1. Baixe ou clone este repositório: `git clone https://github.com/GabrielYeshuaPasqualiGarcia/GS_ENGSOFT_FIAP_3ECR.git`
2. Abra o arquivo `index.html` em um navegador atualizado (Chrome, Edge ou Firefox).
3. Na tela de entrada, marque o aceite da política de privacidade, escolha um perfil e clique em **Entrar**.

Para trocar de perfil sem sair, use o seletor no canto superior direito (Morador, Agente ou Operador). Para voltar aos dados iniciais, use **Privacidade e alertas > Restaurar dados de exemplo**.

## Telas

| Código | Tela | Perfis |
|---|---|---|
| T01 | Entrar (perfil e consentimento LGPD) | Todos |
| T02 | Painel de acompanhamento (mapa e indicadores) | Todos |
| T03 | Lista de alertas (filtros e prioridade) | Todos |
| T04 | Detalhe do alerta (risco, orientações e ciclo de vida) | Todos |
| T05 | Origem e nível de confiança do dado | Todos |
| T06 | Central de notificações | Todos |
| T07 | Registro comunitário de ocorrência | Morador |
| T08 | Minhas ocorrências | Morador |
| T09 | Fila de validação | Agente e Operador |
| T10 | Análises e status das fontes de dados | Agente e Operador |
| T11 | Privacidade e preferências | Todos |

## Fluxo principal para testar

1. Entre como **Morador** e abra **Registrar ocorrência**.
2. Escolha *Alagamento*, a altura da água *Na altura do joelho*, adicione a foto e clique em **Enviar ocorrência**.
3. Em **Minhas ocorrências**, veja o protocolo no estado *Em validação*.
4. Troque o perfil para **Agente** e abra **Fila de validação**. Clique em **Confirmar evento**.
5. Volte para **Morador**, abra **Notificações** e clique no novo alerta.
6. No detalhe, veja o ciclo de vida e clique em **Ver origem e confiança dos dados**.

## Tecnologias

HTML, CSS e JavaScript puro, com fonte Public Sans incorporada (licença SIL OFL). O estado da demonstração fica no `localStorage` do navegador.

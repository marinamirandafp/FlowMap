# FlowMap — Diagnóstico de Rotinas e Checklist de Ação

O **FlowMap** é uma aplicação web desenvolvida para transformar relatos soltos e desorganizados de processos e rotinas em uma trilha visual de etapas, diagnóstico de gargalos, sugestões de melhoria e checklist acionável com salvamento automático no navegador.

Acesso ao produto:
- **Aplicação online (GitHub Pages):** [https://marinamirandafp.github.io/FlowMap/]
- **Repositório:** (https://github.com/marinamirandafp/FlowMap)

---

## O Problema e a Proposta
Em equipes, projetos e rotinas recorrentes, processos críticos costumam ficar perdidos em conversas de chat, mensagens avulsas ou anotações soltas, sem dono definido, prazo claro ou critério de prioridade. Isso gera esperas, retrabalho, perda de contexto e urgências sem critério.

O **FlowMap** nasceu da ideia de tirar o processo da bagunça e transformá-lo em um plano claro de execução: o usuário descreve como a rotina acontece hoje (ou testa exemplos prontos) e recebe uma leitura estruturada do fluxo, os pontos onde trava e ações práticas para destravar.

---

## Principais Funcionalidades e Como Funciona
1. **Entrada livre ou exemplos rápidos:** permite preencher **Nome do processo**, **Quem participa / objetivo** e **Como funciona hoje**, ou carregar cenários prontos (*Onboarding de cliente*, *Triagem de pedidos* e *Rotina semanal*).
2. **Métricas e progresso em tempo real:** exibe progresso do checklist, quantidade de etapas mapeadas, pontos de atenção e tempo estimado de ajuste formatado em horas e minutos (ex.: `45 min`, `1h 15min`).
3. **Trilha visual do fluxo:** apresenta a sequência das etapas identificadas com estimativa de ajuste por ponto.
4. **Diagnóstico em 3 colunas:** organiza **Resumo do cenário**, **Onde trava (Gargalos)** e **Como melhorar**.
5. **Checklist de execução com anotações:** converte o relato em ações práticas (*o que fazer*), permite marcar concluídas, adicionar observações por etapa e acompanhar o avanço.
6. **Persistência local (`localStorage`):** salva automaticamente os processos gerados, o estado do checklist e as anotações no navegador do usuário, permitindo reabrir ou excluir registros pela barra **Processos salvos**.

---

## Tecnologias e Ferramentas Utilizadas
- **HTML5, CSS3 e JavaScript puro:** estrutura em arquivo único (`index.html`) para facilitar testes, estabilidade na execução e publicação direta sem dependências complexas de build.
- **Web Storage API (`localStorage`):** persistência local de dados no navegador do usuário.
- **Git, GitHub e GitHub Pages:** versionamento do código e hospedagem estática pública da aplicação.
- **VS Code e navegador web (Chrome):** ambiente de edição, depuração e validação prática.

---

## Uso de Inteligência Artificial no Desenvolvimento
A Inteligência Artificial foi utilizada como parceira de apoio ao longo do processo de construção, combinando geração, revisão de código e validação humana:

- **Ferramentas escolhidas:** assistente de IA conversacional para ideação, estruturação da lógica, diagnóstico de bugs e refinamento de produto, em conjunto com testes manuais no navegador e edição no VS Code.
- **Como cada ferramenta foi aplicada:**
  - *Concepção e proposta de valor:* exploração do problema de processos desorganizados, definição do nome **FlowMap**, estrutura do diagnóstico e formato do pitch.
  - *Construção e depuração técnica:* desenvolvimento da interface, lógica de geração de etapas/gargalos/checklist, formatação de horas e minutos, persistência em `localStorage` e resolução de falhas de execução em JavaScript.
  - *Refinamento de produto e clareza:* ajustes para tornar o checklist mais acionável, evitar cortes na trilha visual e dar identidade visual própria sem aparência genérica.
- **Contribuição para o resultado final:** acelerou iterações, ajudou a identificar e corrigir gargalos de código rapidamente e permitiu focar na clareza da experiência e na entrega completa dentro do prazo, mantendo o critério humano sobre o que faz sentido para o usuário.

---

## Visão de Evolução e Produto
A versão atual valida o fluxo principal de forma simples e funcional no navegador. Como evolução de produto e eventual modelo de recorrência para equipes ou empresas, o FlowMap pode avançar para:
- Integração com IA via API para diagnósticos ainda mais ricos e adaptações por segmento;
- Espaços compartilhados para times, metas e indicadores de redução de gargalos;
- Exportação de planos e relatórios de execução.

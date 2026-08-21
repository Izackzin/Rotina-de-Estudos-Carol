# Rotina-de-Estudos-Carol

---

## 📖 Sobre o Projeto

A Rotina de Estudos - Carol é uma plataforma robusta de organização e produtividade acadêmica, desenvolvida especificamente para atender às necessidades de estudantes do ensino médio em preparação para o PAS (Programa de Avaliação Seriada) da UnB. O projeto foi concebido como uma Single-Page Application (SPA) utilizando tecnologias web puras, garantindo leveza, rapidez e independência de servidores externos para o processamento de dados.

A aplicação opera inteiramente no lado do cliente (client-side), o que significa que a privacidade do usuário é preservada, uma vez que todos os dados — desde cronogramas até notas de boletim — são armazenados localmente no navegador através da API localStorage.

**URL do site:** [https://izackzin.github.io/Rotina-de-Estudos-Carol/](https://izackzin.github.io/Rotina-de-Estudos-Carol/)
**Desenvolvedor:** Isaac Ramos

---

## ✨ Funcionalidades

A plataforma é composta por 14 módulos integrados, acessíveis através de uma navegação lateral intuitiva, cada um projetado para uma etapa específica do ciclo de aprendizagem:

1. **🏠 Início (Dashboard):** Atua como o centro de comando do estudante. Apresenta métricas em tempo real, incluindo o tempo total estudado no dia, contagem de tarefas concluídas, streak (dias consecutivos de estudo) e progresso percentual dos tópicos. Inclui um card de eventos próximos (7 dias) e atalhos para ações rápidas.
2. **⏱️ Timer:** Ferramenta baseada na técnica Pomodoro, mas com tempo flexível (1 a 180 minutos). Possui interface visual com progresso circular e seleção de matéria. Ao zerar, o sistema emite um alerta sonoro e invoca automaticamente o módulo de Pós-Estudo.
3. **📖 Matérias:** Gestão completa do conteúdo programático do 2º e 3º ano. Permite o acompanhamento detalhado de tópicos, marcação de status (Não estudado, Em andamento, Concluído) e inserção de anotações ricas para cada assunto.
4. **📋 Boletim:** Central de notas escolares organizada por bimestres. Realiza o cálculo automático da média aritmética e aplica a regra de negócio de aprovação (média 60), sinalizando visualmente o status do aluno em cada disciplina.
5. **📅 Calendário:** Gestão de prazos fatais. Permite o cadastro de provas, simulados e trabalhos com datas específicas. O sistema calcula automaticamente os dias restantes e prioriza a exibição desses itens no Dashboard.
6. **📐 Referências Rápidas:** Biblioteca de consulta imediata contendo fórmulas matemáticas, conceitos químicos, leis da física e diretrizes de redação. Inclui sistema de busca global e destaque visual para sintaxe matemática.
7. **🔗 Bibliotecas:** Portal de acesso rápido a acervos externos. Contém links diretos e configurados para a Minha Biblioteca e BVirtual, facilitando a pesquisa bibliográfica sem sair do ecossistema de estudo.
8. **📊 Histórico:** Log detalhado de todas as sessões de estudo. Armazena os dados coletados no Pós-Estudo, permitindo que o aluno revise seu desempenho subjetivo (aprendizado) e objetivo (notas e tempo) ao longo do tempo.
9. **📆 Cronograma:** Organizador de rotina semanal. Permite a montagem da grade horária fixa, associando matérias a dias da semana e horários específicos, com integração direta ao Timer.
10. **✅ Tarefas:** Gerenciador de pendências (To-Do List) com níveis de prioridade e datas de vencimento. O sistema identifica e destaca automaticamente tarefas em atraso.
11. **🎯 Metas:** Sistema de gamificação e objetivos. O usuário pode definir metas quantitativas (ex: "estudar 10 horas de Física na semana") e acompanhar a evolução através de barras de progresso dinâmicas.
12. **🃏 Flashcards:** Ferramenta de repetição espaçada. Permite a criação de cartões de memorização com sistema de autoavaliação (Acertei/Errei) e estatísticas de retenção por card.
13. **📈 Estatísticas:** Central de análise de dados. Gera gráficos via SVG que demonstram a distribuição do tempo de estudo, média de notas por disciplina e evolução volumétrica nos últimos 30 dias.
14. **📝 Notas:** Bloco de notas persistente e versátil. Suporta o uso de #hashtags para categorização e possui um motor de busca interno para recuperação rápida de informações.

---

## 🎨 Design e Tema

A interface foi projetada focando na experiência do usuário (UX) e na redução da fadiga visual durante longas sessões de estudo:

*   **Identidade Visual:** Utilização de uma paleta amarela e dourada (#c9971a) que remete ao foco e atenção.
*   **Modos de Visualização:** Suporte nativo a Tema Escuro (preservação ocular) e Tema Claro, alternáveis com um único clique.
*   **Acessibilidade:** Elementos de interface amplos, fontes legíveis e alto contraste.
*   **Responsividade:** Layout adaptável que transiciona a barra lateral para um menu horizontal em dispositivos móveis, mantendo a funcionalidade total em smartphones e tablets.

---

## 🛠️ Tecnologias Utilizadas

O projeto destaca-se pela eficiência técnica ao não utilizar frameworks pesados ou bibliotecas de terceiros, mantendo-se fiel ao Vanilla JavaScript:




Tecnologia
Aplicação no Projeto




HTML5 Semantic
Estruturação da SPA e acessibilidade.


CSS3 Advanced
Grids, Flexbox e animações de transição.


JavaScript (ES6+)
Lógica de negócio, manipulação de DOM e cálculos.


Web Storage API
Persistência de dados local (localStorage).


SVG Dinâmico
Renderização de gráficos estatísticos e donuts.


Web Audio API
Gerenciamento de notificações sonoras do Timer.




---

## 🚀 Como Usar

Para usufruir da plataforma, siga o fluxo operacional recomendado:

1.  **Configuração Inicial:** Acesse o site e utilize os botões de restauração nas abas de Matérias para carregar o conteúdo padrão do PAS/UnB.
2.  **Planejamento:** Cadastre sua rotina semanal no Cronograma e suas datas de provas no Calendário.
3.  **Execução:** No Timer, selecione a matéria do momento e inicie o ciclo. Ao finalizar, preencha o formulário de Pós-Estudo para alimentar seu histórico.
4.  **Monitoramento:** Acompanhe sua evolução na aba Estatísticas e verifique se suas notas no Boletim garantem a aprovação desejada.

---

## 📝 Matérias Cadastradas

A plataforma já vem pré-configurada com a matriz curricular oficial exigida para o PAS:

*   **2º Ano + PAS 2:** Matemática, Química, Física, Biologia, Geografia, História, Português, Filosofia, Sociologia e Inglês.
*   **3º Ano + PAS 3:** Matemática, Química, Física, Biologia, Geografia, História, Português, Redação, Filosofia, Sociologia e Inglês.

---

## 🔄 Recursos de Restauração

Para garantir a segurança dos dados, a plataforma oferece mecanismos de recuperação inteligente:

*   Restaurar Matérias: Caso uma disciplina padrão seja excluída acidentalmente, este recurso a readiciona mantendo quaisquer outras matérias personalizadas criadas pelo usuário.
*   Restaurar Referências: Reinstala o conjunto de fórmulas e conceitos originais da aplicação.

---

© 2026 Isaac Ramos. Projeto de uso educacional.
Site: https://izackzin.github.io/Rotina-de-Estudos-Carol/

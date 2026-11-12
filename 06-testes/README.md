# ETAPA 6 – TESTES, VALIDAÇÃO E APERFEIÇOAMENTO

Nesta etapa, documentou-se o processo de avaliação exploratória do protótipo da plataforma **Mosaico** e como os resultados obtidos orientaram as melhorias de usabilidade e interface.

---

## 1. Plano de Testes de Usabilidade

Para avaliar o protótipo visual e conceitual da plataforma, foram estabelecidas 6 tarefas de teste fundamentais com seus respectivos critérios de sucesso:

| ID | Tarefa de Teste | Descrição da Ação | Critério de Sucesso |
| :--- | :--- | :--- | :--- |
| **T01** | Autenticação por Perfil | Realizar o login na plataforma selecionando o perfil de "Professor". | Acesso liberado e direcionamento correto ao painel docente em menos de 5 segundos. |
| **T02** | Simplificação por IA | Inserir um texto didático extenso na ferramenta e solicitar a versão simplificada. | O sistema deve retornar o texto reformatado em tópicos e linguagem acessível. |
| **T03** | Montagem de Frase (CAA) | Utilizar a prancha de comunicação alternativa para montar a frase "Estou com dúvida". | Seleção dos pictogramas corretos e exibição da frase montada na barra superior. |
| **T04** | Síntese de Voz (Text-to-Speech) | Acionar o botão de reprodução de áudio após montar a frase na prancha. | Emissão de áudio sintetizado de forma clara e sem distorções. |
| **T05** | Diário de Bordo | Registrar um feedback rápido sobre a aula para acompanhamento da família. | Salvamento e envio do registro no perfil vinculado sem erros de interface. |
| **T06** | Ajuste de Acessibilidade | Ativar o modo de alto contraste e alterar a fonte para dislexia. | Mudança imediata do padrão de cores e tipografia em todas as telas. |

---

## 2. Registro da Avaliação Exploratória

* **Público de Teste:** 6 participantes voluntários adultos (3 professores da rede regular de ensino e 3 estudantes/profissionais de TI e educação inclusiva).
* **Metodologia:** Teste de usabilidade exploratório guiado. Os voluntários executaram as 6 tarefas propostas sem intervenções diretas dos moderadores, permitindo a observação natural de dificuldades de navegação.

---

## 3. Identificação de Problemas e Oportunidades de Melhoria

A partir das observações e feedbacks coletados durante os testes, o grupo identificou 4 oportunidades prioritárias de aperfeiçoamento:

1. **Melhoria 01 – Aumento de Contraste dos Pictogramas:**
   * *Problema:* Alguns ícones da prancha de comunicação (CAA) apresentavam baixo contraste em telas com alto brilho.
   * *Ação:* Adição de bordas marcadas e ajuste do fundo dos cards de pictogramas.
2. **Melhoria 02 – Indicador de Carregamento da IA:**
   * *Problema:* Durante o tempo de processamento da simplificação do texto, os usuários relataram dúvida se o sistema havia travado.
   * *Ação:* Inclusão de uma barra de progresso animada ("Processando IA...") para informar o status da requisição.
3. **Melhoria 03 – Expansão da Área de Toque (Touch Target):**
   * *Problema:* Em dispositivos móveis e tablets menores, a seleção de categorias exigia precisão excessiva.
   * *Ação:* Expansão da área clicável dos botões principais da prancha para facilitar o uso por pessoas com dificuldades motoras.
4. **Melhoria 04 – Reorganização do Painel Docente:**
   * *Problema:* Professores relataram leve poluição visual no dashboard inicial.
   * *Ação:* Simplificação do layout, organizando os atalhos em cartões maiores e com ícones intuitivos.

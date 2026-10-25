# workshop-alta-densidade

# Workshop Prático de Alta Densidade — Engenharia de Software / UCB
**Disciplina:** Metodologia Ativa / Engenharia de Software  
**Docente:** Prof. Marco Machado
**Nome do Aluno:** Pedro Lucas Lopes de Melo

---

## ETAPA 1: Autópsia do Problema & Persona Social

### 1. ONG Selecionada
* **Entidade:** Centro Social Comunitário Esperança Viva (Apoio alimentar e capacitação familiar).
* **Localização:** Cidade Estrutural – DF.
* **Atuação principal:** Triagem, cadastro socioeconómico e distribuição mensal de cestas de alimentos para famílias em vulnerabilidade extrema.

### 2. Ficha da Persona Comunitária
* **Nome:** Francisca das Chagas Oliveira.
* **Idade:** 51 anos.
* **Escolaridade:** Ensino Básico incompleto (interpretação de texto técnico limitada).
* **Modelo de Telemóvel:** Samsung Galaxy A03 Core (ecrã com fissuras, pouca memória e acesso à internet condicionado a pacotes móveis reduzidos ou redes públicas).
* **Bloqueio Digital:** Medo acentuado de carregar na opção errada e gerar custos ou perder ficheiros; depende primordialmente de mensagens de voz no WhatsApp; requer letras com dimensão ampla e interface de elevado contraste devido à vista cansada.

### 3. Principais Gargalos de Atrito (Fluxo em Papel/Planilha da Entidade)
1. **Registo manual em fichas de papel:**  
   O preenchimento manuscrito nas filas causa erros na transcrição de dados (números de documentos ilegíveis) e fichas danificadas pela humidade ou manuseio, gerando duplicação de cadastros e atrasos na validação semanal.
2. **Desfasamento no controlo de inventário em tempo real:**  
   O registo de saídas de mantimentos é feito em cadernos ao longo da manhã e inserido em folha de cálculo apenas no fecho do dia, o que causa divergências imediatas entre as senhas distribuídas e as cestas disponíveis em armazém.

---

## ETAPA 2: Matriz de Ação & Wireframe em Papel

### 1. Jornada do Utilizador em 3 Atos

* **Ato 1: Chegada (Identificação Simples)**  
  A beneficiária chega ao local de atendimento sem necessidade de apresentar pilhas de formulários físicos. O voluntário introduz o documento de identificação num ecrã limpo e o sistema valida de imediato a aptidão para a receção do apoio no mês corrente.

* **Ato 2: Operação (Validação Rápida)**  
  O ecrã exibe apenas a confirmação dos dados essenciais (nome completo e situação) e um botão amplo de ação direta: **"CONFIRMAR ENTREGA"**. A confirmação física é realizada com um único toque, efetuando o abate instantâneo da unidade no inventário do sistema.

* **Ato 3: Conclusão com Dignidade (Finalização Transparente)**  
  Apresenta-se uma mensagem de sucesso nítida com indicação clara da data do próximo atendimento programado. O processo decorre com rapidez e discrição, eliminando interrogatórios públicos ou retenção demorada na fila.

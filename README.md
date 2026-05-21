# TelePronto - Protótipo de Baixa Fidelidade

## Nome dos alunos

- Jonathan Eduardo
- Joao Zanardo
- Yago Costa

## Contexto do Projeto

O **TelePronto** é um aplicativo de saúde criado para ajudar pacientes a realizarem triagem, entrarem em uma fila virtual e serem atendidos por vídeo chamada com um médico.

O objetivo principal do aplicativo é desafogar o pronto-socorro físico, permitindo que casos leves sejam avaliados de forma online, além de facilitar o acesso a receitas digitais, lembretes de medicação e informações importantes do tratamento.

O protótipo foi desenvolvido em baixa fidelidade no Miro, com foco em simplicidade, legibilidade e facilidade de uso, principalmente pensando em usuários idosos ou pessoas que estejam passando mal.

---

## Telas do Protótipo

### 1. Home / Dashboard

A tela inicial apresenta o nome do aplicativo **TelePronto** e dois botões principais:

- **Consulta agora**
- **Meus remédios**

A ideia foi deixar as ações mais importantes logo na primeira tela, evitando que o usuário precise procurar muitas opções.

---

### 2. Triagem de Sintomas

Nesta tela, o usuário informa onde está sentindo dor ou quais sintomas está apresentando.

Foi usada uma imagem do corpo humano para facilitar a identificação da região afetada. Também há um campo para digitar informações adicionais e um botão de confirmação.

Essa tela ajuda o sistema a entender melhor o problema antes de direcionar o paciente para a fila de atendimento.

---

### 3. Lista de Espera Virtual

Após confirmar os sintomas, o usuário entra em uma fila virtual.

A tela mostra:

- Quantas pessoas estão na frente;
- O tempo estimado de espera;
- Um botão para sair da lista.

Essa informação ajuda o usuário a entender o estado do sistema e reduz a ansiedade durante a espera.

---

### 4. Interface de Vídeo-Chamada

A tela de atendimento mostra a área da chamada com o médico e os principais controles:

- Câmera;
- Microfone;
- Encerrar chamada;
- Chat.

Também aparece um espaço indicando a presença do médico, permitindo que o usuário saiba quando o atendimento começou.

---

### 5. Histórico de Prescrições

Essa tela apresenta receitas digitais e atestados gerados pelo médico.

Cada prescrição aparece em formato de cartão, contendo:

- Nome do médico;
- Data;
- Medicamentos receitados;
- Duração do tratamento.

A organização em cartões facilita a leitura e ajuda o usuário a encontrar rapidamente suas receitas anteriores.

---

### 6. Lembretes de Medicação

A tela de lembretes permite visualizar alarmes configurados para tomar os medicamentos nos horários corretos.

O objetivo é ajudar o paciente a seguir corretamente o tratamento recomendado pelo médico.

---

## Análise de Acessibilidade

O design foi pensado para ajudar usuários que podem estar com **visão turva, dor, tontura, mal-estar ou dedos trêmulos**.

As principais decisões de acessibilidade foram:

- Uso de botões grandes e fáceis de clicar;
- Poucas opções por tela, evitando confusão;
- Textos simples e diretos;
- Hierarquia visual clara, destacando as ações principais;
- Separação das informações em blocos;
- Fluxo linear, guiando o usuário passo a passo;
- Ícones grandes para facilitar o reconhecimento das funções;
- Evitar excesso de elementos visuais que possam atrapalhar a leitura.

Como o público pode incluir pessoas idosas ou pacientes em situação de desconforto, o protótipo prioriza simplicidade e rapidez no atendimento.

---

## Fluxo Crítico: Iniciar uma Consulta de Urgência

O caminho principal para iniciar uma consulta é:

1. O usuário abre o aplicativo TelePronto.
2. Na tela inicial, toca em **Consulta agora**.
3. O usuário informa onde sente dor ou descreve os sintomas.
4. Confirma as informações da triagem.
5. O sistema direciona o paciente para a **Lista de Espera Virtual**.
6. O usuário acompanha sua posição na fila e o tempo estimado.
7. Quando chega sua vez, ele entra na vídeo-chamada com o médico.
8. Durante a consulta, pode usar câmera, microfone ou chat.
9. Após o atendimento, o usuário pode acessar suas receitas digitais e lembretes de medicação.

Esse fluxo foi pensado para ser rápido, direto e com o menor número possível de etapas.

---

## Prevenção de Erros

Para evitar que o usuário cometa erros durante o uso do aplicativo, foram aplicadas algumas decisões de design:

- Os botões principais ficam destacados e separados de ações menos importantes.
- O botão de sair da lista aparece de forma clara, mas não misturado com o botão de continuar atendimento.
- Na vídeo-chamada, o botão de encerrar chamada fica separado dos botões de câmera, microfone e chat.
- A ação de encerrar consulta deve ter uma confirmação, como:  
  **“Tem certeza que deseja encerrar a consulta?”**
- As telas possuem poucos elementos para reduzir cliques errados.
- O usuário recebe informações sobre o estado do sistema, como posição na fila e tempo estimado.
- Os textos são curtos para diminuir erros de interpretação.

Essas escolhas ajudam principalmente usuários que estejam nervosos, com dor ou com dificuldade de concentração.

---

## Decisões de UX

As principais decisões de UX foram tomadas com foco em confiança, simplicidade e rapidez.

O botão **Consulta agora** foi colocado logo na tela inicial porque é a principal necessidade do usuário em uma situação de urgência leve.

A triagem foi feita de forma visual para facilitar o entendimento, principalmente para quem tem dificuldade de explicar sintomas apenas digitando.

A lista de espera mostra informações importantes para que o usuário saiba que o sistema está funcionando e que ele será atendido.

Na tela de vídeo-chamada, os controles principais foram colocados de forma simples para que o paciente consiga interagir facilmente com o médico.

As receitas e lembretes foram separados em telas próprias para facilitar o acompanhamento do tratamento depois da consulta.

---

## Ferramenta Utilizada

O protótipo foi desenvolvido utilizando a ferramenta **Miro**, seguindo a proposta de criação de wireframes simples de baixa fidelidade.

---

## Conclusão

O protótipo do **TelePronto** busca oferecer uma experiência simples, acessível e confiável para usuários que precisam de atendimento médico rápido.

A interface foi pensada para reduzir confusão, facilitar a navegação e ajudar pacientes em momentos de mal-estar, mantendo as principais ações sempre claras e fáceis de acessar.

# 2025: Uma Odisseia no Mundo Quântico 
**Hackathon Qiskit Fall Fest 2025 - UFABC**
**Equipe 4** 
Erika Feitosa - erikamcfeitosa@gmail.com
Lucas da Mata - lucasdamata01@hotmail.com
Ricardo Silva - ricardo_skarline@hotmail.com
Samuel Duarte - samucacalcopietro@gmail.com

---

## Introdução

2025: Uma Odisseia no Mundo Quântico faz alusão ao clássico “2001: Uma Odisseia no Espaço”, de Stanley Kubrick — uma jornada sobre os limites do conhecimento humano.

O ano 2025, declarado Ano das Tecnologias Quânticas, simboliza o início de uma nova era: a democratização do acesso ao mundo quântico.

Assim como o filme explorou o mistério do espaço e da consciência, este projeto convida o público a embarcar em uma odisseia intelectual, descobrindo como a física quântica pode ser acessível, visual e interativa.

---

## O Problema

A computação quântica ainda é percebida como algo inacessível, restrita apenas a quem domina matemática avançada ou física teórica.  
Nosso desafio foi **democratizar o aprendizado dos conceitos quânticos** de forma intuitiva, interativa e visual.

Este projeto transforma os fenômenos de superposição e colapso em uma experiência lúdica e interativa, na qual o participante pode aplicar portas quânticas, medir o qubit e visualizar os resultados no circuito e na esfera de Bloch.
De forma intuitiva, o jogo introduz os princípios de qubits, circuitos quânticos e medição, sem recorrer a formalismos matemáticos.

---

## Conceitos Quânticos Aplicados

### 1. Quibit e Superposição
O qubit é a unidade fundamental da informação quântica.
No jogo, ele inicia no estado |0⟩ e, ao aplicar a porta Hadamard (H), entra em superposição — passando a representar simultaneamente os estados |0⟩ e |1⟩.
Essa etapa é visualizada na esfera de Bloch, que representa o qubit entre os polos clássico de 0 e 1.

### 2. Portas Quânticas e Transformações de Estado
As portas quânticas funcionam como operações lógicas que alteram o estado do qubit.
No jogo, o participante pode aplicar:
Porta H (Hadamard): coloca o qubit em superposição.
Porta X: inverte o estado.
Porta Z: altera a fase do qubit.
Porta Y: rotação combinada entre X e Z.
Essas transformações são imediatamente refletidas no circuito quântico exibido no notebook.

### 3. Medição e Colapso da Função de Onda
Ao medir o qubit, ocorre o colapso da função de onda — o estado deixa de ser uma combinação probabilística e assume um valor clássico (|0⟩ ou |1⟩).
A simulação no Qiskit mostra esse colapso de forma probabilística, de acordo com o histórico de portas aplicadas.

### 4. Interatividade
O notebook utiliza widgets interativos (botões) para o jogador escolher ações: aplicar portas (X, H) ou medir.  
Cada escolha altera o circuito e a visualização, criando um aprendizado ativo e engajante e ajudado o jogador a construir intuição visual sobre o comportamento quântico — algo que normalmente é ensinado apenas com matemática complexa.

---

## Como Executar

1. Acesse o notebook: 2025: Uma Odisseia no Mundo Quântico

2. Clique em “Executar tudo” (Ctrl + F9 ou Runtime > Run all) para iniciar a simulação.

3. Interaja com o circuito e observe:
- a mudança do estado do qubit na esfera de Bloch;
- o circuito quântico se atualizando;
- e o resultado da medição em tempo real.

---

## Resultados Esperados

Durante o jogo, você observará:
- O **circuito quântico** sendo atualizado conforme as ações.
- O **estado do qubit** mudando na **esfera de Bloch**.
- Ao **medir**, o sistema **colapsa** para `|0⟩` ou `|1⟩`, com probabilidades determinadas pelas portas aplicadas.

---

## Limitações

Durante o desenvolvimento, percebemos que **traduzir conceitos abstratos em experiências visuais** é uma das formas mais eficazes de ensinar computação quântica.

**Limitações:**
- O jogo utiliza apenas um qubit, sem explorar emaranhamento, interferência ou ruído quântico.
- A visualização 3D (esfera de Bloch) depende do ambiente do Google Colab, o que pode limitar a fluidez da interação.
- A interação é feita via botões no notebook, e não em uma interface independente.

OBS: Os conceitos físicos e matemáticos foram propositalmente simplificados para fins educacionais — o foco está na intuição, não na formalização rigorosa.

**Próximos passos:**
- Expandir o jogo para mais de um qubit, introduzindo emaranhamento e portas controladas (como CNOT).
- Criar uma versão web interativa para maior acessibilidade.
- Incluir níveis de complexidade, permitindo que o jogador explore desde conceitos básicos até fenômenos mais avançados, como interferência quântica e decoerência.

---

### Tecnologias Utilizadas
- Qiskit
- Qiskit Aer Simulator
- Matplotlib
- IPyWidgets
- Pylatexenc

---


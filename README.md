  **Projeto A3 — Sistemas Automatizados**
 
  Curso: Engenharia de Software
  Unidade Curricular: Sistemas Automatizados
  Instituição: Universidade São Judas Tadeu – USJT
  Semestre: 2026/1
  Professor: Prof. Robson Calvetti

  Integrante:
   Kauê Melo Diniz | 823130975 

  ## Descrição do Projeto

  Este projeto consiste no desenvolvimento e simulação de um sistema automatizado para controle de abertura e fechamento
  de portão de garagem utilizando lógica de programação de CLP (Controlador Lógico Programável) em ambiente virtual.

  O sistema simula um portão residencial automatizado, contemplando os principais estados e condições de segurança
  presentes em aplicações reais.

  ---

  ## Funcionalidades do Sistema

  - Comando de abertura e fechamento via botão
  - Sensores de posição (portão aberto / portão fechado)
  - Detecção de obstáculos durante o fechamento
  - Parada automática em caso de obstáculo
  - Retomada do ciclo após remoção do obstáculo

  ---

  ## Estados do Sistema

  | Estado | Descrição |
  |--------|-----------|
  | Fechado | Portão completamente fechado, aguardando comando |
  | Abrindo | Motor acionado, portão em movimento de abertura |
  | Aberto | Portão completamente aberto, aguardando comando |
  | Fechando | Motor acionado, portão em movimento de fechamento |
  | Parado | Obstáculo detectado, sistema em espera |

  ---

  ## Entradas e Saídas (CLP)

  ### Entradas (Sensores / Botões)
  | Variável | Descrição |
  |----------|-----------|
  | I0.0 | Botão de comando (abre/fecha) |
  | I0.1 | Sensor de posição — portão aberto |
  | I0.2 | Sensor de posição — portão fechado |
  | I0.3 | Sensor de obstáculo |

  ### Saídas (Atuadores)
  | Variável | Descrição |
  |----------|-----------|
  | Q0.0 | Motor — sentido abertura |
  | Q0.1 | Motor — sentido fechamento |
  | Q0.2 | Sinaleiro de aviso (luz/buzzer) |

  ---

  ## Ferramentas Utilizadas

  - **Simulador:** [PLC Fiddle](https://www.plcfiddle.com) — simulador online de lógica Ladder
  - **Linguagem de programação:** Ladder (LD)
  - **Documentação:** Padrão ABNT

  ---

  ## Estrutura do Repositório

  a3-sistemas-automatizados/
  ├── README.md
  ├── documentacao/
  │   └── relatorio.pdf
  ├── apresentacao/
  │   └── slides.pptx
  └── simulacao/
      └── logica-ladder.md

  ---

  ## Entregáveis

  - [x] Repositório GitHub
  - [ ] Relatório técnico (PDF — padrão ABNT)
  - [ ] Apresentação em slides (PPTX)
  - [ ] Simulação funcional no PLC Fiddle

  ---

  ## Instituição

  Universidade São Judas Tadeu – USJT
  © 2026 — Kauê Melo Diniz


Sistema de Controle de Missões Espaciais 🚀

Projeto desenvolvido em C++ para a disciplina de Linguagem de Programação 1 do Instituto Metrópole Digital (IMD/UFRN).

O sistema simula o gerenciamento de astronautas e voos espaciais, permitindo cadastrar astronautas, organizar missões, lançar voos, finalizar missões ou registrar explosões.


---

📚 Sobre a atividade

Esta atividade foi proposta na disciplina com o objetivo de praticar:

Programação em C++

Estruturas de dados com vector

Manipulação de strings

Organização de código

Leitura de comandos pela entrada padrão

Controle de estados e validações



---

⚙️ Funcionalidades

O programa permite:

👨‍🚀 Gerenciamento de astronautas

Cadastro de astronautas

Controle de disponibilidade

Controle de vida/morte


🚀 Gerenciamento de voos

Cadastro de voos

Adição e remoção de astronautas

Lançamento de missões

Finalização de voos

Explosão de voos


📋 Listagens

Listagem de todos os voos por estado

Listagem de astronautas mortos

Histórico de participação em voos



---

🧠 Estados dos voos

Cada voo pode estar em um dos seguintes estados:

planejado

em curso

finalizado com sucesso

finalizado com explosão



---

📂 Estrutura do projeto

.
├── main.cpp
├── eventos.txt
└── README.md


---

▶️ Como compilar

Utilizando o compilador g++:

g++ main.cpp -o agencia


---

▶️ Como executar

Execução manual

./agencia

Execução usando arquivo de comandos

./agencia < eventos.txt


---

📝 Exemplo de entrada

Arquivo eventos.txt:

CADASTRAR_ASTRONAUTA 111 30 Ana Maria
CADASTRAR_ASTRONAUTA 222 35 Bruno
CADASTRAR_VOO 10
ADICIONAR_ASTRONAUTA 111 10
ADICIONAR_ASTRONAUTA 222 10
LANCAR_VOO 10
FINALIZAR_VOO 10
LISTAR_VOOS
LISTAR_MORTOS
FIM


---

📌 Comandos disponíveis

Cadastro de astronauta

CADASTRAR_ASTRONAUTA cpf idade nome

Cadastro de voo

CADASTRAR_VOO codigo

Adicionar astronauta ao voo

ADICIONAR_ASTRONAUTA cpf codigo

Remover astronauta do voo

REMOVER_ASTRONAUTA cpf codigo

Lançar voo

LANCAR_VOO codigo

Explodir voo

EXPLODIR_VOO codigo

Finalizar voo

FINALIZAR_VOO codigo

Listar voos

LISTAR_VOOS

Listar astronautas mortos

LISTAR_MORTOS

Encerrar programa

FIM


---

🛠️ Tecnologias utilizadas

Linguagem: C++

Biblioteca padrão:

iostream

string

vector




---

📖 Conceitos aplicados

Structs/classes

Vetores dinâmicos (vector)

Enumerações (enum)

Ponteiros

Busca em coleções

Entrada e saída padrão

Manipulação de estados

Validações de regras de negócio



---

👨‍💻 Autor

Desenvolvido por Mayan Victor para fins acadêmicos na disciplina de Linguagem de Programação 1 — IMD/UFRN.

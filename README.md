# 🎲 Projeto DOMINÓ – Jogo Educativo e de Entretenimento  

**Integrantes:** Deborah Carvalho | Gustavo Negrão | João Pedro | Matheus Reis  
**Instituição:** PUC-SP  
**Ano:** 2024  

---

## 📋 Descrição  

O **Projeto DOMINÓ** é um jogo desenvolvido em **C**, com fins educativos e de entretenimento.  
O jogo pode ser jogado:  

- 👤 Sozinho contra a **CPU**  
- 👥 Dois jogadores, um contra o outro  

O sistema foi implementado utilizando o padrão de arquitetura **MVC (Model-View-Controller)**, dividido em módulos para melhor organização e manutenção.  

---

## 🕹️ Funcionalidades  

- Iniciar jogo para **dois jogadores**  
- Iniciar jogo **contra a CPU**  
- Retomar jogo interrompido  
- **Salvar** e **Carregar** partida  
- Jogar peça, comprar peça e passar a vez  
- Visualizar as **regras**  
- **Sair** para o menu principal  

---

## 🗂️ Estrutura de Arquivos  

- `DOM_DGJM_Controller.cpp / .h` → Controle do fluxo do jogo (turnos, jogadas, fim de jogo)  
- `DOM_DGJM_Model.cpp / .h` → Estruturas de dados e inicialização das peças e mesa  
- `DOM_DGJM_View.cpp / .h` → Interface textual com menus, regras e exibição da mesa  
- `DOM_DGJM_PROJETO.cpp` → Arquivo principal (ponto de entrada do programa)  
- `CAD_DOMINO.txt` → Estado das peças (salvamento)  
- `CAD_MESA.txt` → Estado da mesa (salvamento)  
- `CAD_JOGO.txt` → Variáveis do jogo (salvamento)  

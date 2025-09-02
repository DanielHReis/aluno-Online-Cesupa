# Sistema de Autenticação e Portal do Aluno

Este projeto é um sistema de autenticação e portal do aluno desenvolvido em C, simulando um ambiente acadêmico onde estudantes podem acessar suas informações pessoais, notas, frequência e dados financeiros.

## 📋 Funcionalidades

### 🔐 Sistema de Autenticação
- **Login seguro** com matrícula e senha
- **Alteração de senha** com confirmação
- Três usuários pré-cadastrados com diferentes perfis

### 👤 Perfis de Usuários Cadastrados
1. **Daniel Henrique Reis e Silva** (Matrícula: 25070104)
2. **Daniel Barros Pinto Do Rego** (Matrícula: 25070092) 
3. **Pedrinho Girotaum** (Matrícula: 24070001)

### 📊 Menu Principal (Após Login)
- **Informações Cadastrais**: Dados pessoais completos do aluno
- **Notas e Frequência**: Desempenho acadêmico e registro de presenças
- **Pagamentos**: Histórico de mensalidades e status financeiro
- **Atividades Complementares**: Registro de atividades extracurriculares

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: C
- **Compilador**: GCC (MinGW)
- **Sistema Operacional**: Windows
- **IDE**: Visual Studio Code com extensão C/C++

## 📁 Estrutura do Projeto
projeto/
├── prova.c # Código fonte principal
├── c_cpp_properties.json # Configuração do compilador
├── launch.json # Configuração de debug
├── tasks.json # Tarefas de build
└── settings.json # Configurações do workspace

## 🚀 Como Executar

### Pré-requisitos
- GCC instalado (MinGW recomendado)
- Visual Studio Code
- Extensão C/C++ para VS Code

### Compilação e Execução
1. Abra o projeto no VS Code
2. Compile o código usando `Ctrl+Shift+B`
3. Execute o programa gerado (`prova.exe`)

### Execução Direta
```bash
gcc prova.c -o prova.exe
./prova.exe

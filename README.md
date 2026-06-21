# 🎮 Pong Arena System

Um sistema de Pong multiplayer local em Python. Autenticação de jogadores, ranking persistente, histórico de matches e tudo integrado com SQLite.

---

## ⚙️ Funcionalidades

- ✅ **Autenticação**: Login com username e senha (bcrypt)
- ✅ **Ranking Global**: Placar persistente em SQLite
- ✅ **Histórico de Matches**: Registro de todos os jogos
- ✅ **Exportação**: Dados em CSV para análise
- ✅ **Suporte Joystick**: Compatível com controles
- ✅ **Multiplayer Local**: Dois jogadores, mesma tela
- ✅ **Estrutura Modular**: Código organizado e testável

---

## 🛠️ Tecnologias

- **Python** 3.8+
- **Pygame** - Renderização e game loop
- **SQLite** - Persistência de dados
- **bcrypt** - Hash seguro de senhas

---

## 📦 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/gabrielinfosec/Pong-Arena-System.git
cd Pong-Arena-System
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Execute

```bash
python pingpong.py
```

---

## 🎮 Como Jogar

### Controles

**Jogador 1 (Esquerda)**
- `W` - Mover para cima
- `S` - Mover para baixo

**Jogador 2 (Direita)**
- `UP ARROW` - Mover para cima
- `DOWN ARROW` - Mover para baixo

**Geral**
- `ESC` - Sair do jogo

### Joystick
Se conectar um joystick, os controles serão automaticamente mapeados.

---

## 📂 Estrutura do Projeto

```
Pong-Arena-System/
├── pingpong.py           # Arquivo principal
├── criar_pong.py         # Setup inicial
├── requirements.txt      # Dependências
├── README.md
├── .gitignore
└── dados/
    └── jogadores.db      # Banco de dados (criado automaticamente)
```

---

## 🚀 Primeiro Uso

1. Execute o programa
2. Crie sua conta (username + senha)
3. Selecione outro jogador para começar
4. Jogue até 10 pontos para vencer

Os dados são salvos automaticamente no SQLite.

---

## 💾 Dados

Os seguintes dados são persistidos:

- **Jogadores**: ID, username, hash de senha, data de criação
- **Matches**: ID, jogadores, placar, data
- **Ranking**: Vitórias, derrotas, taxa de vitória

---

## 📌 Próximas Features

- [ ] Modo contra IA
- [ ] Interface melhorada
- [ ] Sons e efeitos
- [ ] Estatísticas avançadas
- [ ] Modo online

---

## 👨‍💻 Autor

**Gabriel** - [@gabrielinfosec](https://github.com/gabrielinfosec)

Estudante de Análise e Desenvolvimento de Sistemas | Focado em Cybersecurity

---

## 📄 Licença

Este projeto está aberto para uso e aprendizado.

---

**Feedback?** Abra uma issue ou faça um pull request.

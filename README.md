
# 💣 Campo Minado em Java (Swing)

Este é um projeto de um jogo **Campo Minado** desenvolvido em Java com interface gráfica usando Swing. O jogo é iniciado na classe `TelaPrincipal` e permite jogar em um tabuleiro padrão com 16 linhas, 30 colunas e 50 minas.

---

## 📦 Estrutura do Projeto

```
campo-minado-swing/
├── src/
│   └── br/com/cod3r/cm/
│       ├── modelo/
│       │   ├── Campo.java
│       │   ├── CampoEvento.java
│       │   ├── CampoObservador.java
│       │   ├── ResultadoEvento.java
│       │   └── Tabuleiro.java
│       └── visao/
│           ├── BotaoCampo.java
│           ├── PainelTabuleiro.java
│           └── TelaPrincipal.java
```

---

## ⚙️ Requisitos

- **Java JDK 8 ou superior** (é necessário o **JDK**, não apenas o JRE)
- Opcionalmente, uma IDE como **Eclipse**

Para verificar se o Java está instalado corretamente:

```bash
java -version
javac -version
```

Se `javac` não for reconhecido, verifique se o JDK está instalado e o caminho `<caminho do jdk>/bin` está no `PATH`.

---

## 🚀 Como Rodar o Projeto

### ✅ Usando o **Eclipse**

1. Abra o Eclipse
2. Vá em `File > New > Java Project`
3. Nomeie o projeto como `CampoMinado` e clique em **Finish**
4. Clique com o botão direito no projeto > `New > Package` e crie:
   - `br.com.cod3r.cm.modelo`
   - `br.com.cod3r.cm.visao`
5. Copie os arquivos `.java` do repositório para os pacotes correspondentes
6. Localize a classe `TelaPrincipal.java` no pacote `br.com.cod3r.cm.visao`
7. Clique com o botão direito > `Run As > Java Application`

---

### ✅ Usando o **Terminal (sem IDE)**

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/campo-minado-swing.git
cd campo-minado-swing
```

2. **Crie o diretório `bin/`**, se ainda não existir:

```bash
mkdir bin
```

3. Compile os arquivos:

```bash
javac -d bin src/br/com/cod3r/cm/modelo/*.java src/br/com/cod3r/cm/visao/*.java
```

4. Execute o jogo:

```bash
java -cp bin br.com.cod3r.cm.visao.TelaPrincipal
```

---

## 🎮 Sobre o jogo

- O tabuleiro tem **16 linhas**, **30 colunas** e **50 minas**
- Interface gráfica construída com Java Swing
- Clique para revelar campos e evite as minas!

## Olá, eu sou o Matheus Henrique 👋

Desenvolvo software para **áudio e música** em Python, com foco em aplicações
desktop e automação de processos.

🎓 Estudante de Análise e Desenvolvimento de Sistemas na Cruzeiro do Sul Virtual (UNICID)

---

### 🛠 Stack

**Uso no dia a dia**

| | |
|---|---|
| Linguagem | Python |
| Interfaces desktop | Kivy, Flet |
| Processamento de sinais | NumPy |
| Testes e qualidade | pytest, GitHub Actions |
| Versionamento | Git |
| Distribuição | PyInstaller, Inno Setup |

**Estudando ativamente**

- **C++ e JUCE** — para portar processamento de áudio a plugins VST3
- **TypeScript** — versão web do meu afinador, reaproveitando a lógica já testada

---

### 📌 Projetos

#### 🎸 [BWRLD Tuner](https://github.com/matheusbutexistworld/bwrld_tuner)

Afinador cromático em tempo real para guitarra e baixo. Detecção de pitch por
autocorrelação via FFT, com correção de erro de oitava, afinação de referência
440/432/415 Hz e interface em português e inglês.

A lógica musical é isolada da interface e da captura de áudio — regra garantida
por um teste que lê o AST de cada módulo. **193 testes, 98% de cobertura e CI
rodando em Python 3.11 e 3.12.**

`Python` `NumPy` `Kivy` `pytest` `GitHub Actions`

> Escrever os testes revelou um erro que o uso manual não mostrava: o detector
> lia até 22 cents acima do real nas notas graves. O afinador marcava "afinado"
> com a corda baixa. Corrigido, o desvio caiu para menos de 1 cent.

#### 📄 Suite CSC — *projeto corporativo, código privado*

Aplicação multiferramenta para manipulação de PDFs, 100% offline por requisito
de segurança: documentos sensíveis não saem da máquina. Empacotada com
PyInstaller e Inno Setup para rodar em computadores sem Python instalado.

`Python` `Flet` `PyInstaller` `Inno Setup`

---

### 🎯 Interesses

- Processamento de áudio em tempo real e DSP
- Aplicações desktop que funcionam offline
- Automação de processos repetitivos
- Arquitetura em camadas e testes automatizados

---

### 📫 Onde me encontrar

[LinkedIn](https://www.linkedin.com/in/matheus-henrique-47583b409/)

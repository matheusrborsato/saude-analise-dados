# 🏥 Análise de Hábitos de Saúde

> Projeto de Análise de Dados para Iniciantes — desenvolvido com Python e Google Colab

---

## 📋 Sobre o Projeto

Este projeto analisa dados sobre hábitos de saúde de 40 participantes fictícios, explorando indicadores como **IMC**, **sono**, **exercícios**, **hidratação** e **estresse**.

O objetivo é praticar Análise de Dados do zero, de forma didática e comentada.

---

## 🔍 Perguntas que o projeto responde

- 📊 Qual é a distribuição do IMC dos participantes?
- 😴 As pessoas estão dormindo o suficiente (recomendação da OMS)?
- 🏃 Quem se exercita mais — homens ou mulheres?
- 💧 Existe relação entre consumo de água e nível de estresse?
- 🚬 Quantas pessoas fumam?

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Para que serve |
|---|---|
| `Python 3` | Linguagem de programação principal |
| `pandas` | Manipulação e análise de dados (como um Excel em código) |
| `matplotlib` | Criação de gráficos |
| `seaborn` | Gráficos mais elaborados e bonitos |
| `Google Colab` | Ambiente de execução (sem instalação!) |

---

## 📁 Estrutura do Projeto

```
saude-analise-dados/
│
├── 📓 analise_saude.ipynb     ← Notebook principal com toda a análise
│
└── 📂 dados/
    └── saude_dados.csv        ← Dataset com os dados dos participantes
```

---

## 🚀 Como Executar

### Opção 1 — Google Colab (Recomendado, sem instalação!)

1. Acesse [colab.research.google.com](https://colab.research.google.com)
2. Clique em **"Arquivo" → "Fazer upload de notebook"**
3. Suba o arquivo `analise_saude.ipynb`
4. Na primeira célula de código, adicione este trecho para carregar os dados:

```python
# Cole este código na primeira célula do Colab para subir o arquivo CSV
from google.colab import files
uploaded = files.upload()  # Selecione o arquivo saude_dados.csv
```

5. Execute cada célula clicando no botão ▶ ou pressionando `Shift + Enter`

---

### Opção 2 — Localmente com Python instalado

```bash
# 1. Clone o repositório
git clone https://github.com/SEU_USUARIO/saude-analise-dados.git
cd saude-analise-dados

# 2. Instale as dependências
pip install pandas matplotlib seaborn jupyter

# 3. Abra o Jupyter Notebook
jupyter notebook analise_saude.ipynb
```

---

## 📊 Prévia dos Dados

| Coluna | Descrição |
|---|---|
| `nome` | Nome do participante |
| `idade` | Idade em anos |
| `sexo` | M (Masculino) ou F (Feminino) |
| `peso_kg` | Peso em quilogramas |
| `altura_cm` | Altura em centímetros |
| `horas_sono` | Horas de sono por noite |
| `dias_exercicio_semana` | Dias por semana com atividade física |
| `litros_agua_dia` | Litros de água consumidos por dia |
| `nivel_estresse` | Nível de estresse de 1 (baixo) a 10 (alto) |
| `qualidade_alimentacao` | Qualidade da dieta de 1 a 10 |
| `fuma` | Sim ou Não |
| `consultas_medicas_ano` | Consultas médicas realizadas no último ano |

---

## 📚 O que você vai aprender

- ✅ Como carregar e explorar um dataset com `pandas`
- ✅ Como calcular estatísticas básicas (média, mín., máx.)
- ✅ Como criar novas colunas com cálculos próprios (ex: IMC)
- ✅ Como criar gráficos de barras, pizza, histograma e dispersão
- ✅ Como interpretar uma correlação entre variáveis

---

## 👤 Autora / Autor

Feito com 💚 como projeto de aprendizado em Análise de Dados.

---

## 📄 Licença

Este projeto é de uso livre para fins educacionais.

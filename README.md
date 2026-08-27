# CardioIA – Fase 1: Batimentos de Dados

## Projeto Acadêmico – FIAP | Inteligência Artificial

O **CardioIA** é um projeto acadêmico desenvolvido no curso de Inteligência Artificial da FIAP com o objetivo de simular um ecossistema de cardiologia inteligente.

Na **Fase 1 – Batimentos de Dados**, assumimos o papel de cientistas de dados hospitalares e realizamos a coleta, organização e documentação de diferentes tipos de dados relacionados à saúde cardiovascular.

Esta etapa tem como objetivo construir uma base de dados multimodal que poderá ser utilizada nas próximas fases do projeto para o desenvolvimento de soluções envolvendo Machine Learning, Processamento de Linguagem Natural (NLP), Visão Computacional e outros recursos de Inteligência Artificial.

A Fase 1 está dividida em três partes:

1. **Dados Numéricos – IoT / Machine Learning**
2. **Dados Textuais – NLP (Natural Language Processing)**
3. **Dados Visuais – Visão Computacional**

Além da coleta dos dados, também foram considerados aspectos relacionados à qualidade, governança, privacidade, ética e possíveis vieses presentes nas bases utilizadas.

---

# PARTE 1 – DADOS NUMÉRICOS (IoT)

## 1.1 Objetivo

A primeira parte do projeto consiste na organização de um conjunto de dados estruturados contendo informações relacionadas à saúde cardiovascular.

O dataset possui mais de **100 registros**, atendendo ao requisito mínimo estabelecido para a atividade.

Os dados foram organizados no formato `.CSV` ou `.XLSX`, permitindo sua utilização futura em ferramentas como Python, Pandas, Excel e bibliotecas de Machine Learning.

---

## 1.2 Variáveis do Dataset

O conjunto de dados contém variáveis relacionadas a fatores clínicos e cardiovasculares, como:

- Idade;
- Sexo;
- Pressão arterial;
- Colesterol;
- Frequência cardíaca;
- Histórico de doenças cardíacas;
- Sintomas;
- Outros indicadores relacionados à saúde cardiovascular.

---

## 1.3 Variáveis Clinicamente Relevantes

### Idade

A idade é um importante fator relacionado ao risco cardiovascular. O risco de diversas doenças cardiovasculares tende a aumentar com o envelhecimento, tornando essa variável relevante para modelos de classificação e previsão.

### Sexo

Diferenças biológicas e epidemiológicas podem influenciar a incidência e a manifestação de doenças cardiovasculares. Essa variável também é importante para avaliar a representatividade da base e possíveis vieses existentes nos dados.

### Pressão arterial

A hipertensão arterial é um importante fator de risco cardiovascular. Valores elevados de pressão arterial podem estar associados ao aumento do risco de diferentes complicações cardiovasculares.

### Colesterol

Alterações nos níveis de colesterol estão relacionadas ao desenvolvimento de aterosclerose e podem contribuir para o aumento do risco cardiovascular.

### Frequência cardíaca

A frequência cardíaca fornece informações sobre o funcionamento do sistema cardiovascular e pode contribuir para a identificação de determinados padrões ou alterações.

### Histórico de doença cardíaca

O histórico clínico permite identificar pacientes que apresentam antecedentes cardiovasculares, podendo representar uma variável relevante para modelos de avaliação de risco.

### Sintomas

Sintomas como dor no peito, falta de ar, palpitações, fadiga, tontura e desmaios podem fornecer informações importantes para sistemas de triagem e classificação.

---

## 1.4 Aplicações em Inteligência Artificial

Os dados numéricos poderão ser utilizados futuramente em aplicações como:

- Classificação de risco cardiovascular;
- Identificação de padrões;
- Análise de fatores de risco;
- Modelos preditivos;
- Triagem automatizada;
- Sistemas de apoio à decisão;
- Agrupamento de pacientes com características semelhantes;
- Estudos de correlação entre variáveis clínicas.

---

## 1.5 Origem dos Dados Numéricos

Os dados utilizados nesta etapa foram organizados para fins acadêmicos dentro do contexto do projeto CardioIA.

Caso sejam utilizados dados simulados, eles foram elaborados de forma a representar características clínicas relacionadas à saúde cardiovascular sem utilizar informações pessoais identificáveis de pacientes reais.

**Fonte / origem do dataset:**

(https://www.physionet.org/content/ptb-xl/1.0.3/?utm_source=chatgpt.com)

---

## 1.6 Acesso aos Dados Numéricos

O conjunto completo de dados numéricos está disponível no link abaixo:

(https://drive.google.com/drive/u/1/folders/1d3g1aWClhOTMOwJblMnkSMSHsVCe2HXx)

O arquivo também está disponível na pasta `data` deste repositório.

```text
data/
└── cardioia_dados_numericos_iot.xlsx
```

---

# PARTE 2 – DADOS TEXTUAIS (NLP)

## 2.1 Objetivo

A segunda parte do projeto consiste na coleta e organização de textos relacionados à saúde cardiovascular.

Foram selecionados no mínimo **dois textos**, armazenados no formato `.TXT`.

Os documentos podem abordar temas como:

- Doenças cardiovasculares;
- Sintomas;
- Fatores de risco;
- Prevenção;
- Diagnóstico;
- Tratamentos;
- Saúde pública;
- Cardiologia.

Os arquivos foram armazenados na pasta `docs` deste repositório.

---

## 2.2 Organização dos Arquivos

A estrutura utilizada é:

```text
docs/
├── texto_01.txt
└── texto_02.txt
```

Os arquivos foram mantidos em formato de texto para facilitar sua utilização futura em algoritmos de Processamento de Linguagem Natural.

---

## 2.3 Texto 1

**Título:**

Cardiovascular diseases (CVDs)

**Tema:**

Saúde cardiovascular / doenças cardíacas.

**Fonte original:**

https://drive.google.com/drive/u/1/folders/1t8K5I4XbZiKxsRC1Mn4-JyfOy2jiddd-

**Arquivo no repositório:**

```text
docs/texto_01.txt
```

---

## 2.4 Texto 2

**Título:**

Noncommunicable diseases

**Tema:**

Saúde cardiovascular / doenças cardíacas.

**Fonte original:**

https://drive.google.com/drive/u/1/folders/1t8K5I4XbZiKxsRC1Mn4-JyfOy2jiddd-

**Arquivo no repositório:**

```text
docs/texto_02.txt
```

---

## 2.5 Como os Textos Poderão ser Utilizados em NLP

Os documentos poderão ser utilizados futuramente em diferentes técnicas de **Processamento de Linguagem Natural (NLP)**.

### Extração de sintomas

Algoritmos podem identificar automaticamente sintomas mencionados nos documentos, como:

- Dor no peito;
- Falta de ar;
- Palpitações;
- Fadiga;
- Tontura;
- Desmaios.

Essa aplicação pode contribuir para o desenvolvimento de sistemas automatizados de triagem.

### Reconhecimento de Entidades Médicas

Modelos de NLP podem identificar entidades presentes nos documentos.

Exemplos:

- Doenças;
- Sintomas;
- Medicamentos;
- Procedimentos;
- Exames;
- Tratamentos;
- Fatores de risco.

Essa técnica é conhecida como **Named Entity Recognition (NER)**.

### Classificação de Textos

Algoritmos podem classificar automaticamente os documentos de acordo com seu conteúdo.

Exemplos de categorias:

- Prevenção;
- Diagnóstico;
- Tratamento;
- Sintomas;
- Doenças cardiovasculares;
- Fatores de risco.

### Extração de Tópicos

Técnicas de NLP podem identificar automaticamente os principais assuntos presentes em uma grande quantidade de documentos médicos.

Isso permite organizar grandes bases textuais e descobrir os temas predominantes.

### Busca Inteligente

Os textos também podem ser utilizados para criação de mecanismos de busca capazes de recuperar informações médicas relevantes de acordo com perguntas ou termos utilizados pelo usuário.

---

## 2.6 Importância do NLP para o CardioIA

Grande parte das informações existentes na área da saúde está armazenada de forma não estruturada.

Exemplos incluem:

- Prontuários;
- Relatórios médicos;
- Artigos científicos;
- Descrições de sintomas;
- Documentos de saúde pública;
- Orientações clínicas.

O NLP pode permitir que o CardioIA interprete essas informações e transforme textos em informações estruturadas que possam ser utilizadas por outros sistemas inteligentes.

---

## 2.7 Acesso aos Dados Textuais

Os arquivos `.TXT` estão disponíveis diretamente na pasta:

```text
docs/
```

Também disponibilizamos os documentos através do armazenamento externo:

https://drive.google.com/drive/u/1/folders/1t8K5I4XbZiKxsRC1Mn4-JyfOy2jiddd-

---

# PARTE 3 – DADOS VISUAIS (VISÃO COMPUTACIONAL)

## 3.1 Objetivo

A terceira parte do projeto consiste na organização de um conjunto contendo no mínimo **100 imagens relacionadas a exames cardiológicos**.

Para esta atividade foram selecionadas imagens relacionadas a:

### Eletrocardiograma – ECG

O eletrocardiograma registra a atividade elétrica do coração e pode apresentar diferentes padrões relacionados ao funcionamento cardiovascular.

As imagens poderão ser utilizadas futuramente para experimentos envolvendo **Visão Computacional e Deep Learning**.

---

## 3.2 Quantidade de Imagens

O conjunto visual preparado para esta atividade possui:

**100 ou mais imagens de ECG em formato `.PNG` ou `.JPG`.**

As imagens foram armazenadas externamente devido à quantidade de arquivos.

---

## 3.3 Fonte das Imagens

Foi utilizado como referência o dataset:

### PTB-XL – A Large Publicly Available Electrocardiography Dataset

Disponibilizado pelo **PhysioNet**.

O PTB-XL é uma base pública de eletrocardiogramas clínicos de 12 derivações utilizada em pesquisas envolvendo análise automática de ECG e Inteligência Artificial.

**Fonte oficial:**

https://physionet.org/content/ptb-xl/

**Referência acadêmica:**

Wagner, P. et al.  
*PTB-XL, a large publicly available electrocardiography dataset.*  
Scientific Data.

---

## 3.4 Preparação das Imagens

Os dados do PTB-XL são originalmente disponibilizados como sinais digitais de eletrocardiograma.

Para utilização em tarefas de Visão Computacional, esses sinais podem ser transformados em representações gráficas no formato `.PNG`.

Esse processo pode ser realizado utilizando ferramentas como:

- Python;
- Google Colab;
- NumPy;
- Pandas;
- Matplotlib;
- WFDB.

Cada arquivo de imagem representa visualmente um exame ou sinal de ECG.

---

## 3.5 Organização das Imagens

As imagens podem ser organizadas em uma estrutura semelhante a:

```text
Dados_Visuais_ECG/
│
├── ECG_001.png
├── ECG_002.png
├── ECG_003.png
├── ECG_004.png
├── ECG_005.png
│
└── ...
```

Caso as imagens tenham sido separadas por categorias, também podem ser organizadas da seguinte maneira:

```text
Dados_Visuais_ECG/
│
├── NORM/
│   └── imagens...
│
├── MI/
│   └── imagens...
│
├── STTC/
│   └── imagens...
│
├── CD/
│   └── imagens...
│
└── HYP/
    └── imagens...
```

---

## 3.6 Possíveis Categorias dos ECGs

Dependendo dos exames selecionados do PTB-XL, podem existir categorias como:

| Classe | Significado |
|---|---|
| NORM | ECG normal |
| MI | Infarto do miocárdio |
| STTC | Alterações de ST/T |
| CD | Distúrbios de condução |
| HYP | Hipertrofia |

Essas categorias poderão ser utilizadas futuramente como classes para treinamento e avaliação de modelos de Inteligência Artificial.

---

## 3.7 Aplicações em Visão Computacional

### Classificação de Exames

Modelos de Deep Learning, especialmente Redes Neurais Convolucionais (CNNs), podem ser treinados para identificar padrões visuais associados a diferentes classes de exames.

Um modelo poderia, por exemplo, receber uma imagem de ECG e tentar classificá-la entre diferentes categorias.

### Detecção de Padrões

Algoritmos de Visão Computacional podem identificar padrões presentes nos traçados dos exames.

Isso pode permitir a diferenciação entre exames normais e exames que apresentam determinadas alterações.

### Identificação de Anomalias

Modelos de IA também podem ser utilizados para identificar exames que apresentam características diferentes dos padrões considerados normais.

Essa abordagem pode ser utilizada futuramente como ferramenta auxiliar de triagem.

### Análise das Características do ECG

Técnicas de processamento de imagens podem analisar características como:

- Formato das ondas;
- Picos;
- Segmentos;
- Intervalos;
- Alterações no traçado;
- Padrões visuais.

---

## 3.8 Importância da Visão Computacional para o CardioIA

A Visão Computacional pode permitir que sistemas de Inteligência Artificial processem automaticamente exames médicos representados visualmente.

No contexto do CardioIA, isso pode ser utilizado para:

- Identificação de padrões;
- Classificação de exames;
- Detecção de possíveis anomalias;
- Priorização de exames;
- Apoio à triagem;
- Apoio à decisão clínica.

Essas soluções devem ser utilizadas como ferramentas de apoio e não como substitutas da avaliação realizada por profissionais de saúde.

---

## 3.9 Acesso às 100 Imagens

O conjunto completo de imagens está disponível no link abaixo:

(https://drive.google.com/drive/u/1/folders/1VkqWboStiFfCUDmJ3VSbl0qV9_Rl7ACs)

---

# 4. GOVERNANÇA DE DADOS

Projetos de Inteligência Artificial aplicados à saúde exigem cuidados especiais relacionados à governança dos dados.

Entre os principais aspectos considerados neste projeto estão:

- Origem dos dados;
- Rastreabilidade;
- Qualidade;
- Integridade;
- Padronização;
- Privacidade;
- Segurança;
- Documentação;
- Controle de acesso;
- Uso ético dos dados.

Sempre que possível, foram priorizados dados públicos, anonimizados ou simulados.

O projeto não pretende utilizar informações pessoais identificáveis de pacientes.

---

# 5. PRIVACIDADE E LGPD

Dados relacionados à saúde são considerados dados pessoais sensíveis pela Lei Geral de Proteção de Dados Pessoais (LGPD).

Em uma aplicação real, o tratamento dessas informações exige cuidados relacionados a:

- Finalidade;
- Necessidade;
- Segurança;
- Privacidade;
- Anonimização;
- Minimização de dados;
- Controle de acesso;
- Transparência.

No contexto desta atividade acadêmica, são priorizados dados públicos, anonimizados ou simulados que não permitam identificar pacientes.

---

# 6. VIÉS NOS DADOS

Bases utilizadas para treinamento de modelos de Inteligência Artificial podem apresentar vieses.

Na área da saúde, isso é particularmente importante porque diferentes populações podem estar representadas de maneira desigual.

Possíveis fontes de viés incluem:

- Idade;
- Sexo;
- Origem geográfica;
- Condições socioeconômicas;
- Distribuição das doenças;
- Características da população;
- Quantidade de registros por classe.

Por exemplo, um modelo treinado predominantemente com dados de pacientes de determinada faixa etária pode apresentar desempenho diferente quando utilizado em outras populações.

Antes do treinamento dos futuros modelos do CardioIA, será importante analisar a representatividade das bases e o balanceamento das diferentes categorias.

---

# 7. QUALIDADE DOS DADOS

Antes da utilização das bases em modelos de Inteligência Artificial, será necessário verificar:

- Valores ausentes;
- Dados duplicados;
- Valores inconsistentes;
- Outliers;
- Formatos incorretos;
- Padronização;
- Integridade dos arquivos;
- Distribuição das classes;
- Balanceamento dos dados.

A qualidade dos dados influencia diretamente a qualidade dos modelos desenvolvidos posteriormente.

---

# 8. INTEGRAÇÃO MULTIMODAL DO CARDIOIA

Um dos aspectos mais importantes desta primeira fase é a utilização de diferentes modalidades de dados.

O projeto trabalha com:

### Dados estruturados

Informações clínicas e numéricas dos pacientes.

### Dados não estruturados em texto

Documentos relacionados à saúde cardiovascular.

### Dados visuais

Imagens relacionadas a exames cardiológicos.

No futuro, essas diferentes fontes poderão ser integradas em uma solução multimodal de Inteligência Artificial.

Por exemplo, um sistema poderia considerar simultaneamente:

- Idade;
- Pressão arterial;
- Colesterol;
- Sintomas descritos em texto;
- Histórico clínico;
- Imagem de ECG.

A integração dessas informações pode permitir o desenvolvimento de sistemas mais completos de apoio à análise cardiovascular.

---

# 9. TECNOLOGIAS UTILIZADAS

As seguintes tecnologias podem ser utilizadas durante a preparação e análise dos dados:

- Python;
- Google Colab;
- Pandas;
- NumPy;
- Matplotlib;
- WFDB;
- Microsoft Excel;
- Git;
- GitHub;
- Google Drive / OneDrive.

---

# 10. ESTRUTURA DO REPOSITÓRIO

A estrutura do repositório foi organizada da seguinte maneira:

```text
CardioIA-Fase1/
│
├── README.md
│
├── data/
│   └── cardioia_dados_numericos_iot.xlsx
│
├── docs/
│   ├── texto_01.txt
│   └── texto_02.txt
│
└── scripts/
    └── gerar_imagens_ecg.ipynb
```

### README.md

Documento principal contendo a descrição completa do projeto, metodologia, fontes e links para os dados.

### data/

Contém o arquivo `.CSV` ou `.XLSX` com os dados numéricos.

### docs/

Contém os dois ou mais documentos `.TXT` utilizados na etapa de NLP.

### scripts/

Pode conter notebooks ou códigos utilizados para preparar os dados e gerar as imagens dos ECGs.

### Imagens

Devido à quantidade de arquivos, as imagens completas podem ser armazenadas no Google Drive ou OneDrive, mantendo o link público neste README.

---

# 11. LINKS PARA TODOS OS ENTREGÁVEIS

## Dados Numéricos – IoT

https://drive.google.com/drive/u/1/folders/1d3g1aWClhOTMOwJblMnkSMSHsVCe2HXx

Formato: `.CSV` ou `.XLSX`

Quantidade: mínimo de 100 registros.

---

## Dados Textuais – NLP

(https://drive.google.com/drive/u/1/folders/1t8K5I4XbZiKxsRC1Mn4-JyfOy2jiddd-)

Os arquivos `.TXT` também estão disponíveis na pasta `docs` deste repositório.

---

## Dados Visuais – ECG

https://drive.google.com/drive/u/1/folders/1VkqWboStiFfCUDmJ3VSbl0qV9_Rl7ACs

Quantidade: mínimo de 100 imagens.

Formato: `.PNG` ou `.JPG`.

---

# 12. FONTES E REFERÊNCIAS

## Dados Numéricos

**Fonte:**

https://www.physionet.org/content/ptb-xl/1.0.3/?utm_source=chatgpt.com

---

## Dados Textuais

### Texto 1

**Título:**  
Cardiovascular diseases (CVDs)

**Fonte:**  
https://www.who.int/news-room/fact-sheets/detail/cardiovascular-diseases-%28cvds%29

### Texto 2

**Título:**  
Noncommunicable diseases

**Fonte:**  
https://www.who.int/news-room/fact-sheets/detail/noncommunicable-diseases

---

## Dados Visuais

**PTB-XL – A Large Publicly Available Electrocardiography Dataset**

Wagner, P. et al.

*PTB-XL, a large publicly available electrocardiography dataset.*

Scientific Data.

PhysioNet:

https://physionet.org/content/ptb-xl/

---

# 13. PRÓXIMAS ETAPAS

A base construída nesta primeira fase poderá ser utilizada nas próximas etapas do CardioIA para:

- Análise exploratória;
- Tratamento dos dados;
- Machine Learning;
- Classificação de risco cardiovascular;
- NLP;
- Extração de sintomas;
- Visão Computacional;
- Deep Learning;
- Classificação de ECGs;
- Detecção de anomalias;
- Sistemas de apoio à decisão;
- Agentes inteligentes.

---

# 14. CONCLUSÃO

A **Fase 1 – Batimentos de Dados** do projeto CardioIA teve como objetivo construir uma base inicial de dados para futuras aplicações de Inteligência Artificial voltadas à cardiologia.

Foram trabalhadas três modalidades:

1. **Dados Numéricos**, contendo informações relacionadas a pacientes e fatores cardiovasculares;
2. **Dados Textuais**, contendo informações relacionadas a doenças, sintomas, prevenção e tratamentos;
3. **Dados Visuais**, contendo imagens de exames de ECG.

Além da coleta e organização, foram considerados aspectos relacionados à governança, privacidade, qualidade, ética e possíveis vieses existentes nos dados.

A combinação dessas três modalidades estabelece uma base para o desenvolvimento futuro de uma solução multimodal de Inteligência Artificial voltada à saúde cardiovascular.

---

# 15. INTEGRANTES

- Filipe Augusto Lima Silva 
- Laísa Cristina Capodifoglio Andrade
- Johnathan da Cruz Gatti
- Diogo Ferreira Pereira
- André Victor Gonçalves Toledo

---

**FIAP – Inteligência Artificial**

**CardioIA – Fase 1: Batimentos de Dados**



---

# ☁️ IA em Nuvem — Tradução & Reconhecimento de Imagens

### 🔹 Google Colab • APIs Gratuitas • Wikimedia API • Modelos de IA em Nuvem

**Aluno:** Diego Roberto Aragan Aoki
**Curso:** Tecnólogo em Análise e Desenvolvimento de Sistemas – 5º Semestre
**Instituição:** Anhanguera – Unidade Ouro Verde (Campinas-SP)

---

## 📘 Descrição Geral do Projeto

Este repositório reúne as atividades práticas da disciplina **Computação em Nuvem**, realizadas no **Google Colab** utilizando:

* ✅ Tradução automática (notebook: **Atividade_IA_em_Nuvem**)
* ✅ Reconhecimento de imagens (notebook: **Reconhecimento_de_imagem**)
* ✅ Consumo de APIs gratuitas em nuvem
* ✅ Geração de relatório técnico com prints dos testes

O projeto demonstra o uso de inteligência artificial via serviços remotos, reforçando conceitos de arquitetura em nuvem, escalabilidade e integração com APIs.

---

# 🧩 Parte 1 — Tradução Automática

### 🔎 Notebook: `Atividade_IA_em_Nuvem.ipynb`

### ✅ Funcionalidades Implementadas

* Função `traduzir(texto, origem, destino)`
* Tradução entre diversos idiomas
* Testes com diferentes frases e idiomas
* Manipulação de exceções e impressão dos resultados

### ✅ Testes Realizados

Foram testados vários cenários:

#### 🔤 **Testes de tradução**

* Português → Inglês
* Português → Espanhol
* Português → Japonês
* Inglês → Português
* Frases longas e frases curtas
* Textos técnicos e textos comuns

#### ✅ Resultados Positivos

* As traduções ocorreram rapidamente e com boa coerência
* O modelo interpretou bem frases contextuais
* A ferramenta funcionou sem necessidade de configurar hardware local
* O Colab permitiu alterar o código e repetir testes de forma muito ágil

### ⚠️ Dificuldades Enfrentadas

* Algumas traduções apresentaram pequenas variações semânticas
* Palavras com múltiplos sentidos poderiam ser traduzidas de forma ambígua
* Idiomas não-latinos (como japonês) podem perder nuances de contexto

---

# 🧩 Parte 2 — Reconhecimento de Imagem

### 🔎 Notebook: `Reconhecimento_de_imagem.ipynb`

### ✅ Funcionalidades Implementadas

* Integração com a **Wikimedia API** para buscar imagens automaticamente
* Testes com URLs diretas de imagens
* Reconhecimento por modelo de IA em nuvem
* Exibição dos rótulos preditos e tratamento de erros

### ✅ Testes Realizados

#### 🔍 **Testes com URLs de imagens**

* URL de um cão (Pug)
* URL de um gato
* URL de uma baleia
* Testes com URLs inexistentes
* Testes com imagens de baixa resolução

#### ✅ Resultados Positivos

* O modelo classificou corretamente a maioria das imagens
* O uso da Wikimedia API facilitou encontrar imagens públicas
* O notebook exibe mensagens claras quando a imagem não é encontrada
* O tempo de resposta da IA hospedada na nuvem foi muito rápido

### ⚠️ Dificuldades Enfrentadas

* Algumas imagens complexas geram classificações genéricas
* URLs inválidas ou imagens bloqueadas exigiram tratamento de exceções
* Dependência total da conexão para baixar e processar imagens

---

# ✅ Conclusão Geral da Atividade

A aula proporcionou uma visão prática e acessível sobre como **IA na nuvem pode ser usada sem qualquer infraestrutura local**.
Os resultados foram extremamente positivos:

* ✅ As APIs funcionaram de forma estável e rápida
* ✅ Os modelos de IA demonstraram boa precisão
* ✅ O Google Colab simplificou toda a execução
* ✅ Foi possível testar, alterar e validar códigos em tempo real
* ✅ A atividade reflete aplicações reais usadas em empresas e projetos profissionais

A experiência reforçou o papel da nuvem como ferramenta essencial no desenvolvimento moderno de soluções inteligentes.

---

# 📁 Estrutura do Repositório

```
/
├── notebooks/
│   ├── Atividade_IA_em_Nuvem.ipynb
│   └── Reconhecimento_de_imagem.ipynb
├── relatorio/
│   └── Relatorio_IA_em_Nuvem.pdf
└── README.md
```

---

# 👨‍💻 Autor

**Diego Roberto Aragan Aoki**
📚 Tecnólogo em Análise e Desenvolvimento de Sistemas
🏫 Anhanguera — Unidade Ouro Verde
🌐 GitHub: [https://github.com/diego87aoki](https://github.com/diego87aoki)

---



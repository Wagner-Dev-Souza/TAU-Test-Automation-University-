# Test Automation University — Estudos e Certificações

> Material de estudo e certificados das trilhas concluídas na **Test Automation University**, cobrindo três pilares da automação de testes em Java: testes unitários, testes de API e framework de organização de testes.

## 🎯 Objetivo

Consolidar, em código executável, o conteúdo das certificações — em vez de guardar apenas os certificados. Cada trilha tem sua pasta com o projeto Maven correspondente e o comprovante de conclusão.

## 📂 Estrutura

```
Junit5/
├── certificates_TAU-*.png            # certificado da trilha
└── junit5-tutorial/                  # projeto Maven (src/test/java/junit5tests)
Rest Assured/
├── certificates_TAU-*.png
└── tau-rest-assured/                 # projeto Maven com testes de API
TestNG/
├── certificates_TAU-*.png
└── Test-Automation-University/       # material do curso (capítulos em PDF/PPTX) + código
```

## 📚 O que cada trilha cobre

### JUnit 5 — 13 classes de teste

- Asserções e suposições (**assumptions**), incluindo a diferença prática entre as duas
- Testes habilitados/desabilitados e testes anotados com **tags**
- Ordenação de execução de testes e classes de teste
- **Testes parametrizados** com fonte de dados em **CSV**
- **Testes repetidos** e classes internas (*nested tests*)
- Anotações customizadas e **listeners** de ciclo de vida

### Rest Assured — 8 classes de teste

- Testes de API REST em Java
- Modelagem de payload com classes de entidade (`Place`, `Location`) em vez de JSON solto
- Validação de resposta, status e corpo

### TestNG — 26 classes + material do curso

- Estrutura de framework de teste, anotações e ciclo de execução
- Material teórico preservado em PDF e apresentações (14 documentos)

## ▶️ Como executar

Cada trilha é um projeto Maven independente:

```bash
cd Junit5/junit5-tutorial        && mvn test
cd "Rest Assured/tau-rest-assured" && mvn test
```

## 📌 Status

Repositório de estudo e certificação, sem continuidade de desenvolvimento. Os testes são exercícios dirigidos pelo curso — servem como demonstração de domínio das ferramentas, não como suíte de um produto.

Os arquivos de certificado estão versionados de propósito: são a evidência das trilhas concluídas.

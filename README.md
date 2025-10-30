# Desafio Técnico - Beedoo QA Challenge

### 1. Descrição do Desafio

Este projeto documenta a análise de qualidade realizada no módulo de cursos da aplicação "Beedoo QA Challenge", como parte do processo seletivo. O objetivo foi conduzir testes exploratórios, identificar e documentar bugs, e propor melhorias de produto.

**URL da Aplicação Testada:** https://creative-sherbet-a51eac.netlify.app/

---

### 2. Documentação e Artefatos Gerados

Abaixo estão os links para os documentos criados durante a análise:

* **📄 Relatório Completo de Qualidade e Análise de Bugs:**
    ### [Relatório Completo com melhorias e Report de Bugs](https://docs.google.com/document/d/1IZOVg9KiqXUKiz-wOOvD-ruZp7KpmOzxsXoPiQGiVZk/edit?usp=sharing)

* **📊 Planilha de Plano de Testes (Google Sheets):**
    ### [Planilha de Casos de Teste](https://docs.google.com/spreadsheets/d/1-y0y2DpZC1cM2BDvcCqVOwhPf7-XSxQ4/edit?usp=sharing&ouid=108642266182806597024&rtpof=true&sd=true)
                                     
* **🎥 Evidências em Vídeo (Google Drive):**
    ### [Pasta Com os Vídeos de Evidência em Formato MP4](https://drive.google.com/drive/folders/13VXBuED4uHkvfkTilt3_Y5DFw3qdGKUs?usp=sharing)
                                                          
---

### 3. Resumo da Análise

Durante os testes exploratórios no módulo de cursos, foram observadas as seguintes características:

* **Segurança:** O sistema não possui autenticação, permitindo que qualquer visitante crie e exclua cursos.
* **Fluxo Principal:** A aplicação se concentra em um CRUD (Criar, Ler, Excluir) de cursos, porém as funcionalidades de **Excluir** e **Editar** (inexistente) estão quebradas ou ausentes.
* **Validações:** Foram identificadas falhas críticas na validação de dados em todos os campos do formulário de cadastro.
* **Usabilidade:** A interface, embora simples, apresenta quebras de layout e não possui funcionalidades essenciais como busca, filtro ou ordenação.

---

### 4. User Stories

**US-01: Cadastrar um Novo Curso**
* **Como um** Gerente de Cursos,
* **Eu quero** cadastrar um novo curso com todos os seus detalhes,
* **Para que** eu possa expandir o catálogo de ofertas da plataforma.

**US-02: Visualizar a Lista de Cursos**
* **Como um** Gerente de Cursos,
* **Eu quero** ver uma lista de todos os cursos cadastrados,
* **Para que** eu possa ter uma visão geral rápida de todas as ofertas ativas.

**US-03: Excluir um Curso**
* **Como um** Gerente de Cursos,
* **Eu quero** remover um curso que não será mais oferecido,
* **Para que** eu possa manter a lista de cursos limpa e relevante.

**US-04: Editar as Informações de um Curso**
* **Como um** Gerente de Cursos,
* **Eu quero** editar as informações de um curso já cadastrado,
* **Para que** eu possa corrigir erros ou manter os detalhes (como datas e vagas) sempre atualizados.

---

### 5. Sugestões de Melhoria

| Área | Melhoria Proposta | Benefício |
| :--- | :--- | :--- |
|  **Segurança** | Implementar login e perfis (Admin / Aluno) | Garante controle de acesso e integridade dos dados. |
|  **Funcionalidade** | Adicionar a funcionalidade de **Editar Curso** | Completa o fluxo CRUD essencial e melhora a usabilidade. |
|  **Aluno** | Criar uma área pessoal ("Meus Cursos", "Lista de Desejos") | Personaliza a experiência do aluno e aumenta o engajamento. |
|  **Usabilidade** | Adicionar busca, filtros e ordenação alfabética | Facilita a localização de cursos em uma lista crescente. |

---

### 6. Ferramentas Utilizadas

* **Gherkin / Google Sheets:** Para criação e documentação dos casos de teste.
* **Google Docs:** Para a elaboração do relatório final de qualidade.
* **Google Drive:** Para armazenamento centralizado das evidências em vídeo.
* **Markdown:** Para a documentação deste `README.md`.
* **GitHub:** Para versionamento e publicação do projeto.

---

## 7. Estrutura do Repositório

Para manter a clareza e organização, os artefatos gerados durante o desafio estão estruturados da seguinte forma dentro deste repositório:
```
/
├── DOCs/
│   ├── Casos de Testes - Beedoo QA Chalenge.xlsx
│   └── RELATÓRIO– PROJETO BEEDOO QA CHALLENGE.pdf
└── README.md
```
- **DOCs/**: Pasta contendo todos os documentos detalhados, como o relatório de análise e a planilha de testes.  
- **README.md**: Arquivo principal do repositório.

**Autor:** João Silva  
**Data:** 30/10/2025  
**Contexto:** Beedoo - QA Chalenge
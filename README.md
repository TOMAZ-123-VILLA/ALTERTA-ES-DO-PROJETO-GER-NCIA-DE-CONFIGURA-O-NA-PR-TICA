# ALTERTA-ES-DO-PROJETO-GER-NCIA-DE-CONFIGURA-O-NA-PR-TICA
AS 3 ALTERAÇÕES REALIZADAS NO PROJETO, COM OS RESPETIVOS FICHEIROS AFETADOS, MENSAGENS DE COMMIT E DESCRIÇÕES DETALHADAS:

Plaintext
SISTEMA-CONTROLE-ALUNOS
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── especificacao-requisitos.md
├── node_modules/
├── src/
│   ├── config/
│   │   └── database.js
│   ├── controllers/
│   │   ├── AlunoController.js
│   │   ├── HistoricoController.js
│   │   ├── MatriculaController.js
│   │   └── NotaController.js
│   ├── models/
│   │   ├── Aluno.js
│   │   ├── Disciplina.js
│   │   └── Turma.js
│   ├── routes/
│   │   └── api.js
│   ├── utils/
│   │   └── pdfGenerator.js
│   └── server.js
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```[cite: 6]

---

#### **2. Detalhamento das 3 Alterações Incrementais Inseridas**

##### **1ª Alteração: Cadastro de Alunos e Validação de CPF**
* **Arquivos Modificados/Adicionados:**
  * `src/models/Aluno.js`[cite: 1, 2, 6]
  * `src/controllers/AlunoController.js`[cite: 1, 2, 6]
* **Comando Executado:**
  ```bash
  git add src/models/Aluno.js src/controllers/AlunoController.js
  git commit -m "feat: adiciona cadastro de alunos e validacao de CPF"

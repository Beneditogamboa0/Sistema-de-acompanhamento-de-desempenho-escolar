# "Mi-School" - Sistema de acompanhamento de desempenho escolar

Mi-School é um sistema web desenvolvido para facilitar o acompanhamento académico dos alunos de uma instituição de ensino.

O sistema centraliza informações essenciais como notas, presenças, faltas, avaliações de comportamento e dificuldades individuais, permitindo uma visão completa e eficiente sobre cada estudante.

✏️ Funcionalidades Principais

🔑 1. Acesso ao Sistema

☑️ Login.
☑️ Registo (signup);
☑️ Perfis com permissões diferentes (Admin, Professor e Aluno).

🧑‍🦰 2. Perfis e Funcionalidades

2.1. Administrador

☑️ Cadastro de alunos;
☑️ Listagem geral de alunos;
☑️ Acesso às informações académicas e comportamentais;
☑️ Contato com encarregados em caso de irregularidades;
☑️ Cálculo de médias e estatísticas filtradas por curso, classe e turma.

2.2. Professor

☑️ Acesso aos alunos das suas disciplinas;
☑️ Visualização de notas, faltas, turmas e classes;
☑️ Contato direto com encarregados em caso de inquietações;
☑️ Registo e acompanhamento do comportamento do aluno.

2.3. Aluno

☑️ Visualização das próprias notas, faltas e avaliações;
☑️ Indicação das disciplinas com maior e menor dificuldades;
☑️ Criação de um plano de estudo personalizado (mini to-do list).

3. 💻 Tecnologias Utilizadas

☑️ PHP;
☑️ MySQL;
☑️ JavaScript;
☑️ HTML/CSS;
☑️ Arquitetura MVC.

4. 🔏 Regras de negócio

4.1. 🗝️ Acesso ao sistema
  a.	Signup
    •	Usuários devem definir email, senha e nickname;
    •	Os emails devem ser únicos;
    •	Um usuário não pode possuir mais de um perfil;
    •	As senhas devem conter entre 8 e 20 caracteres;
    •	O nick do usuário informado deve ser único.
  b.	Login
    •	As credenciais do usuário devem coincidir;
    •	O usuário tem a opção de definir a senha caso se tenha esquecido.
4.2.	Permissões, funcionamento e uso do sistema
  a.	Admin
    •	Tem acesso ao desempenho individual e geral dos alunos;
    •	Poder entrar em contacto com os encarregados dos alunos caso haja necessidade;
    •	Cadastrar alunos a um curso, classe e turma.
  b.	Professor
    •	Visualizar as notas, faltas e presenças dos seus alunos;
    •	Visualizar informações apenas dos alunos que leciona;
    •	Publicar notas apenas dos alunos que leciona e na respectiva disciplina lecionada;
    •	As notas publicadas podem ser alteradas apenas com permissão da instituição;
    •	Observações comportamentais devem ser enviadas ao admin.
  c.	Aluno
    •	Poder visualizar as suas notas de cada disciplina, presença, faltas e, caso existam, observações comportamentais, com permissão do admin;
    •	O cálculo das médias de cada disciplina, assim como a média geral, é feito automaticamente;
    •	Poder informar as disciplinas em que apresenta maior dificuldade;
    •	Ter acesso a uma lista de tarefas pessoal, com limite de registro de 20 atividades.


```
MIT License

Copyright (c) 2025 Benedito Kapolo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

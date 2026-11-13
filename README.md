# 🧪 Pyro Tools QA

**Testes manuais do [Pyro Tools](https://github.com/Alswes/pyro-tools), um sistema web de acompanhamento de compras.**

Este repositório documenta como eu testo o Pyro Tools: os defeitos que encontro, as evidências e, em breve, os casos de teste. É o meu caderno de prática em Análise de Testes (QA), feito sobre um sistema que eu mesmo criei e que está em uso real.

> Sou estudante de Análise e Desenvolvimento de Sistemas e estou começando em QA. O que está aqui é o que eu já fiz de verdade, não uma lista do que pretendo saber.

---

## 🎯 O que é testado

| Item | Detalhe |
| --- | --- |
| Sistema | Pyro Tools v0.16.1 |
| Ambiente | Demonstração, com dados fictícios: [pyro-tools-demo.web.app](https://pyro-tools-demo.web.app) |
| Tipo de teste | Manual, exploratório e por casos de teste |
| Gestão dos defeitos | Jira (quadro Kanban: To Do → In Testing → Bug Open → In Fix → Retest → Done) |

O quadro do Jira é privado, então cada defeito é copiado para cá em um arquivo próprio.

---

## 🐞 Defeitos registrados

| ID | Título | Severidade | Status |
| --- | --- | --- | --- |
| [PYRO-1](bug-reports/PYRO-1.md) | Entregas e Coletas: nome do item quebra letra por letra em telas de 901px a 1344px de largura | Medium | Aberto |

O modelo que uso para registrar um defeito está em [bug-reports/MODELO.md](bug-reports/MODELO.md).

---

## 📁 Estrutura

```
/
├── bug-reports/     # um arquivo por defeito, no mesmo formato do card do Jira
├── evidence/        # prints de cada defeito, em uma pasta por ID
└── README.md
```

---

## 🗺️ Próximos passos

- [ ] Casos de teste da tela Entregas e Coletas (caminho feliz, negativos e limites)
- [ ] Análise do PYRO-1: falha, defeito, erro e causa-raiz
- [ ] Correção do PYRO-1 na próxima versão, reteste e fechamento
- [ ] Cenários e casos de teste gerados com IA (Claude), comparados com os meus
- [ ] Plano de teste

---

## 📚 Base de estudo

Estudo os fundamentos pelo Syllabus CTFL (ISTQB/BSTQB) e aplico cada tópico no Pyro Tools.

---

Desenvolvido por **Wesley Lemos** · [LinkedIn](https://linkedin.com/in/wesley-lemos-profissional) · [GitHub](https://github.com/Alswes)

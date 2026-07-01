# LeadFlow

`Análise e Desenvolvimento de Sistemas - PUC Minas`

`Desenvolvimento de aplicação web front-end`

`1º semestre/2026`

CRM para pequenos e micro negócios, criado para centralizar contatos, funil de vendas e follow-up em um único lugar.

## Evolução do projeto

### v1.0 — Projeto acadêmico (este repositório)

Desenvolvido durante o 1º semestre do curso de Análise e Desenvolvimento de Sistemas (PUC Minas), como projeto em dupla com Hylbert Honorato.

* Stack: JavaScript, HTML5, CSS3 (vanilla, sem frameworks)
* Escopo: cadastro e gestão de leads, funil de vendas, responsividade mobile
* Documentação completa: contexto do problema, especificação de requisitos, metodologia e projeto de interface — disponíveis na pasta /documentos
* Deploy: GitHub Pages
* Objetivo: estudo acadêmico de conceitos de desenvolvimento de software e validar lógica de negócio e fluxo de produto com ferramentas simples, antes de escalar a arquitetura

### v2.0 — Reconstrução fullstack (em desenvolvimento)

Após validar o conceito na v1.0, o projeto está sendo reconstruído do zero com uma stack fullstack moderna, já que o código acadêmico não comporta os requisitos de um SaaS real (multi-tenancy, autenticação segura, pagamentos recorrentes).

* Stack: Next.js 14, TypeScript, Tailwind CSS, Supabase, Stripe, Evolution API (WhatsApp), Vercel
* Escopo: workspaces multi-usuário, automação de WhatsApp, assinaturas via Stripe, autenticação e autorização
* Repositório: (futuramente será disponibilizado)

### Por que reconstruir em vez de evoluir o código v1.0?

A base v1.0 foi construída sem framework, sem tipagem e sem separação clara entre front-end e back-end — suficiente para provar o conceito acadêmico, mas não para sustentar autenticação real, cobrança recorrente ou múltiplos usuários simultâneos. A v2.0 parte de uma arquitetura pensada desde o início para esses requisitos.

## Funcionalidades (v1.0)
* Cadastro e edição de leads
* Visualização de funil de vendas
* Interface responsiva

## Como rodar localmente

```
git clone https://github.com/LucasMartinToth/LeadFlow.git
cd LeadFlow
# abrir index.html no navegador ou usar um servidor local (ex: Live Server)
```

## Autores

* Lucas Martin Toth
* Hylbert Honorato

## Orientadora

* Viviâne de Almeida Tôrres

# Documentação

Toda a documentação de processo (contexto, especificação, metodologia e projeto de interface) está disponível na pasta /documentos deste repositório.

<ol>
<li><a href="documentos/01-Documentação de Contexto.md"> Documentação de Contexto</a></li>
<li><a href="documentos/02-Especificação do Projeto.md"> Especificação do Projeto</a></li>
<li><a href="documentos/03-Metodologia.md"> Metodologia</a></li>
<li><a href="documentos/04-Projeto de Interface.md"> Projeto de Interface</a></li>
<li><a href="documentos/05-Template padrão do Site.md"> Template padrão do Site</a></li>
<li><a href="documentos/06-Programação de Funcionalidades.md"> Programação de Funcionalidades</a></li>
<li><a href="documentos/07-Referências Bibliográficas.md"> Referências Bibliográficas</a></li>
</ol>

# Hospedagem

A aplicação em HTML/CSS/JS é um projeto que pode ser utilizado tanto em servidores como em navegadores web. Clique <a href="https://lucasmartintoth.github.io/LeadFlow/codigo-fonte/pages/index.html">aqui</a> para acessá-lo.

# Apresentação

* <a href="apresentacao/README.md"> Apresentação da solução</a></li>

# Licença
* <a href ="./LICENSE"> MIT License </a>

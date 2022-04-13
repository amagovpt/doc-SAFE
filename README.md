# Documentação técnica relativa ao Serviço de Assinatura de Faturas Eletrónicas (SAFE)


## Introdução

O Serviço de Assinatura de Faturas Eletrónicas (SAFE) permite que o administrador, gerente, diretor ou procurador de uma empresa possa assinar faturas eletrónicas em _softwares_ de faturação integrados com o SAFE.

A assinatura digital através do SAFE é certificada pelo Estado Português.

O Serviço de Assinatura de Faturas Eletrónicas (SAFE) vem dar resposta e cumpre os requisitos impostos pelo [DL 28/2019 de 15 de fevereiro](https://dre.pt/home/-/dre/119622094/details/maximized)  e  [Regulamento UE n.º 910/2014 do Parlamento Europeu e do Conselho, de 23 de julho de 2014](https://eur-lex.europa.eu/legal-content/PT/TXT/PDF/?uri=CELEX:32014R0910&from=ga).

Este repositório contêm a documentação técnica relativamente ao Serviço de Assinatura de Faturas Eletrónicas (SAFE).

## Estrutura da documentação

* Na pasta **api** encontram-se as especificações das API em formato OpenAPI.
	* **SAFE-AccountManagementService.json** - especificação da API de gestão de conta SAFE.
	* **SAFE-SignatureService.json** - especificação da API de assinatura SAFE.
* Na pasta **guidelines** disponibiliza-se um documento que elenca as guidelines de integração necessárias para certificação da aplicação.
* [Manual de integração (download pdf)](https://amagovpt.github.io/doc-SAFE/AMA&#32;-&#32;SAFE&#32;Documento&#32;de&#32;integração.pdf)
*  [Guia de fluxos complementares (download pdf)](https://amagovpt.github.io/doc-SAFE/AMA&#32;-&#32;SAFE&#32;Guia&#32;de&#32;Fluxos&#32;Complementares.pdf)

## Certificação
Para a certificação deverão ser fornecidas as seguintes evidências:
* Relatório assinado digitalmente (com LTV) com evidências de cumprimento das guidelines de integração.
* Vídeo demonstrativo da solução.
* Providenciar 5 exemplares de documentos assinados, em ambiente pré-produtivo.

Após a receção das evidências a Agência para a Modernização Administrativa (AMA IP)  precederá à avaliação.
No processo de avaliação está previsto: 
 - Possibilidade de requisição de acesso ao sistema, para validação das evidências e esclarecimento de dúvidas.
 - Possibilidade de solicitar:
	 -  Novo relatório corrigido.
	 - Evidências adicionais ou substituição das fornecidas.

**NOTA:** A configuração em ambiente produtivo é precedida da formalização de protocolo e de certificação.
## Outros recursos
Para a integração com OAuth (funcionalidade opcional, mas recomendável) a documentação técnica está disponível em https://github.com/amagovpt/doc-AUTENTICACAO
## Contactos
Para questões, sugestões ou comentários envie um e-mail para eid@ama.pt.
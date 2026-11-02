# AWS Lab 01 — Site estático no S3

Laboratório 1 da minha trilha de estudos para a **AWS Certified Cloud Practitioner (CLF-C02)**.

## Objetivo

Hospedar uma página pessoal simples em um bucket Amazon S3 e compreender o funcionamento de buckets, objetos, hospedagem estática e políticas de acesso.

## Arquitetura

![Arquitetura AWS S3](prints/arquitetura.png)

## O que eu fiz

- [x] Criei o arquivo `index.html` no computador.
- [x] Criei o bucket S3.
- [x] Enviei o arquivo `index.html`.
- [x] Ativei a hospedagem de site estático.
- [x] Configurei o acesso público somente para leitura.
- [x] Testei o acesso ao site pelo navegador.
- [x] Documentei o laboratório.

## Prints

### Site bloqueando acesso para público
![Bucket S3](prints/bucket-s3.png)

### Site funcionando para público
![Site funcionando](prints/site-funcionando.png)

## O que aprendi

- A diferença entre buckets e objetos no Amazon S3.
- Como hospedar conteúdo estático utilizando o Amazon S3.
- Como configurar permissões de leitura pública.
- Como funciona o acesso a um site estático hospedado na AWS.

## Domínio da prova

Tecnologia — Armazenamento (Amazon S3).

## Limpeza — prevenção de custos

- Excluí os objetos do bucket.
- Excluí o bucket S3.
- Revisei as configurações de acesso público da conta AWS.

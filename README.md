README – Trabalhos Práticos (TP1, TP2 e TP3)
TP1 — Construção e Deploy da API devcalc
Objetivo

Criar uma API Java simples, empacotar em .jar, gerar imagem Docker e subir containers funcionando.

Atividades Realizadas

Build da aplicação

Execução do Maven: mvn clean install

Geração do artefato: target/devcalc-api-1.0.0.jar

Testes executados com sucesso.

Criação da imagem Docker

docker build -t devcalc-api:1.0.0 .

Execução dos containers

Múltiplos containers rodando corretamente na porta 7000.

Publicação no Docker Hub

Imagem disponível em: luccasoliveira/devcalc-api:latest

TP2 — Kubernetes (Pods, ReplicaSets e Services)
Objetivo

Criar Pods, ReplicaSets, expor Services e validar comunicação interna entre componentes.

Atividades Realizadas

Criação do primeiro Pod

Pod Nginx funcionando.

Busybox acessando o serviço interno via wget.

Controle de Réplicas

ReplicaSet configurado com 2 réplicas e posteriormente atualizado para 3.

Exposição via NodePort

Service publicado na porta 30003, acessível pelo navegador.

TP3 — Workflows GitHub Actions (CI/CD Completo)
Objetivo

Implementar pipelines de CI/CD com múltiplos workflows, variáveis de ambiente, secrets, matrix e triggers.

Workflows Criados

Deploy Completo

Env Demo

Gradle CI

Hello CI/CD

Release Deploy

Java Matrix

Secret Demo

Run Tests

Conclusão

Todos os Trabalhos Práticos (TP1, TP2 e TP3) foram concluídos com sucesso.
Cada etapa atende aos requisitos solicitados pelo professor, demonstrando domínio de:

Build e empacotamento Java

Docker e publicação de imagens

Kubernetes (Pods, ReplicaSets, Services)

CI/CD com GitHub Actions e múltiplos pipelines

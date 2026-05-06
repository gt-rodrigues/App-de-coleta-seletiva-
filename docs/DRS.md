# Documento de Requisitos de Software (DRS)

## 1. Introdução

### 1.1 Visao Geral

Este documento descreve os requisitos para o desenvolvimento de um sistema voltado à coleta seletiva de resíduos eletrônicos (e-lixo), como computadores, celulares, baterias e eletrodomésticos.

O sistema permitirá que usuários solicitem coletas, acompanhem o descarte correto e promovam a sustentabilidade ambiental.

Considera-se que a empresa é pioneira na região, inspirando-se em práticas adotadas por organizações como Green Eletron e Reciclus.

### 1.2 Objetivos do Sistema

Facilitar o descarte correto de resíduos eletrônicos.

Organizar e gerenciar solicitações de coleta.

Promover conscientização ambiental.

Garantir rastreabilidade dos materiais coletados.

Otimizar rotas de coleta para reduzir custos e impacto ambiental.

### 1.3 Público Alvo

População em geral (usuários residenciais).

Empresas que descartam equipamentos eletrônicos.

Órgãos públicos.

Equipe interna (motoristas, administradores, operadores).

---

## 2. Escopo do Sistema

### 2.1 Escopo Incluído

Cadastro e autenticação de usuários (pessoas físicas e empresas).

Solicitação de coleta de resíduos eletrônicos.

Agendamento de data, horário e local para coleta.

Acompanhamento do status da coleta (pendente, em rota, concluída).

Cadastro e gerenciamento de tipos de resíduos eletrônicos.

Sistema de rotas para otimização das coletas.

Painel administrativo para gerenciamento de solicitações.

Notificações para usuários sobre status da coleta.

Histórico de coletas realizadas.

Visualização de pontos de coleta próximos.

---

## 3. Requisitos Funcionais


### RF00 – O sistema deve permitir o cadastro de usuários.

### RF01 – O sistema deve permitir login e autenticação.

### RF02 – O usuário deve poder solicitar coleta de resíduos eletrônicos.

### RF03 – O usuário deve informar tipo de material e endereço.

### RF04 – O sistema deve permitir agendamento de coleta.

### RF05 – O sistema deve mostrar o status da coleta em tempo real.

### RF06 – O sistema deve enviar notificações sobre atualizações da coleta.

### RF07 – O administrador deve gerenciar solicitações de coleta.

### RF08 – O sistema deve armazenar histórico de coletas.

### RF09 – O sistema deve sugerir pontos de coleta próximos.

### RF10 – O sistema deve organizar rotas de coleta automaticamente.

---

## 4. Requisitos Não Funcionais

### RNF00 – O sistema deve ter tempo de resposta inferior a 3 segundos.

### RNF01 – O sistema deve ser acessível via dispositivos móveis (Android/iOS).

### RNF02 – Os dados dos usuários devem ser protegidos (segurança e privacidade).

### RNF03 – O sistema deve ter alta disponibilidade (mínimo 95% uptime).

### RNF04 – Interface simples e intuitiva.

### RNF05 – O sistema deve suportar múltiplos usuários simultaneamente.

### RNF06 – O sistema deve seguir boas práticas de sustentabilidade digital.

### RNF07 – Backup automático dos dados.

---

## 5. Arquitetura Técnica 

### 5.1 Stacks

#### 5.1.1 Stack Backend 

Node.js (com express) 

API REST 

Autenticação com jwt

#### 5.1.2 Stack Frontend

Mobile:react Native (ou flutter)

web (admin):react.js

#### 5.1.7 Banco de Dados

postgreSQL (dados estruturados) 

firebase(notificações em tempo real)

## 6. Modelo de Dados

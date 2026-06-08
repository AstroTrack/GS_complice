# AstroTrack - Logística Satelital Inteligente

TOGAF • ArchiMate • Logística • IoT • Satélites

## Visão Geral

O AstroTrack é uma solução de monitoramento logístico baseada em comunicação via satélite, desenvolvida para garantir o rastreamento contínuo de veículos e cargas em regiões sem cobertura de redes móveis convencionais (4G e 5G).

O projeto foi concebido para atender empresas de transporte, logística e agronegócio que necessitam de monitoramento em tempo real mesmo em áreas remotas. A solução combina dispositivos IoT embarcados, comunicação satelital, processamento centralizado e interfaces de monitoramento para fornecer visibilidade completa das operações.

---

# Objetivo

O principal objetivo do AstroTrack é garantir conectividade e monitoramento contínuo em qualquer localidade, aumentando a segurança das cargas, reduzindo riscos operacionais e melhorando a eficiência logística.

---

# Principais Funcionalidades

### Rastreamento em Tempo Real

Monitoramento contínuo da localização dos veículos através de GPS.

### Comunicação Satelital

Transmissão de dados mesmo em regiões sem cobertura móvel.

### Gestão de Alertas

Geração automática de notificações para situações de risco ou eventos críticos.

### Histórico de Rotas

Armazenamento completo das viagens realizadas para auditoria e análise.

### Dashboard Operacional

Visualização centralizada das informações de transporte e logística.

### Segurança da Informação

Proteção dos dados através de firewall, controle de acesso e infraestrutura segura.

---

# Problema Solucionado

Atualmente muitas regiões do Brasil apresentam baixa ou nenhuma cobertura de internet móvel, dificultando o rastreamento de veículos e aumentando riscos relacionados à segurança das cargas.

O AstroTrack elimina essa limitação através da utilização de comunicação via satélite, garantindo monitoramento contínuo independentemente da localização do veículo.

---

# Arquitetura da Solução

A solução foi modelada utilizando os conceitos de TOGAF e ArchiMate, sendo dividida em quatro visões principais.

## 1. Vision Architecture

Representa a visão estratégica do projeto.

### Stakeholders

* Empresa de Transporte
* Gestor Logístico
* Motorista
* Cliente Contratante

### Drivers

* Falta de cobertura móvel
* Segurança da carga
* Eficiência logística

### Objetivos

* Garantir rastreamento 24x7
* Reduzir perdas de carga
* Melhorar eficiência logística

### Requisitos

* Rastreamento em tempo real
* Comunicação satelital
* Gestão de alertas
* Armazenamento histórico

### Constraints

* Atualização a cada 60 segundos
* Disponibilidade de 99,9%
* Precisão GPS inferior a 10 metros
* Retenção de dados por 5 anos

---

## 2. Business Architecture

Representa o fluxo operacional da solução.

### Fluxo Principal

Viagem Iniciada

↓

Monitoramento Logístico

↓

Capturar Posição GPS

↓

Coletar Dados da Carga

↓

Transmitir Dados via Satélite

↓

Processar Informações

↓

Atualizar Dashboard

↓

Gerar Alertas

↓

Viagem Monitorada com Sucesso

### Atores

* Administrador
* Motorista
* Gestor Logístico
* Analista de Operações

### Produtos Gerados

* Dados de Localização
* Pacote de Telemetria
* Registro de Rastreamento
* Painel Atualizado
* Notificação Operacional

---

## 3. Application Architecture

Representa os componentes de software e suas comunicações.

### Camada de Apresentação

* Dashboard Web
* Aplicativo Mobile
* Portal Administrativo

### Camada de Aplicação

* API AstroTrack
* Serviço de Rastreamento
* Serviço de Alertas
* Serviço de Autenticação
* Serviço de Relatórios

### Camada de Dados

* PostgreSQL
* Veículo
* Motorista
* Localização
* Carga
* Alerta
* Usuário
* Histórico de Rotas

---

## 4. Technology Architecture

Representa a infraestrutura necessária para operação da solução.

### Componentes

* Dispositivo IoT
* Rede Satelital
* Satélite
* Gateway Satelital
* Internet
* Firewall
* Load Balancer
* Servidor de Aplicação
* Servidor Banco de Dados
* Servidor de Backup

### Fluxo Tecnológico

Dispositivo IoT

↓

Rede Satelital

↓

Satélite

↓

Gateway Satelital

↓

Internet

↓

Firewall

↓

Load Balancer

↓

Servidor de Aplicação

↓

Servidor Banco de Dados

↓

Servidor Backup

---

# Tecnologias e Conceitos Utilizados

| Tecnologia/Conceito   | Finalidade                              |
| --------------------- | --------------------------------------- |
| TOGAF                 | Estruturação da arquitetura corporativa |
| ArchiMate             | Modelagem das arquiteturas              |
| IoT                   | Coleta de dados dos veículos            |
| GPS                   | Geolocalização em tempo real            |
| Comunicação Satelital | Transmissão de dados em áreas remotas   |
| PostgreSQL            | Armazenamento das informações           |
| Dashboard Web         | Monitoramento operacional               |
| Mobile                | Acompanhamento das operações            |

---

# Benefícios da Solução

* Monitoramento contínuo de veículos.
* Redução de perdas e roubos de carga.
* Maior segurança operacional.
* Melhor tomada de decisão logística.
* Cobertura em regiões sem sinal móvel.
* Histórico completo das operações.
* Maior eficiência no transporte.

---

# ODS Atendido

ODS 9 – Indústria, Inovação e Infraestrutura

O AstroTrack contribui para o desenvolvimento de soluções inovadoras voltadas à infraestrutura logística e conectividade em regiões remotas, promovendo maior eficiência e modernização dos processos de transporte.

---

# Autores

Equipe AstroTrack

FIAP – Global Solution

2026

# 🏥 Sistema de Pré-Agendamento

## 📋 Descrição
Este projeto tem como objetivo criar um sistema de pré-agendamento de atendimentos. O sistema permite que o paciente cadastre suas informações pessoais e de saúde antes da consulta, facilitando o acesso e a visualização desses dados pelos profissionais de saúde no momento do atendimento.

O sistema conta com duas interfaces principais:
- **Interface Web**: voltada para os profissionais da saúde, para consulta de agendamentos e gerenciamento dos atendimentos.
- **Interface Mobile**: voltada para os pacientes, permitindo o pré-cadastro, agendamento e acompanhamento do status do atendimento.

## 🧩 Problema que o Sistema Resolve
O sistema busca reduzir o tempo de espera e a burocracia nos atendimentos de emergência, oferecendo um cadastro antecipado que agiliza o processo médico e melhora o fluxo de atendimento nas UPAs. Isso contribui para uma triagem mais eficiente e um atendimento mais humanizado.

## 🎯 Público-Alvo
- Pacientes que necessitam de atendimento em UPAs
- Profissionais da área da saúde (médicos, enfermeiros, recepcionistas)
- Gestores de unidades de saúde pública

## 💻 Tecnologias Utilizadas
- **Backend**: C# com .NET 6 (MVC)
- **Banco de Dados**: SQL Server
- **ORM**: Entity Framework
- **Versionamento**: Git e GitHub
- **Frontend Web**: Razor Pages / ASP.NET
- **Interface Mobile**: React Native com Expo

## ⚙️ Funcionalidades
- Cadastro de pacientes
- Cadastro de profissionais da saúde
- Pré-agendamento de atendimentos
- Consulta de agendamentos
- Visualização de histórico médico
- Gestão de triagens e atendimentos
- Acesso restrito por tipo de usuário (paciente, médico, administrador)
- Envio de lembretes ou confirmações

## 🚀 Como Rodar o Projeto

### 🔧 Backend (Web)

#### Pré-requisitos
- Visual Studio 2022 ou superior (com .NET 6 instalado)
- SQL Server
- Git

#### Passo a Passo
1. Clone o repositório:
   ```bash
   git clone <repositorio-no-github>

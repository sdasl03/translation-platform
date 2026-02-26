# 🌍 Translation Platform - IASD Porto

## 📋 Descrição

Plataforma de tradução em tempo real desenvolvida para facilitar a compreensão de sermões e programas para membros não falantes de português na IASD do Porto. O sistema captura áudio diretamente da mesa de som, traduz automaticamente para múltiplos idiomas usando IA, e disponibiliza o texto traduzido através da interface em uma intranet.

## 🎯 Objetivo

Promover a inclusão e acessibilidade linguística durante os cultos e programas da igreja, permitindo que todos os membros possam acompanhar e participar independentemente do seu idioma nativo.

## 🏗️ Arquitetura do Sistema

### Componente 1: Serviço de Processamento de Áudio (Python)
- **Captura de Áudio**: Integração direta com mesa de som via interface de áudio
- **Speech-to-Text**: Transcrição automática usando modelos de IA
- **Tradução**: Tradução em tempo real idealmente para múltiplos idiomas
- **Comunicação**: Envio de texto traduzido

### Componente 2: Interface Web
- **Recepção de Dados**: Obtenção do texto traduzido em tempo real
- **Visualização**: Interface responsiva e acessível
- **Text-to-Speech**: Síntese de voz no dispositivo do utilizador
- **Multi-idioma**: Suporte para seleção de idioma preferido

## 🚀 Funcionalidades

- ✅ Captura de áudio em tempo real da mesa de som
- ✅ Transcrição automática português → texto
- ✅ Tradução automática para inglês (e outros idiomas futuramente)
- ✅ Interface web responsiva
- ✅ Síntese de voz no dispositivo do cliente
- ✅ Baixa latência (<3 segundos)
- ✅ Suporte para múltiplos utilizadores simultâneos

## 📦 Requisitos

### Backend (Python)
### Frontend
### Instalação
git clone https://github.com/{seu-usuario}/translation-platform.git
cd translation-platform

## Contribuir
Contribuições são bem-vindas! Por favor:

Clone o projeto
Crie uma branch para sua feature (git checkout -b feature/NovaFuncionalidade)
Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade')
Push para a branch (git push origin feature/NovaFuncionalidade)
Abra um Pull Request

## Reportar Problemas
Encontrou um bug? Por favor, abra uma issue com:
  Descrição detalhada do problema
  Passos para reproduzir
  Screenshots (se aplicável)
  Versão do sistema operativo e navegador



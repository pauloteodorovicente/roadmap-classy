# 📋 Criador de POP (Procedimento Operacional Padrão)

![Agente](https://img.shields.io/badge/tipo-agente-3498DB?style=for-the-badge)
![Ideia](https://img.shields.io/badge/status-ideia-95A5A6?style=for-the-badge)
![Uso Pessoal](https://img.shields.io/badge/uso-pessoal-8E44AD?style=for-the-badge)

> Agente proativo que identifica processos repetitivos nas suas conversas com IAs e cria documentação de qualidade "nível McDonald's" automaticamente.

---

## 🎯 Problema que Resolve

Você faz a mesma coisa 3 vezes e não documenta. Na 4ª vez, precisa reexplicar tudo para a IA novamente, desperdiçando tempo e tokens.

**Dores específicas:**
- Fica refazendo configurações que já fez antes
- Perde tempo explicando contexto repetidamente
- Não sabe quais processos deveriam ser documentados
- Documentação manual é chata e nunca acontece

---

## 💡 A Solução

Um agente que:
1. **Monitora suas conversas** com Claude, Gemini, etc
2. **Identifica padrões** (ex: "Ele configurou o Supabase 3 vezes")
3. **Te avisa proativamente:** "Ei Paulo, você faz isso sempre. Bora criar um POP?"
4. **Gera a documentação** em formato checklist, pronta para usar

---

## ✨ Características Principais

- 🔍 **Monitoramento Inteligente** - Analisa histórico de conversas
- 🤖 **Proatividade** - Sugere POPs sem você pedir
- 📝 **Qualidade McDonald's** - Checklists detalhados, sem ambiguidade
- 🎯 **Priorização** - Indica quais POPs são mais urgentes
- 📚 **Biblioteca Central** - Todos os POPs em um só lugar (Wiki)

---

## 🔍 Como Funciona (Fluxo)

### Etapa 1: Monitoramento Passivo
O agente roda em background, analisando:
- Conversas no Claude.ai
- Chats no Google AI Studio
- Comandos no Claude Code

### Etapa 2: Identificação de Padrões
Quando detecta repetição, classifica:
- **Alta prioridade:** Feito 3+ vezes nos últimos 30 dias
- **Média prioridade:** Feito 2 vezes, mas complexo
- **Baixa prioridade:** Feito 1 vez, mas com potencial de repetir

### Etapa 3: Notificação Proativa
````
🔔 Novo POP Sugerido!

Você configurou o Supabase 3 vezes este mês:
- 03/02: Projeto "Diário"
- 11/02: Projeto "Galeria de Fotos"
- 18/02: Projeto "RH Cognitivo"

Gerar POP agora? [Sim] [Lembrar depois] [Não precisa]
````

### Etapa 4: Geração Automática
Se você aceita, ele cria:
````markdown
# POP: Configuração Inicial do Supabase

## Contexto
Este procedimento é executado sempre que iniciamos um novo projeto com banco de dados.

## Pré-requisitos
- [ ] Conta no Supabase criada
- [ ] Projeto novo criado no painel

## Passo a Passo

### 1. Configurar Autenticação
- [ ] Acessar Settings > Authentication
- [ ] Ativar Google OAuth
- [ ] Copiar Client ID e Secret
- [ ] Colar no `.env`:
```bash
SUPABASE_URL=https://xxx.supabase.co
SUPABASE_ANON_KEY=xxx
```

### 2. Criar Tabela de Usuários
- [ ] SQL Editor > New Query
- [ ] Colar código:
```sql
CREATE TABLE users (
  id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
  email TEXT UNIQUE NOT NULL,
  created_at TIMESTAMPTZ DEFAULT NOW()
);
```
- [ ] Executar (Run)

### 3. Configurar RLS (Row Level Security)
- [ ] Table Editor > users > RLS
- [ ] Habilitar RLS
- [ ] Criar policy: "Usuários só veem próprios dados"

## Checklist Final
- [ ] Autenticação funcionando
- [ ] Tabela criada
- [ ] RLS ativo
- [ ] Teste de login concluído

## Referências
- [Docs oficiais](https://supabase.com/docs)
- Conversa original: [Link para Claude chat]

*Criado automaticamente em: 18/02/2026*
````

---

## 🛠️ Onde ele opera?

**Opção 1: Gem no AI Studio (Início)**
- Você cola manualmente o histórico de conversas
- Ele analisa e sugere POPs
- Limitação: Processo manual

**Opção 2: Sistema Automatizado (Futuro)**
- Integração via API com Claude.ai
- Roda em background
- Notificações automáticas

---

## 🔧 Stack Tecnológica (Provisória)

### Versão MVP (Gem)
- **Plataforma:** Google AI Studio
- **Input:** Você cola histórico de chats manualmente
- **Output:** POPs em Markdown

### Versão Automatizada (Futuro)
- **Backend:** Node.js + Supabase
- **IA:** Claude API (análise de padrões)
- **Integrações:** Claude.ai API, Gemini API
- **Notificações:** Email ou Slack
- **Hospedagem:** Railway

---

## 📅 Roadmap Planejado

### Fase 1: MVP Manual (1 semana)
- [x] Ideia documentada
- [ ] Criar Gem no AI Studio
- [ ] Prompt de System Instructions
- [ ] Testar com 3 históricos de chat reais
- [ ] Gerar 3 POPs de qualidade

### Fase 2: Semi-automação (2 semanas)
- [ ] Script que exporta chats do Claude.ai
- [ ] Processa localmente e sugere POPs
- [ ] Salva na Wiki automaticamente

### Fase 3: Full Automation (Futuro)
- [ ] Integração nativa com Claude.ai
- [ ] Dashboard: "5 POPs pendentes"
- [ ] Sistema de tags e busca

---

## 🎯 Critério de Sucesso (MVP)

- ✅ Gerar 10 POPs de qualidade usando o Gem
- ✅ Reutilizar pelo menos 3 deles em projetos reais
- ✅ Economizar 2+ horas/semana não tendo que reexplicar processos

---

## 📚 Inspiração: POPs de Referência

Estudar estes materiais para garantir qualidade "nível McDonald's":
- [ ] Documentação da NASA (processos espaciais)
- [ ] Manual de franquias do McDonald's
- [ ] Protocolos médicos de hospitais
- [ ] SOPs de empresas de aviação

---

*Criado em: Fevereiro 2026*

# 📔 Diário Inteligente

![App](https://img.shields.io/badge/tipo-app-2ECC71?style=for-the-badge)
![Ideia](https://img.shields.io/badge/status-ideia-95A5A6?style=for-the-badge)
![SaaS Potencial](https://img.shields.io/badge/uso-SaaS_potencial-D35400?style=for-the-badge)

> Sistema de diário pessoal que transforma áudios desorganizados em registros estruturados com acompanhamento de metas e evolução por áreas da vida.

---

## 🎯 Problema que Resolve

Gravar áudios do dia é rápido, mas depois eles ficam perdidos e difíceis de revisar. Impossível acompanhar progresso ou identificar padrões de evolução ao longo do tempo.

**Dores específicas:**
- Perco insights importantes que não são revisitados
- Não consigo medir se estou evoluindo nas áreas certas
- Difícil transformar reflexões em ações concretas (metas)

---

## 💡 A Solução

Um app onde você:
1. **Grava áudio do seu dia** (5-10 min no celular)
2. **IA transcreve e organiza** em bullets estruturados
3. **Categoriza automaticamente** por áreas da vida (Espiritual, Profissional, Saúde, etc)
4. **Acompanha metas SMART** com lembretes de progresso
5. **Visualiza evolução** em gráficos semanais/mensais

---

## ✨ Características Principais

- 🎙️ **Input por Voz** - Transcrição automática via Whisper API
- 🧠 **Organização Inteligente** - Claude analisa e cria bullets + tags
- 📊 **Dashboard de Evolução** - Gráficos de progresso por área
- 🎯 **Metas SMART** - Define e acompanha objetivos mensuráveis
- 🔔 **Cobrança Automática** - Notificações: "Você não registrou nada há 3 dias"
- 📱 **Mobile First** - App nativo ou PWA para gravar onde estiver

---

## 🗂️ Estrutura de Áreas da Vida

1. **Espiritual** - Oração, leitura, meditação
2. **Apostólico** - Evangelização, serviço
3. **Profissional** - Trabalho, projetos, aprendizado
4. **Intelectual** - Estudo, leitura, cursos
5. **Saúde** - Exercício, alimentação, sono
6. **Relacionamentos** - Família, amigos, networking
7. **Financeiro** - Receita, investimentos, controle

---

## 🔧 Stack Tecnológica (Provisória)

- **Frontend:** React Native (app mobile) ou Next.js (PWA)
- **Backend:** Supabase (auth + database + storage)
- **IA:** 
  - Whisper API (transcrição de áudio)
  - Claude API (organização + insights)
- **Notificações:** OneSignal ou Firebase Cloud Messaging
- **Hospedagem:** Vercel + Supabase

---

## 📅 Roadmap Planejado

### Fase 1: MVP Pessoal (2 semanas)
- [x] Ideia documentada
- [ ] Criar BRIEFING.md detalhado
- [ ] Protótipo de telas (Figma)
- [ ] PRD técnico
- [ ] Desenvolver: Gravar áudio → Transcrever → Organizar em bullets
- [ ] Testar 30 dias de uso pessoal

### Fase 2: Metas & Acompanhamento (1 semana)
- [ ] Sistema de metas SMART
- [ ] Dashboard de progresso
- [ ] Notificações de cobrança

### Fase 3: SaaS (Futuro)
- [ ] Multi-usuário
- [ ] Planos (Freemium + Premium)
- [ ] Exportação para PDF/Notion
- [ ] Integração com calendários

---

## 🎯 Critério de Sucesso (MVP)

- ✅ Consigo gravar 5 min de áudio e ter bullets organizados em < 30 segundos
- ✅ Identifico padrões de evolução olhando o dashboard semanal
- ✅ Uso todos os dias por 30 dias consecutivos

---

## 🚀 Potencial de Monetização

**ICP Potencial:**
- Empreendedores que fazem journaling
- Coaches e terapeutas (para uso com clientes)
- Estudantes de pós-graduação (registro de pesquisas)

**Planos Possíveis:**
- Free: 10 áudios/mês, 3 áreas da vida
- Pro: Ilimitado, todas áreas, exportação, API

---

*Criado em: Fevereiro 2026*

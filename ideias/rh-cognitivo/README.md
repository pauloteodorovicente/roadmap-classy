# 🧠 RH de Capacidade Cognitiva

![Sistema](https://img.shields.io/badge/tipo-sistema-E74C3C?style=for-the-badge)
![Ideia](https://img.shields.io/badge/status-ideia-95A5A6?style=for-the-badge)
![Cliente](https://img.shields.io/badge/uso-cliente-C0392B?style=for-the-badge)

> Sistema de recrutamento que identifica a capacidade cognitiva de candidatos e faz o match perfeito com a complexidade das funções.

---

## 🎯 Problema que Resolve

Contratar pela experiência no currículo não garante sucesso. Pessoas com QI acima da média ficam desmotivadas em funções repetitivas, e pessoas com perfil operacional travam em cargos estratégicos.

**Dores específicas:**
- Turnover alto porque a pessoa "não se encaixou"
- Contratar cedo demais (quando ainda dá pra fazer sozinho)
- Contratar tarde demais (perdendo oportunidades de crescimento)

---

## 💡 A Solução

Um sistema que:
1. **Analisa a função** e define o nível cognitivo ideal
2. **Testa candidatos** com bateria de avaliações (lógica, verbal, numérica)
3. **Faz o match** entre perfil cognitivo e complexidade da vaga
4. **Recomenda momento certo** de contratar com base na carga de trabalho

---

## ✨ Características Principais

- 🧪 **Bateria de Testes Cognitivos** - Raciocínio lógico, verbal, numérico, espacial
- 📊 **Análise de Complexidade** - IA avalia requisitos da função
- 🎯 **Score de Match** - % de fit entre candidato e vaga
- 📈 **Indicador de Contratação** - "Ainda é cedo" / "Momento ideal" / "Você está atrasado"
- 📝 **Relatório Detalhado** - Pontos fortes, riscos, recomendações de onboarding

---

## 🔍 Como Funciona (Fluxo)

### Etapa 1: Mapeamento da Função
Você responde:
- Qual a principal entrega dessa vaga?
- A pessoa vai executar ou planejar?
- Quantas variáveis ela precisa considerar simultaneamente?
- Qual o nível de autonomia esperado?

**IA classifica** em 5 níveis:
1. **Operacional Repetitivo** (QI 85-100)
2. **Operacional com Variações** (QI 95-110)
3. **Tático** (QI 105-120)
4. **Estratégico** (QI 115-130)
5. **Visionário** (QI 125+)

### Etapa 2: Teste do Candidato
Bateria de 30-45 min com questões de:
- Lógica (padrões, sequências)
- Raciocínio verbal (interpretação, analogias)
- Raciocínio numérico (problemas, gráficos)
- Resolução de problemas complexos

### Etapa 3: Relatório de Match
````
João Silva - Desenvolvedor Backend
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📊 Score Cognitivo: 118 (Estratégico)
🎯 Match com vaga: 92% (Excelente)

✅ Pontos Fortes:
- Raciocínio lógico: 95º percentil
- Capacidade de abstração: 88º percentil

⚠️ Pontos de Atenção:
- Pode ficar desmotivado com tarefas repetitivas
- Precisa de desafios frequentes

💡 Recomendação:
Contrate e dê autonomia desde o início. 
Evite microgerenciamento.
````

---

## 🔧 Stack Tecnológica (Provisória)

- **Frontend:** Next.js (dashboard admin + página de testes)
- **Backend:** Supabase
- **IA:** Claude API (análise de match + relatórios)
- **Testes:** Integração com plataforma existente (ex: TestGorilla) ou criação própria
- **Hospedagem:** Vercel + Supabase

---

## 📅 Roadmap Planejado

### Fase 1: MVP (4 semanas)
- [x] Ideia documentada
- [ ] Criar BRIEFING.md
- [ ] PRD técnico
- [ ] Pesquisar plataformas de teste cognitivo existentes (licenciar ou criar?)
- [ ] Desenvolver: Cadastro de vaga + Teste básico + Relatório de match
- [ ] Testar com 5 contratações reais

### Fase 2: Indicador de Timing (2 semanas)
- [ ] Algoritmo que analisa carga de trabalho x capacidade
- [ ] Dashboard: "Você deve contratar em X meses"

### Fase 3: Expansão (Futuro)
- [ ] Testes personalizados por área (Tech, Vendas, Marketing)
- [ ] Integração com ATS (Applicant Tracking Systems)
- [ ] White-label para consultorias de RH

---

## 🎯 Critério de Sucesso (MVP)

- ✅ Fazer 5 contratações usando o sistema
- ✅ Pelo menos 4 delas se provarem excelentes no primeiro trimestre
- ✅ Reduzir tempo de entrevistas em 50% (menos candidatos desalinhados)

---

## 🚀 Potencial de Monetização

**ICP Potencial:**
- Startups de 10-50 funcionários (crescendo rápido)
- Consultorias de RH especializadas
- Headhunters que querem se diferenciar

**Modelos Possíveis:**
- Pay-per-use: R$ 200 por candidato testado
- Assinatura: R$ 1.500/mês (até 20 testes)
- White-label: R$ 5.000 + % de receita

---

## ❓ Perguntas Pendentes

- [ ] **Usar testes prontos ou criar próprios?** (Investigar TestGorilla, Mettl, Criteria Corp)
- [ ] **Validação científica é necessária?** (Consultar psicólogos organizacionais)
- [ ] **LGPD:** Como armazenar dados sensíveis de candidatos?

---

*Criado em: Fevereiro 2026*

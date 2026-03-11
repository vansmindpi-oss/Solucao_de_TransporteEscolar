# Solucao_de_TransporteEscolar — VansMind

## Visão do MVP
O VansMind é uma plataforma que organiza a operação do transporte escolar com foco no motorista.

### O que o MVP entrega
1. Rotas e vagas padronizadas
2. Solicitação/aprovação de vaga
3. Lista do dia do motorista
4. Check-in/out (registro)
5. Avisos padronizados (atraso/ocorrência)
6. Histórico por rota/dia

---

## Diretrizes de UX (motorista-first)
- poucos cliques para ações críticas
- lista do dia sempre acessível
- botões grandes e claros
- fluxo rápido para check-in/out
- avisos com templates (reduz digitação)

---

## Fluxos essenciais (resumo)
1) Motorista cria rota → define vagas  
2) Responsável solicita vaga → motorista aprova  
3) Motorista abre “lista do dia”  
4) Motorista registra check-in/out  
5) Motorista envia aviso de atraso/ocorrência  
6) Histórico do dia fica registrado  

---

## Regras de negócio (essenciais)
- não permitir check-out sem check-in
- solicitação aprovada consome uma vaga
- responsável vê apenas seu(s) aluno(s) fictícios
- histórico registra autor e horário do evento

---

## Privacidade e segurança (essencial)
- aluno identificado por código (A01) no MVP
- sem endereço completo
- permissões por perfil (responsável/motorista/admin)
- log de ações (auditoria simples)

---

## Roadmap (futuro, fora do MVP)
- integrações com notificações reais
- GPS em tempo real
- pagamento
- otimização automática de rota

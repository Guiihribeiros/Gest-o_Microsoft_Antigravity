# Diário de Bordo: Evolução da Infraestrutura

Este documento registra as intervenções e auditorias realizadas no ambiente Microsoft 365 & Azure via Antigravity AI.

## 🗓️ Janeiro de 2026

### Auditoria de Segurança e Identidade
- **MFA Health Check:** Validação de políticas de Acesso Condicional para contas administrativas e colaboradores.
- **Saneamento de Privilégios:** Remoção de 9 funções administrativas redundantes da conta de Admin Permanente e revogação de acessos globais de contas não-críticas.

### Gestão de Dispositivos (Intune)
- **Inventário de Frota:** Varredura de conformidade em notebooks Dell e ativos BYOD.
- **Check de Criptografia:** Identificação de status de BitLocker para garantir proteção de dados em repouso.

### Monitoramento e Auditoria
- **Diagnóstico de Logs:** Verificação da retenção nativa do Entra ID e ativação do Unified Audit Log no Microsoft Purview.

---

### 29/01/2026 - Verificação de MFA concluída para Admin Permanente via Agente IA.
> [NOTA TÉCNICA] A automação identificou a necessidade da permissão 'UserAuthenticationMethod.Read.All' para futuras auditorias automáticas (Erro 403 resolvido via ajuste de privilégios de API).

### 29/01/2026 - Documentação do Pilar de Gestão de Endpoints (Intune/AVD) concluída.
- Formalização das políticas de conformidade e estratégia de máquinas virtuais para o time de desenvolvimento.

### 29/01/2026 - Governança de Aplicativos: Integração Pipedrive (E-mail/CRM).
- **Resolução Técnica:** Correção de conflito de consentimento administrativo via Microsoft Graph API.
- **Resultado:** Escopos de E-mail (`Mail.ReadWrite`, `Mail.Send`) e Calendário validados e liberados para a organização, garantindo a produtividade do time de vendas com segurança.

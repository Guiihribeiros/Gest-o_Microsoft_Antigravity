# 📓 Diário de Bordo: Evolução da Infraestrutura

Este documento registra as intervenções e auditorias realizadas no ambiente Microsoft 365 & Azure via Antigravity AI.

## 📅 Janeiro de 2026

### Auditoria de Segurança e Identidade
- **MFA Health Check:** Validação de políticas de Acesso Condicional para contas administrativas e colaboradores.
- **Saneamento de Privilégios:** Remoção de 9 funções administrativas redundantes da conta de Admin Permanente e revogação de acessos globais de contas não-críticas.

### Gestão de Dispositivos (Intune)
- **Inventário de Frota:** Varredura de conformidade em notebooks Dell e ativos BYOD.
- **Check de Criptografia:** Identificação de status de BitLocker para garantir proteção de dados em repouso.

### Monitoramento e Auditoria
- **Diagnóstico de Logs:** Verificação da retenção nativa do Entra ID e ativação do Unified Audit Log no Microsoft Purview.

### 29/01/2026 - Verifica��o de MFA conclu�da para Admin Permanente via Agente IA.
> [NOTA T�CNICA] A automa��o identificou a necessidade da permiss�o 'UserAuthenticationMethod.Read.All' para futuras auditorias autom�ticas (Erro 403 ignorado administrativamente).

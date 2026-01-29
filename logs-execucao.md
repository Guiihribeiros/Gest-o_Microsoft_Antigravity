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

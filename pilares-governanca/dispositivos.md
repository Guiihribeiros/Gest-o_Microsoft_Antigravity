💻 Pilar: Gestão de Endpoints e Mobilidade
Na LBPay, a gestão de dispositivos é centralizada no Microsoft Intune, garantindo que qualquer hardware que acesse dados corporativos esteja em conformidade com nossos padrões de segurança.

1. Padronização de Frota (Dell & Corporativos)
Utilizamos o Autopilot e políticas de configuração para garantir que todo notebook novo seja provisionado de forma segura e padronizada:

Criptografia de Disco: Exigência de BitLocker ativo em 100% dos discos corporativos para proteção de dados em caso de perda ou roubo.
Segurança de Host: Configuração de Firewall do Windows e Microsoft Defender for Endpoint gerenciados via nuvem para bloqueio de ameaças em tempo real.
Conformidade (Compliance): Dispositivos que não atendem aos requisitos mínimos de segurança são impedidos de acessar recursos críticos da empresa.
2. Estratégia BYOD (Bring Your Own Device)
Para colaboradores que utilizam dispositivos pessoais, aplicamos políticas de MAM (Mobile Application Management) para proteger a informação sem invadir a privacidade do usuário:

Isolamento de Dados: Separação completa entre dados corporativos e dados pessoais no dispositivo.
Controle de Acesso: Bloqueio de acesso a aplicações sensíveis (Outlook, Teams, SharePoint) caso o dispositivo apresente riscos de segurança detectados.
3. Infraestrutura Virtual (AVD)
Para a equipe de desenvolvimento, operamos via Azure Virtual Desktop (AVD) para garantir performance e segurança:

Ambientes Multi-sessão: Máquinas virtuais de alta performance (32GB) otimizadas para o fluxo de trabalho dos desenvolvedores.
Segurança do Código-Fonte: O desenvolvimento ocorre dentro do perímetro seguro da Azure, impedindo que dados sensíveis residam em máquinas locais não monitoradas.

# 🛡️ Pilar: Segurança e Gestão de Identidade

A segurança na LBPay é fundamentada no modelo **Zero Trust**, onde a identidade é o novo perímetro. Utilizamos auditorias assistidas por IA para garantir que apenas as pessoas certas tenham o acesso certo, no momento certo.

## 1. Princípio do Privilégio Mínimo (PoLP)
Em Janeiro de 2026, realizamos uma revisão profunda das permissões administrativas (Roles) no Entra ID.

* **Saneamento de Funções:** Identificamos que contas de administradores permanentes acumulavam múltiplas funções redundantes (ex: Exchange Admin + Teams Admin + Global Admin).
* **Ação:** Centralizamos as permissões na função de *Global Administrator* para o responsável pela infraestrutura e removemos 9 atribuições diretas desnecessárias.
* **Resultado:** Redução drástica do "blast radius" (raio de impacto) em caso de comprometimento de conta.

## 2. Estratégia de Autenticação Multifator (MFA)
Implementamos políticas de Acesso Condicional granulares para equilibrar segurança e produtividade:

* **Administradores:** Exigência de MFA diária e rigorosa para qualquer acesso ao portal de administração.
* **Colaboradores:** Política de confiança de 30 dias para dispositivos conhecidos, reduzindo a fadiga de MFA sem comprometer a segurança da startup.

## 3. Próximos Passos (Roadmap)
* Implementação de **Privileged Identity Management (PIM)** para acessos Just-In-Time.
* Revisão semestral automatizada de acessos via Access Reviews.

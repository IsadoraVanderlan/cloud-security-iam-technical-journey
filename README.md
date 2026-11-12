# Cloud Security & Identity Access Management | Technical Development & Hands-on Labs

> **Portfólio técnico de estudos e laboratórios em Identity & Access Management (IAM) .**

Este repositório registra minha evolução prática em **Active Directory, PowerShell, Linux, IAM, IGA, PAM e segurança de acessos**. Cada tópico pode conter anotações, comandos, capturas de tela, vídeos e referências das aulas estudadas.

**Objetivo:** desenvolver competências de operação, investigação, auditoria e automação de acessos em ambientes corporativos.


<p align="center">
  <img src="./imgs/iam.png" alt="Cloud Security & IAM | Technical Development & Hands-on Labs" width="750">
</p>

<br/>

### Como navegar

- Clique em uma **etapa** para abrir os tópicos. Todas começam recolhidas.
- Na coluna **Material / evidência**, substitua `—` por links para suas anotações, imagens, vídeos ou scripts.
- Use `anotacoes/`, `evidencias/`, `scripts/` e `videos/` para organizar o material sem deixar a página principal extensa.
- Marque o status com `⬜` (pendente), `🟡` (em estudo) ou `✅` (concluído).

> **Segurança:** publique somente exemplos fictícios e dados de laboratório. Não exponha informações internas, credenciais, nomes de clientes ou evidências de produção.

<br/>

## Trilha de aprendizado

<details>
<summary><strong>ETAPA 01 — Active Directory (AD)</strong> · 55 tópicos</summary>

### Estrutura do Active Directory

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 001 | O que é Active Directory e para que serve | ⬜ | — |
| 002 | O que é um controlador de domínio (Domain Controller) | ⬜ | — |
| 003 | O que é domínio, floresta e árvore | ⬜ | — |
| 004 | O que são Unidades Organizacionais (OUs) | ⬜ | — |
| 005 | O que são sub-OUs | ⬜ | — |
| 006 | O que são objetos do Active Directory | ⬜ | — |
| 007 | Como utilizar o ADUC (Active Directory Users and Computers) | ⬜ | — |
| 008 | O que são grupos de segurança e grupos de distribuição | ⬜ | — |
| 009 | Diferenças entre grupos Global, Domain Local e Universal | ⬜ | — |
| 010 | Como funciona a herança e organização de objetos | ⬜ | — |

### Gerenciamento de usuários no AD

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 011 | Criar um usuário | ⬜ | — |
| 012 | Alterar dados de um usuário | ⬜ | — |
| 013 | Renomear um usuário | ⬜ | — |
| 014 | Redefinir a senha de um usuário | ⬜ | — |
| 015 | Desbloquear uma conta | ⬜ | — |
| 016 | Habilitar uma conta | ⬜ | — |
| 017 | Desabilitar uma conta | ⬜ | — |
| 018 | Excluir um usuário | ⬜ | — |
| 019 | Mover um usuário entre OUs | ⬜ | — |
| 020 | Configurar expiração de conta | ⬜ | — |
| 021 | Configurar exigência de troca de senha | ⬜ | — |
| 022 | Consultar propriedades e atributos de um usuário | ⬜ | — |
| 023 | Identificar contas inativas | ⬜ | — |
| 024 | Identificar contas com senha que não expira | ⬜ | — |
| 025 | Identificar contas administrativas | ⬜ | — |

### Grupos e permissões no AD

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 026 | Criar grupos | ⬜ | — |
| 027 | Alterar propriedades de grupos | ⬜ | — |
| 028 | Excluir grupos | ⬜ | — |
| 029 | Adicionar usuários a grupos | ⬜ | — |
| 030 | Remover usuários de grupos | ⬜ | — |
| 031 | Consultar membros de grupos | ⬜ | — |
| 032 | Identificar todos os grupos de um usuário | ⬜ | — |
| 033 | Entender grupos aninhados | ⬜ | — |
| 034 | Identificar acessos herdados por associação a grupos | ⬜ | — |
| 035 | Entender o modelo AGDLP | ⬜ | — |
| 036 | Delegar permissões administrativas | ⬜ | — |
| 037 | Identificar grupos privilegiados, como Domain Admins | ⬜ | — |

### GPO e permissões Windows

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 038 | O que é Group Policy (GPO) | ⬜ | — |
| 039 | Como as GPOs são aplicadas | ⬜ | — |
| 040 | Como verificar GPOs aplicadas a um usuário ou computador | ⬜ | — |
| 041 | Entender políticas de senha e bloqueio | ⬜ | — |
| 042 | Entender permissões NTFS | ⬜ | — |
| 043 | Conceder e remover permissões em pastas | ⬜ | — |
| 044 | Diferença entre permissões NTFS e de compartilhamento | ⬜ | — |
| 045 | Identificar permissões efetivas | ⬜ | — |
| 046 | Investigar acesso negado a pastas | ⬜ | — |

### Autenticação e diagnóstico do AD

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 047 | Entender DNS aplicado ao Active Directory | ⬜ | — |
| 048 | Entender LDAP e LDAPS | ⬜ | — |
| 049 | Entender Kerberos e autenticação no domínio | ⬜ | — |
| 050 | Entender o básico de NTLM | ⬜ | — |
| 051 | Investigar falhas de login | ⬜ | — |
| 052 | Investigar bloqueios recorrentes de contas | ⬜ | — |
| 053 | Identificar problemas de associação a grupos | ⬜ | — |
| 054 | Consultar logs de segurança do Windows | ⬜ | — |
| 055 | Identificar alterações realizadas em usuários e grupos | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 02 — PowerShell para Gestão de Acessos</strong> · 44 tópicos</summary>

### Fundamentos de PowerShell

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 056 | Abrir e utilizar o PowerShell | ⬜ | — |
| 057 | Entender cmdlets | ⬜ | — |
| 058 | Utilizar Get-Help | ⬜ | — |
| 059 | Utilizar Get-Command | ⬜ | — |
| 060 | Entender o pipeline (\|) | ⬜ | — |
| 061 | Trabalhar com variáveis | ⬜ | — |
| 062 | Trabalhar com objetos e propriedades | ⬜ | — |
| 063 | Utilizar Where-Object | ⬜ | — |
| 064 | Utilizar Select-Object | ⬜ | — |
| 065 | Utilizar Sort-Object | ⬜ | — |
| 066 | Criar condições com if e else | ⬜ | — |
| 067 | Criar repetições com foreach | ⬜ | — |
| 068 | Criar funções simples | ⬜ | — |

### Administração do AD com PowerShell

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 069 | Consultar usuários com Get-ADUser | ⬜ | — |
| 070 | Criar usuários com New-ADUser | ⬜ | — |
| 071 | Alterar usuários com Set-ADUser | ⬜ | — |
| 072 | Desabilitar usuários com Disable-ADAccount | ⬜ | — |
| 073 | Habilitar usuários com Enable-ADAccount | ⬜ | — |
| 074 | Desbloquear usuários com Unlock-ADAccount | ⬜ | — |
| 075 | Redefinir senhas com Set-ADAccountPassword | ⬜ | — |
| 076 | Consultar grupos com Get-ADGroup | ⬜ | — |
| 077 | Consultar membros com Get-ADGroupMember | ⬜ | — |
| 078 | Criar grupos com New-ADGroup | ⬜ | — |
| 079 | Adicionar membros com Add-ADGroupMember | ⬜ | — |
| 080 | Remover membros com Remove-ADGroupMember | ⬜ | — |
| 081 | Consultar usuários de uma OU | ⬜ | — |
| 082 | Mover usuários entre OUs | ⬜ | — |
| 083 | Localizar contas inativas | ⬜ | — |
| 084 | Localizar contas com senha sem expiração | ⬜ | — |
| 085 | Consultar membros de grupos privilegiados | ⬜ | — |

### Automação e relatórios

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 086 | Importar dados de CSV | ⬜ | — |
| 087 | Exportar relatórios para CSV | ⬜ | — |
| 088 | Criar scripts para consultas em lote | ⬜ | — |
| 089 | Criar scripts para criação de usuários | ⬜ | — |
| 090 | Criar scripts para desabilitação de usuários | ⬜ | — |
| 091 | Criar scripts para adicionar e remover grupos | ⬜ | — |
| 092 | Validar dados antes de executar alterações | ⬜ | — |
| 093 | Utilizar -WhatIf quando disponível | ⬜ | — |
| 094 | Tratar erros com try e catch | ⬜ | — |
| 095 | Criar logs de execução | ⬜ | — |
| 096 | Evitar alterações duplicadas em scripts | ⬜ | — |
| 097 | Gerar relatórios de contas inativas | ⬜ | — |
| 098 | Gerar relatórios de grupos privilegiados | ⬜ | — |
| 099 | Criar um script de auditoria de acessos | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 03 — Linux para Gestão de Acessos</strong> · 52 tópicos</summary>

### Usuários e grupos Linux

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 100 | Entender usuários locais | ⬜ | — |
| 101 | Entender grupos locais | ⬜ | — |
| 102 | Consultar usuários com id e getent | ⬜ | — |
| 103 | Criar usuários com useradd | ⬜ | — |
| 104 | Alterar usuários com usermod | ⬜ | — |
| 105 | Excluir usuários com userdel | ⬜ | — |
| 106 | Criar grupos com groupadd | ⬜ | — |
| 107 | Alterar grupos com groupmod | ⬜ | — |
| 108 | Excluir grupos com groupdel | ⬜ | — |
| 109 | Adicionar usuários a grupos | ⬜ | — |
| 110 | Remover usuários de grupos | ⬜ | — |
| 111 | Consultar grupos de um usuário | ⬜ | — |
| 112 | Entender /etc/passwd | ⬜ | — |
| 113 | Entender /etc/shadow | ⬜ | — |
| 114 | Entender /etc/group | ⬜ | — |

### Senhas e permissões Linux

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 115 | Alterar senhas com passwd | ⬜ | — |
| 116 | Configurar expiração de senha com chage | ⬜ | — |
| 117 | Bloquear e desbloquear contas | ⬜ | — |
| 118 | Configurar expiração de usuários | ⬜ | — |
| 119 | Entender permissões rwx | ⬜ | — |
| 120 | Utilizar chmod | ⬜ | — |
| 121 | Utilizar chown | ⬜ | — |
| 122 | Utilizar chgrp | ⬜ | — |
| 123 | Entender permissões numéricas (755, 750, 640 etc.) | ⬜ | — |
| 124 | Entender umask | ⬜ | — |
| 125 | Consultar e configurar ACLs com getfacl e setfacl | ⬜ | — |
| 126 | Identificar por que um usuário não consegue acessar um arquivo ou diretório | ⬜ | — |

### Privilégios e autenticação Linux

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 127 | Entender o que é sudo | ⬜ | — |
| 128 | Configurar permissões com visudo | ⬜ | — |
| 129 | Entender o arquivo sudoers | ⬜ | — |
| 130 | Conceder sudo a grupos específicos | ⬜ | — |
| 131 | Restringir comandos administrativos | ⬜ | — |
| 132 | Identificar usuários com privilégios elevados | ⬜ | — |
| 133 | Entender autenticação por SSH | ⬜ | — |
| 134 | Configurar autenticação por chaves SSH | ⬜ | — |
| 135 | Restringir usuários e grupos no sshd_config | ⬜ | — |
| 136 | Entender PAM (Pluggable Authentication Modules) | ⬜ | — |
| 137 | Entender o diretório /etc/pam.d/ | ⬜ | — |
| 138 | Entender o papel do NSS na resolução de identidades | ⬜ | — |

### Linux integrado ao Active Directory

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 139 | Entender o que é SSSD | ⬜ | — |
| 140 | Entender o que é realmd | ⬜ | — |
| 141 | Entender Kerberos no Linux | ⬜ | — |
| 142 | Integrar Linux ao AD com realm join | ⬜ | — |
| 143 | Consultar usuários do domínio no Linux | ⬜ | — |
| 144 | Consultar grupos do domínio no Linux | ⬜ | — |
| 145 | Restringir login a grupos autorizados do AD | ⬜ | — |
| 146 | Configurar sudo para grupos do AD | ⬜ | — |
| 147 | Verificar o funcionamento do SSSD | ⬜ | — |
| 148 | Investigar falhas de autenticação do domínio | ⬜ | — |
| 149 | Consultar logs com journalctl | ⬜ | — |
| 150 | Consultar /var/log/auth.log ou /var/log/secure, conforme a distribuição | ⬜ | — |
| 151 | Investigar falhas de sudo e SSH | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 04 — IAM — Gestão de Identidades e Acessos</strong> · 29 tópicos</summary>

### Conceitos essenciais de IAM

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 152 | O que é IAM | ⬜ | — |
| 153 | Diferença entre identidade e conta | ⬜ | — |
| 154 | Diferença entre autenticação e autorização | ⬜ | — |
| 155 | O que é MFA | ⬜ | — |
| 156 | O que é SSO | ⬜ | — |
| 157 | O que é federação de identidade | ⬜ | — |
| 158 | O que é RBAC | ⬜ | — |
| 159 | O que é ABAC | ⬜ | — |
| 160 | O que é princípio do menor privilégio | ⬜ | — |
| 161 | O que é necessidade de saber (Need to Know) | ⬜ | — |
| 162 | O que é segregação de funções (SoD) | ⬜ | — |
| 163 | O que é uma conta de serviço | ⬜ | — |
| 164 | O que é uma conta privilegiada | ⬜ | — |
| 165 | O que é uma conta compartilhada e quais são seus riscos | ⬜ | — |

### Ciclo de vida dos acessos

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 166 | Entender o processo Joiner (admissão) | ⬜ | — |
| 167 | Entender o processo Mover (mudança de cargo ou setor) | ⬜ | — |
| 168 | Entender o processo Leaver (desligamento) | ⬜ | — |
| 169 | Provisionar acessos | ⬜ | — |
| 170 | Alterar acessos | ⬜ | — |
| 171 | Revogar acessos | ⬜ | — |
| 172 | Conceder acessos temporários | ⬜ | — |
| 173 | Controlar expiração de acessos | ⬜ | — |
| 174 | Validar aprovações antes de conceder acesso | ⬜ | — |
| 175 | Identificar quem é responsável por aprovar um acesso | ⬜ | — |
| 176 | Entender acessos por perfil ou função | ⬜ | — |
| 177 | Verificar se o acesso solicitado é compatível com o cargo | ⬜ | — |
| 178 | Documentar evidências de concessão e revogação | ⬜ | — |
| 179 | Tratar solicitações emergenciais | ⬜ | — |
| 180 | Evitar privilégios excessivos | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 05 — IGA — Governança de Identidades</strong> · 18 tópicos</summary>

### Governança e revisão de acessos

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 181 | O que é IGA | ⬜ | — |
| 182 | Diferença entre IAM e IGA | ⬜ | — |
| 183 | Entender Access Requests | ⬜ | — |
| 184 | Entender fluxos de aprovação | ⬜ | — |
| 185 | Entender Access Reviews | ⬜ | — |
| 186 | Entender recertificação de acessos | ⬜ | — |
| 187 | Entender Entitlements | ⬜ | — |
| 188 | Entender Role Mining | ⬜ | — |
| 189 | Entender Role Engineering | ⬜ | — |
| 190 | Criar e interpretar matrizes de acesso | ⬜ | — |
| 191 | Identificar conflitos de segregação de funções | ⬜ | — |
| 192 | Identificar contas órfãs | ⬜ | — |
| 193 | Identificar contas inativas | ⬜ | — |
| 194 | Identificar permissões excessivas | ⬜ | — |
| 195 | Entender reconciliação de contas e acessos | ⬜ | — |
| 196 | Verificar divergências entre acessos aprovados e acessos existentes | ⬜ | — |
| 197 | Gerar evidências para auditoria | ⬜ | — |
| 198 | Entender o funcionamento básico de ferramentas como SailPoint ou Saviynt | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 06 — PAM — Gestão de Acessos Privilegiados</strong> · 15 tópicos</summary>

### Contas privilegiadas

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 199 | O que é PAM | ⬜ | — |
| 200 | Diferença entre IAM, IGA e PAM | ⬜ | — |
| 201 | Identificar contas privilegiadas | ⬜ | — |
| 202 | Entender contas administrativas individuais | ⬜ | — |
| 203 | Entender contas de serviço privilegiadas | ⬜ | — |
| 204 | Entender cofres de senhas (Password Vault) | ⬜ | — |
| 205 | Entender rotação de credenciais | ⬜ | — |
| 206 | Entender acesso Just-in-Time (JIT) | ⬜ | — |
| 207 | Entender elevação temporária de privilégios | ⬜ | — |
| 208 | Entender aprovação de acesso privilegiado | ⬜ | — |
| 209 | Entender gravação e monitoramento de sessões | ⬜ | — |
| 210 | Entender contas de emergência (Break Glass) | ⬜ | — |
| 211 | Entender revogação de privilégios | ⬜ | — |
| 212 | Entender auditoria de acessos privilegiados | ⬜ | — |
| 213 | Conhecer o funcionamento básico de ferramentas como CyberArk | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 07 — Auditoria, segurança e troubleshooting</strong> · 25 tópicos</summary>

### Investigação de acessos

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 214 | Investigar por que um usuário não consegue autenticar | ⬜ | — |
| 215 | Investigar por que um usuário não consegue acessar um recurso | ⬜ | — |
| 216 | Diferenciar problema de autenticação e de autorização | ⬜ | — |
| 217 | Identificar permissões ausentes | ⬜ | — |
| 218 | Identificar permissões excessivas | ⬜ | — |
| 219 | Investigar contas bloqueadas | ⬜ | — |
| 220 | Investigar contas desabilitadas | ⬜ | — |
| 221 | Investigar grupos incorretos | ⬜ | — |
| 222 | Investigar falhas de sincronização de identidades | ⬜ | — |
| 223 | Investigar problemas de acesso no Linux | ⬜ | — |
| 224 | Investigar falhas de sudo e SSH | ⬜ | — |
| 225 | Identificar alterações não autorizadas em grupos | ⬜ | — |
| 226 | Consultar logs de auditoria | ⬜ | — |
| 227 | Identificar eventos relevantes de segurança | ⬜ | — |
| 228 | Registrar evidências e causa raiz | ⬜ | — |
| 229 | Escalar incidentes de segurança corretamente | ⬜ | — |

### Compliance e controles

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 230 | Entender controles de acesso da ISO 27001/27002 | ⬜ | — |
| 231 | Entender os princípios relevantes do NIST | ⬜ | — |
| 232 | Entender a relação entre LGPD e controle de acesso | ⬜ | — |
| 233 | Entender rastreabilidade de alterações | ⬜ | — |
| 234 | Entender retenção e integridade de evidências | ⬜ | — |
| 235 | Entender revisões periódicas de acesso | ⬜ | — |
| 236 | Entender indicadores de risco de identidade | ⬜ | — |
| 237 | Criar relatórios de auditoria | ⬜ | — |
| 238 | Recomendar correções para falhas de controle | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 08 — Ferramentas e processos corporativos</strong> · 12 tópicos</summary>

### Chamados e gestão de serviços

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 239 | Entender o que é ITSM | ⬜ | — |
| 240 | Diferenciar incidente, requisição, problema e mudança | ⬜ | — |
| 241 | Entender SLAs | ⬜ | — |
| 242 | Validar aprovações de chamados | ⬜ | — |
| 243 | Registrar atividades executadas | ⬜ | — |
| 244 | Documentar evidências | ⬜ | — |
| 245 | Identificar chamados que precisam de escalonamento | ⬜ | — |
| 246 | Entender procedimentos operacionais (SOP) | ⬜ | — |
| 247 | Criar documentação técnica | ⬜ | — |
| 248 | Criar uma base de conhecimento | ⬜ | — |
| 249 | Entender indicadores de produtividade e qualidade | ⬜ | — |
| 250 | Conhecer ServiceNow ou a ferramenta de chamados utilizada pela equipe | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 09 — Microsoft Entra ID e identidades híbridas</strong> · 14 tópicos</summary>

### Identidades Microsoft

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 251 | Entender a diferença entre AD e Entra ID | ⬜ | — |
| 252 | Criar e administrar usuários no Entra ID | ⬜ | — |
| 253 | Administrar grupos | ⬜ | — |
| 254 | Entender funções administrativas (Roles) | ⬜ | — |
| 255 | Entender sincronização de identidades | ⬜ | — |
| 256 | Entender identidade híbrida | ⬜ | — |
| 257 | Entender MFA no Entra ID | ⬜ | — |
| 258 | Entender Conditional Access | ⬜ | — |
| 259 | Entender redefinição de senha por autoatendimento (SSPR) | ⬜ | — |
| 260 | Entender Access Reviews | ⬜ | — |
| 261 | Entender Privileged Identity Management (PIM) | ⬜ | — |
| 262 | Consultar logs de login | ⬜ | — |
| 263 | Consultar logs de auditoria | ⬜ | — |
| 264 | Entender o básico de Microsoft Graph para consultas e automação | ⬜ | — |

</details>

<details>
<summary><strong>ETAPA 10 — Automação e melhoria contínua</strong> · 14 tópicos</summary>

### Automação aplicada ao trabalho

| Nº | Aprendizado / laboratório | Status | Material / evidência |
|:--:|---|:--:|---|
| 265 | Identificar tarefas repetitivas que podem ser automatizadas | ⬜ | — |
| 266 | Criar scripts PowerShell reutilizáveis | ⬜ | — |
| 267 | Criar relatórios automáticos de usuários e grupos | ⬜ | — |
| 268 | Automatizar consultas de contas inativas | ⬜ | — |
| 269 | Automatizar verificações de grupos privilegiados | ⬜ | — |
| 270 | Validar solicitações antes de executar alterações | ⬜ | — |
| 271 | Entender APIs REST e JSON | ⬜ | — |
| 272 | Entender SCIM para provisionamento de identidades | ⬜ | — |
| 273 | Criar automações com logs e tratamento de erros | ⬜ | — |
| 274 | Utilizar Git para versionar scripts | ⬜ | — |
| 275 | Testar scripts em laboratório antes da produção | ⬜ | — |
| 276 | Documentar procedimentos automatizados | ⬜ | — |
| 277 | Medir tempo economizado com melhorias | ⬜ | — |
| 278 | Propor correções para processos com falhas recorrentes | ⬜ | — |

</details>

<br/>

## Organização dos arquivos

```text
gestao-acessos-n1/
├── README.md
├── anotacoes/       # Resumos, comandos e links de aulas
├── evidencias/      # Capturas de tela de laboratórios
├── scripts/         # Scripts PowerShell e Bash
└── videos/          # Links ou pequenos vídeos demonstrativos
```
<br/>

### Exemplo de preenchimento

Para o tópico **011 — Criar um usuário**, você pode substituir `—` por:

```markdown
[Anotações](anotacoes/011-criar-usuario-ad.md) · [Imagem](evidencias/011-criar-usuario-ad.png) · [Vídeo](https://exemplo.com/meu-video) · [Aula](https://exemplo.com/aula)
```

Use links externos para vídeos grandes; isso evita aumentar desnecessariamente o tamanho do repositório.

<br/>

---

*Projeto pessoal de aprendizado e laboratório. Não representa documentação oficial de empregadores ou clientes.*

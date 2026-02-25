# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: 24 de fevereiro de 2026
Empresa: AURORA
Responsável: Carlos Henrique

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa AURORA, realizado por Carlos Henrique. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto com os serviços da AWS, com a finalidade de aumentar a maturidade digital e a proteção de dados da empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas da implantação:

Etapa 1: Implementação de MFA e Políticas de Menor Privilégio (AWS IAM)
Descrição de caso de uso: Configuração do AWS Identity and Access Management (IAM) para garantir que cada colaborador tenha apenas as permissões estritamente necessárias para sua função. Foi estabelecida a obrigatoriedade de Autenticação de Múltiplos Fatores (MFA) para todos os acessos ao console, prevenindo invasões por roubo de credenciais simples.

Etapa 2: Proteção de Bordas e Mitigação de Ataques (AWS WAF & Shield)
Descrição de caso de uso: Ativação do AWS WAF (Web Application Firewall) para filtrar o tráfego de entrada das aplicações da AURORA, bloqueando padrões de ataques comuns como SQL Injection e Cross-Site Scripting (XSS). Em conjunto, o AWS Shield foi configurado para garantir proteção automática contra ataques de negação de serviço (DDoS), mantendo a disponibilidade dos sistemas.

Etapa 3: Monitoramento Contínuo e Detecção de Ameaças (Amazon GuardDuty)
Descrição de caso de uso: Implementação do Amazon GuardDuty, um serviço de detecção inteligente que monitora continuamente atividades suspeitas em contas AWS, instâncias e dados armazenados no S3. Ele utiliza aprendizado de máquina para identificar comportamentos anômalos, como tentativas de mineração de criptomoedas ou acessos de localizações geográficas incomuns, gerando alertas imediatos para a equipe técnica.

## Conclusão
A implementação de ferramentas na empresa AURORA tem como esperado a redução drástica da superfície de ataque e a garantia de conformidade com boas práticas de segurança em nuvem, o que aumentará a eficiência e a produtividade da empresa ao mitigar riscos de paralisação por incidentes cibernéticos. Recomenda-se a continuidade da utilização das ferramentas implementadas e a realização de auditorias periódicas para manter os processos atualizados.

## Assinatura do Responsável pelo Projeto:
Carlos Henrique N. S.

# Governança de Dados - Projeto Sabor Seguro DBurger 

Este documento detalha as políticas de proteção de dados, anonimização e controle de acesso implementadas no Projeto Sabor Seguro da DBurger, garantindo a conformidade com a Lei Geral de Proteção de Dados (LGPD) e as melhores práticas de ética em dados [2] [3]. 

 

1. Políticas de Proteção de Dados 

1.1. Coleta e Uso de Dados 

Finalidade Específica: A coleta de dados é realizada exclusivamente para a previsão de demanda e otimização de estoque, com o objetivo de reduzir o desperdício de insumos e melhorar a experiência do cliente [2]. 

Minimização de Dados: Apenas os dados estritamente necessários para atingir os objetivos do projeto são coletados. Informações sensíveis, como geolocalização exata, são deliberadamente excluídas [2]. 

Consentimento: Quando aplicável, o consentimento explícito dos titulares dos dados será obtido e registrado, conforme exigido pela LGPD. 

 

1.2. Armazenamento e Segurança 

Infraestrutura Criptografada: Todos os dados coletados são armazenados em infraestrutura criptografada para proteger contra acessos não autorizados [3]. 

Controles de Acesso: O acesso aos dados é restrito a pessoal autorizado e é baseado no princípio do menor privilégio, garantindo que apenas quem precisa acessar os dados para desempenhar suas funções tenha permissão. 

Monitoramento Contínuo: A infraestrutura de dados é monitorada continuamente para identificar e responder a quaisquer vulnerabilidades ou incidentes de segurança [3]. 

 

2. Políticas de Anonimização 

2.1. Anonimização por Design 

Dados de Geolocalização: Dados de geolocalização exata não são armazenados. Apenas informações de bairro são utilizadas para fins de logística de entrega, garantindo que a identificação individual não seja possível [2] [3]. 

Agregação de Dados: Padrões de grupos de clientes são analisados de forma agregada, sem a possibilidade de identificar indivíduos específicos. Isso permite a previsão de comportamento sem comprometer a privacidade [2]. 

 

2.2. Técnicas de Anonimização 

Pseudonimização: Dados que poderiam, em teoria, identificar um indivíduo são pseudonimizados, substituindo identificadores diretos por substitutos artificiais. Isso permite a análise sem a exposição da identidade real. 

Generalização: Informações detalhadas são substituídas por categorias mais amplas para evitar a reidentificação. 

 

3. Controle de Acesso 

3.1. Papéis e Responsabilidades 

DPO (Data Protection Officer): Um DPO é designado para supervisionar todas as atividades relacionadas à proteção de dados e garantir a conformidade com a LGPD [3]. 

Equipe Especializada: A equipe de Cientistas de Dados e TI é treinada em práticas de segurança e privacidade de dados e é responsável pela implementação e manutenção das políticas [3]. 

 

3.2. Auditoria e Rastreabilidade 

Logs de Acesso: Todos os acessos aos dados são registrados em logs de auditoria, permitindo a rastreabilidade de quem acessou o quê e quando. 

Revisões Periódicas: As políticas de controle de acesso e as permissões são revisadas periodicamente para garantir que permaneçam adequadas e seguras. 

 

Referências 

[1] FIAP. (2026). Aula 4: Construção de uma visão de desenvolvimento de solução de dados alinhada à governança (Solution Product View). 
[2] FIAP. (2026). CheckPoint 2 - Case DBurger1.pptx. 
[3] FIAP. (2026). Aula 5: Defesa de proposta de projetos de dados corporativos (Data Science Innovation Proposal). 

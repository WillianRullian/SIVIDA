# Backlog do Projeto SIVIDA - Plataforma de Monitoramento Ambiental Urbano

## Projeto: SIVIDA - Plataforma de Monitoramento Ambiental Urbano

### Épico 1: Monitoramento da Qualidade do Ar
- **Feature**: Coleta e Exibição de Dados de Qualidade do Ar
  - **História do Usuário 1**: "Como cidadão, quero visualizar a qualidade do ar na minha região para entender os níveis de poluentes."
  - **História do Usuário 2**: "Como gestor público, quero receber alertas automáticos quando os níveis de poluentes ultrapassarem limites aceitáveis."
  - **Tarefas**:
    - Implementar integração com sensores IoT para coleta de dados em tempo real.
    - Desenvolver mapa interativo com índice de qualidade do ar (com gradiente de cores).
    - Criar pop-up informativo explicando os níveis de poluição.

### Épico 2: Monitoramento de Risco de Deslizamento
- **Feature**: Detecção de Riscos com Base em Dados de Sensores e Clima
  - **História do Usuário 3**: "Como cidadão, quero ser alertado sobre riscos de deslizamento para evitar áreas perigosas."
  - **História do Usuário 4**: "Como gestor público, quero visualizar áreas de risco de deslizamento para planejar ações de mitigação."
  - **Tarefas**:
    - Desenvolver algoritmo de análise de dados climáticos e do solo.
    - Criar botão de compartilhamento para alertar outros cidadãos via WhatsApp.
    - Implementar visualização de mapas com zonas de risco.

### Épico 3: Monitoramento da Cobertura Vegetal
- **Feature**: Análise de Imagens de Satélite e Detecção de Desmatamento
  - **História do Usuário 5**: "Como gestor público, quero acompanhar a evolução da cobertura vegetal para prevenir desmatamento ilegal."
  - **Tarefas**:
    - Integrar imagens de satélite a partir de bancos de dados governamentais.
    - Implementar ferramenta de comparação temporal para identificar perda de vegetação.
    - Gerar alertas para desmatamento em áreas críticas.

### Épico 4: Interface do Usuário
- **Feature**: Interface Mobile
  - **História do Usuário 6**: "Como cidadão, quero acessar informações do SIVIDA pelo meu celular de forma prática e intuitiva."
  - **Tarefas**:
    - Desenvolver telas em React Native para iOS e Android.
    - Implementar funcionalidades como localização automática e menu interativo.
    - Criar funcionalidade de download de relatórios.
- **Feature**: Interface Web
  - **História do Usuário 8**: "Como gestor público, quero acessar um painel detalhado com gráficos e relatórios sobre o ambiente."
  - **Tarefas**:
    - Desenvolver dashboards interativos com dados consolidados.
    - Configurar sistema de login e autenticação.

### Épico 5: Integração com IoT e Big Data
- **Feature**: Processamento de Dados em Tempo Real
  - **História do Usuário 9**: "Como analista ambiental, quero visualizar dados consolidados e tendências para apoiar a tomada de decisão."
  - **Tarefas**:
    - Criar pipelines de processamento em Big Data.
    - Implementar algoritmos de aprendizado de máquina para predição de tendências ambientais.

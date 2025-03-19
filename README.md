# Desafio Código na Veia

### **Desafio de Programação: Sistema de Relatório de Rodovias**

**Descrição**: Desenvolva um sistema web simples para cadastrar e gerar relatórios sobre a situação de rodovias, estradas e sinalizações. O sistema permitirá que usuários façam o cadastro de novas ocorrências e visualizem relatórios detalhados sobre diferentes rodovias.

---

#### **Requisitos Técnicos**:
- **Framework**: Qualquer
- **Banco de Dados**: Postgres, MySQL (ou SQLite para simplificação)

---

### **Funcionalidades Principais**:

1. **Cadastro de Ocorrências de Estradas**:
   - Crie um formulário para adicionar novas ocorrências relacionadas a uma estrada.
   - Campos sugeridos:
     - Nome da rodovia
     - Trecho (início e fim)
     - Tipo de problema (buraco, sinalização danificada, erosão, etc.)
     - Data de ocorrência
     - Descrição do problema
     - Localização (latitude e longitude)

2. **Listagem de Ocorrências**:
   - Exiba uma lista de todas as ocorrências cadastradas.
   - Permitir filtrar por:
     - Nome da rodovia
     - Tipo de problema
     - Data da ocorrência

3. **Autenticação**:
   - Os usuários devem se autenticar para acessar o sistema. Utilize a autenticação nativa do Laravel.

---

### **Funcionalidades Extras (Opcional)**:
- **Mapas**: Integrar um mapa (por exemplo, Google Maps ou Leaflet) para mostrar a localização das ocorrências com marcadores.
- **Uploads de Imagens**: Permitir que os usuários façam upload de fotos das ocorrências para adicionar aos relatórios.
- **Notificações por E-mail**: Enviar um e-mail para um usuário cadastrado quando uma nova ocorrência for adicionada.
- **Dashboard**:
   - Exiba um resumo no dashboard com:
     - Total de ocorrências registradas
     - Número de ocorrências por tipo de problema
     - Gráfico simples com ocorrências por rodovia

---

### **Critérios de Avaliação**:
- Qualidade e organização do código.
- Uso adequado das funcionalidades do Laravel.
- Estruturação correta do banco de dados.
- Implementação de segurança (como autenticação e validação de dados).
- Cumprimento dos requisitos propostos.
- Clareza e simplicidade da interface.

---

### **Instruções para Participação**:

1. **Criação da Branch**:
   - A partir da branch `main`, crie uma nova branch utilizando seu nome completo, separado por hífens. Exemplo:
     ```
     git checkout -b joao-silva
     ```

2. **Implementação**:
   - Desenvolva a aplicação com base nos requisitos listados.
   - Siga as boas práticas de desenvolvimento.
   - Garanta que o código esteja bem organizado e funcional.

3. **Commit e Push**:
   - Realize commits frequentes e claros, documentando as alterações e funcionalidades implementadas.
   - Faça o push da sua branch para o repositório.

---

### **Diferenciais (Extras)**:

- **Docker**:
  - Disponibilize um ambiente Docker para facilitar a execução do projeto. Crie um `Dockerfile` e um `docker-compose.yml` configurando a aplicação, banco de dados e outras dependências necessárias.
  
- **Cobertura de Testes**:
  - Implementar testes automatizados para as principais funcionalidades do sistema.
  - Utilizar PHPUnit para criar testes de integração e unitários.

- **Boas Práticas de Código**:
  - Aplicar padrões de projeto (Design Patterns) adequados ao contexto.
  - Utilização de PSR-12 (PHP Standards Recommendations) e outras práticas de qualidade de código.

- **Uso de PHPStan**:
  - Configure e execute a ferramenta PHPStan para análise estática do código, garantindo alta qualidade e prevenção de erros.
  
- **Documentação**:
  - Adicionar uma documentação clara no arquivo `README.md` com instruções detalhadas de como configurar e executar o projeto localmente utilizando Docker.

---

### **Critérios de Diferenciação**:

- Organização e clareza dos commits.
- Implementação de funcionalidades extras como mapas e uploads de imagens.
- Validação de dados e segurança da aplicação.
- Usabilidade e design da interface.
- Uso de Docker para facilitar a execução e desenvolvimento do projeto.
- Implementação e uso de PHPStan para validação estática do código.

---

**Boa sorte no desafio!**

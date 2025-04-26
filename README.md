# DIO - Trilha Java Básico

## Autor

🔸[wprotheus](https://github.com/wprotheus)

---

## Desafio - Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio  

Atividade executada conforme vídeos do [Desafio](https://web.dio.me/lab/criando-um-copiloto-com-fluxo-de-conversa-personalizado-no-microsoft-copilot-studio/learning/dc37952e-e5dd-480d-8d3e-24a15903b4fe) e orientações abaixo.  
<small><sup>Obs.: O link acima somente é acessado através de uma conta na plataforma DIO.</sup></small>

### Descrição do Desafio

> O objetivo deste desafio é criar um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio.

#### Em -> INFORMAÇÕES  
> Crie um Copilot com um fluxo de conversa personalizado no Microsoft Copilot Studio. Aprenda a iniciar um copiloto do zero, customizar um tópico, personalizar mensagens de erro e ajustar a qualidade das respostas utilizando GenAI. Ao final, você terá um copiloto otimizado para oferecer interações mais precisas e eficientes.  


---  

## 📜 # Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

### 1. Apresentação do Tutorial

Neste tutorial, você aprenderá a criar um copiloto totalmente customizado utilizando o [Microsoft Copilot Studio](https://copilotstudio.microsoft.com). Vamos partir de um projeto em branco, configurar tópicos personalizados, melhorar as mensagens de erro e ajustar a qualidade das respostas geradas por IA (GenAI). Ao final, você terá um copiloto otimizado para interações mais precisas e eficientes.

---

### 2. Criar um Copilot em Branco

**Passos:**

1. Acesse [Microsoft Copilot Studio](https://copilotstudio.microsoft.com).
2. Clique em **Copilots** no menu lateral.
3. Selecione **Criar copiloto**.
4. Escolha **Copiloto em branco**.
5. Defina:
    - Nome do copiloto
    - Idioma
    - Descrição (opcional)
6. Clique em **Criar**.

> **Nota:** O copiloto será criado sem fluxos ou conexões iniciais. Ideal para máxima personalização.

---

### 3. Customizar um Tópico

**Passos:**

1. No painel do copiloto, acesse **Tópicos**.
2. Clique em **Novo Tópico**.
3. Defina:
    - **Nome:** Um nome claro e objetivo (ex: "Agendamento de Reunião").
    - **Frases de gatilho:** Expressões que o usuário pode usar para ativar o tópico.
4. Configure o **Fluxo de Conversa**:
    - Adicione perguntas e respostas.
    - Utilize condições de decisão (If/Else) conforme necessário.

> **Dica:** Crie perguntas abertas para enriquecer a interação.

---

### 4. Personalizar uma Mensagem de Erro de Tópico

**Passos:**

1. No editor de fluxo do tópico, clique no botão de erro padrão.
2. Substitua a mensagem genérica por uma resposta mais humana e amigável.

   **Exemplo:**
   > "Desculpe, não entendi o que você quis dizer. Pode reformular, por favor?"

3. Salve o tópico.

> **Importante:** Mensagens personalizadas melhoram drasticamente a experiência do usuário e a taxa de retenção no chat.

---

### 5. Aumentar/Diminuir a Qualidade da Resposta com GenAI

**Passos:**

1. Acesse o fluxo do tópico onde existe uma **Resposta Generativa**.
2. Clique na resposta generativa para abrir as opções.
3. Ajuste os seguintes parâmetros:

    - **Temperatura**:
        - Valor mais baixo (ex: 0.2) → Respostas mais diretas e previsíveis.
        - Valor mais alto (ex: 0.8) → Respostas mais criativas e variadas.

    - **Top-p**:
        - Controle a diversidade considerando as palavras de maior probabilidade.

4. Teste diferentes configurações para encontrar o equilíbrio ideal entre criatividade e precisão para seu caso de uso.

> **Recomendação:**  
> Para bots corporativos: **Temperatura baixa** + **Top-p restrito**.  
> Para bots de suporte leve ou engajamento social: **Temperatura média-alta** + **Top-p mais amplo**.

---

## Conclusão

Seguindo este tutorial, você terá desenvolvido um copiloto funcional, customizado para atender com alta eficiência às necessidades dos usuários.  
Para evoluir ainda mais, explore integração com bases de conhecimento (Dataverse, SharePoint, Azure Cognitive Search) e implemente fluxos de fallback inteligentes.
    
---  
  
## 📚 Documentação Recomendada    

- [Documentação do Microsoft Copilot Studio - PT-BR](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/)  
- [Documentação do Microsoft Copilot Studio - EN-US](https://learn.microsoft.com/en-us/microsoft-copilot-studio/overview)

>---

### Observações Finais

Este material foi desenvolvido com base em vídeos do desafio proposto no Bootcamp **Suzano - Python Developer**, combinando informações coletadas da Internet e adaptadas com o auxílio de Inteligência Artificial.

> **Nota importante:** Devido à falta de acesso direto ao Microsoft Copilot Studio no momento da produção, os passos e configurações foram ajustados conforme as melhores práticas documentadas e simulações teóricas. Pequenas variações podem ocorrer no ambiente real de desenvolvimento.

***Sugestão:*** Ao obter acesso à ferramenta, recomendo revisar todos os fluxos criados e realizar testes práticos para validar o comportamento efetivo do copiloto.

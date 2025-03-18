# ia-generativa-copilot

## 🛠️ Tecnologias Utilizadas  
- **Microsoft Azure** – Plataforma em nuvem para serviços de IA.  
- **OpenAI** – Modelos avançados de inteligência artificial para processamento de linguagem e geração de conteúdo.  

## ▶️ Passo a Passo  

### 1️⃣ Introdução  
Este guia apresenta um roteiro para explorar os serviços de IA generativa da Microsoft, incluindo Copilot e OpenAI no Azure. Você aprenderá como utilizar filtros de moderação de conteúdo e também como criar imagens e extrair informações de arquivos visuais.  

⚠️ **Nota:** Para aprofundar seus conhecimentos, consulte sempre a documentação oficial:  
- [Microsoft Copilot](#)  
- [Azure OpenAI](#)  
- [Filtros de Conteúdo no Azure OpenAI](#)  

---

### 2️⃣ Criando Imagens com o Microsoft Copilot  
O Microsoft Copilot permite transformar descrições textuais em imagens usando modelos de IA generativa.  

#### Como testar a criação de imagens no Azure:  
1. **Acesse o Microsoft Copilot** no seu navegador.  
2. **Digite uma descrição detalhada** da imagem que deseja gerar. Exemplo: *"Um robô futurista pintando uma tela digital em um estúdio de arte"*  
3. **Escolha o estilo da imagem**, se disponível. Algumas opções incluem realismo, arte digital, desenho animado, entre outros.  
4. **Aguarde o processamento da IA** e visualize o resultado.  
5. **Baixe ou edite a imagem**, conforme necessário.  

Dicas para obter melhores imagens:  
✅ Use descrições detalhadas, mencionando cores, cenários e emoções.  
✅ Experimente diferentes estilos para encontrar a melhor representação.  
✅ Se o resultado não for o esperado, refine a descrição e gere novamente.  

---

### 3️⃣ Extraindo Texto de Imagens  
Agora vamos configurar um serviço de inteligência artificial para reconhecer e extrair texto de imagens usando o Azure AI Services.  

#### Criando um Recurso de IA no Azure:  
1. Acesse o **Portal do Azure** e faça login na sua conta.  
2. No menu lateral, clique em **+ Criar um recurso**.  
3. Na barra de pesquisa, digite **Serviços Cognitivos do Azure** e selecione a opção correspondente.  
4. Clique em **Criar** e preencha as seguintes informações:  
   - **Assinatura:** Escolha sua assinatura ativa no Azure.  
   - **Grupo de Recursos:** Selecione um grupo já existente ou crie um novo.  
   - **Região:** Escolha **Leste dos EUA (East US)** ou a mais próxima da sua localização.  
   - **Nome do recurso:** Defina um nome exclusivo.  
   - **Plano de Preços:** Selecione **Standard S0**.  
5. Marque a opção de aceite dos termos e clique em **Criar**.  

#### Habilitando a Extração de Texto (OCR):  
1. Após a criação do recurso, vá até o **Vision Studio** dentro do Azure.  
2. No menu, selecione a ferramenta de **Reconhecimento Óptico de Caracteres (OCR)**.  
3. Clique em **Experimentar agora**.  
4. Faça o upload de uma imagem contendo texto (exemplo: foto de um documento ou placa).  
5. Aguarde o processamento e visualize o texto extraído.  

Dicas para melhor precisão na extração:  
✅ Utilize imagens nítidas e bem iluminadas.  
✅ Prefira textos escritos em fontes padrão (evite manuscritos com baixa legibilidade).  
✅ Se houver erros na extração, tente aumentar a resolução da imagem antes do upload.  

---

### 4️⃣ Testando a Moderação de Conteúdo no OpenAI  
O Azure OpenAI oferece filtros de segurança para analisar e moderar textos e imagens antes de sua utilização.  

#### Como testar os filtros de moderação:  
1. No Portal do Azure, acesse **OpenAI Services**.  
2. Selecione **Moderação de Conteúdo**.  
3. Insira um texto de teste para avaliar se há palavras inadequadas ou conteúdo sensível.  
4. O sistema classificará a entrada e informará se há restrições.  

💡 **Exemplo:** Teste um texto contendo palavras controversas ou expressões potencialmente ofensivas para ver como os filtros atuam.  

Benefícios da moderação de conteúdo:  
✅ Protege contra discursos nocivos e desinformação.  
✅ Garante que os modelos de IA sejam usados de forma ética e responsável.  
✅ Pode ser integrado a aplicações e chatbots para análise automática de mensagens.
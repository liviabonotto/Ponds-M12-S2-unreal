# Ponderada Semana 2 - Unreal Engine e animações
Projeto desenvolvido usando Unreal Engine 5 modelo 3D. Assets gratuitos. 

# 1. Sobre o projeto

Projeto realizado na semana 2 do curso optativo de Engenharia da Computação - Experiências Imersivas. O objetivo foi criar um projeto com um objetivo definido por nós, e partir disso modelar um personagem usando o Metahuman Creator, junto com um áudio de apresentação desse personagem, e uni-los usando a extensão do Metahuman na Unreal Engine 5. Optamos por criar também uma animação do personagem se apresentando em um cenário escolhido por nós, como apresentação do projeto. 

# 2. Descrição do personagem

### 2.1 Propósito:

Um professor de química em realidade virtual, com referência ao personagem de Breaking Bad. Será usado como educador em um ambiente de realidade virtual, ensinando práticas de laboratório e química orgânica. 

### 2.2 Descrição:

O professor se chama Waltinho Blanco, possui 52 anos, e é pai de um garoto especial. Foi diagnosticado com câncer mas já está em tratamento. Trabalha em uma escola pública dando aulas de química orgânica para alunos do ensino médio. 

Sua função será de auxiliar na instrução sobre assuntos relacionados a química e práticas de laboratório em um ambiente virtual para adolescentes do ensino médio. Os usuários poderão interagir com o personagem por meio de perguntas e demonstrações de experiências químicas. 

### 2.3 Aparência:

A aparência escolhida para o avatar reflete a aparência do ator que interpreta o personagem principal de Breaking Bad. A escolha do personagem foi com o intuito de causar identificação do público alvo, visto que é uma produção cinematográfica renomada e apreciada por várias gerações. 

Os elementos como idade, características específicas sobre sua aparência e vestuário refletem a personalidade do ator na série. A ambientação onde o personagem se encontra também foi escolhida inspirada no contexto em que o personagem se encontra na série, com um ar de mistério e com expressões faciais que demonstram seriedade e intimidação. 

### **2.4 Inspiração:**

![Personagem Walter White na série Breaking Bad.](./assets/image.png)

Personagem Walter White na série Breaking Bad.

# 3. Criação do personagem

O personagem foi criado usando a ferramenta Metahuman Creator da Unreal Engine. O personagem foi exportado para ser usado posteriormente no projeto. 

[Vídeo de apresentação do humano virtual.](./assets/MetaHuman_Creator_-_Google_Chrome_2024-11-26_11-47-31.mp4)

Vídeo de apresentação do humano virtual.

![Imagem do humano virtual.](./assets/image%201.png)

Imagem do humano virtual.

# 4. Criação do áudio

Primeiro, criamos um texto de apresentação do humano virtual, seguindo a caracterização do personagem Walter White na série Breaking Bad. Com esse texto, ele fará uma apresentação pessoal e do intuito do projeto. 

### 4.1 Texto de apresentação do personagem

“Bem vindo ao meu laboratório. Meu nome é Waltinho Blanco. Alguns me chamam de Sr. Blanco. Outros... bem, vamos manter isso no passado. O que importa é que estou aqui para ser seu professor de química orgânica. A ciência é poderosa, e eu estou aqui para mostrar a você o quanto ela pode ser fascinante. Nesse ambiente virtual, você aprenderá os fundamentos da química que regem o mundo. Moléculas, reações e transformações que poucos ousam compreender. A pergunta é: você está pronto para aprender? Porque ciência não é brincadeira. É respeito. É precisão. Vamos começar.”

### 4.2 Criando o áudio usando ElevenLabs

Usamos a ferramenta de criação de uma voz personalizada do ElevenLabs, gerado por meio de inteligência artificial e se baseando nos inputs passados por nós - considerando as características do personagem mencionadas anteriormente. A voz gerada foi selecionada e a partir dela demos o input do texto de apresentação criado. O resultado pode ser observado abaixo: 

**Versão inicial:**

[v1-waltinho.mp3](./assets/v1-waltinho.mp3)

**Versão final:**

[v2-waltinho.mp3](./assets/v2-waltinho.mp3)

# 5. Criação da cena

Utilizamos o motor Unreal Engine 5.5 para a criação da cena de apresentação do nosso humano virtual. Seguimos os passos do tutorial do YouTuber MR GFX Unreal para implementação da animação facial com o áudio que geramos com IA!

### 5.1 Demonstração da animação da fala

[Demonstração da animação da fala](./assets/test_voice_01_pros_2024-11-28_12-51-37.mp4)

Demonstração da animação da fala

### 5.2 Demonstração da implementação do áudio na animação

[Demonstração da implementação do áudio na animação](./assets/test_voice_2024-11-28_12-24-10.mp4)

Demonstração da implementação do áudio na animação

### 5.3 Demonstração da implementação da animação de fala no personagem

[Demonstração da implementação da animação de fala no personagem](./assets/M12S2Ponds__Unreal_Editor_2024-11-28_13-03-38.mp4)

Demonstração da implementação da animação de fala no personagem

# 6. Indo além!

Baseado no tutorial do YouTuber MR GFX Unreal e utilizando assets gratuitos da biblioteca Fab, decidimos implementar uma animação corporal no nosso personagem, junto com uma ambientação baseada na série Breaking Bad, usando um asset de laboratório!

### 6.1 Demonstração da implementação de animação corporal e cenário de laboratório

[Demonstração da implementação de animação corporal e cenário de laboratório.](./assets/M12S2Ponds__Unreal_Editor_2024-11-28_13-13-32.mp4)

Demonstração da implementação de animação corporal e cenário de laboratório.

### 6.2 Testagem do modo câmera para definição do enquadramento e gravação

[Testagem do modo câmera para definição do enquadramento e gravação.](./assets/M12S2Ponds__Unreal_Editor_2024-11-28_13-22-04.mp4)

Testagem do modo câmera para definição do enquadramento e gravação.

# 7. Versão final!

Por fim, fizemos a exportação da gravação feita pela câmera do motor, unimos os arquivos de áudio (.wav) e vídeo (.avi) e adicionamos algumas edições usando o Clipchamp, exportamos para .mp4 e subimos no YouTube!

[Vídeo final de apresentação do projeto.](./assets/Waltinho_Blanco.mp4)

Vídeo final de apresentação do projeto.

https://youtu.be/cD5qMl9XRCI

# 8. Referência e créditos

- Meta Human Creator by Unreal Engine - [https://metahuman.unrealengine.com](https://metahuman.unrealengine.com/)
- Voice Generation and Cloning by Eleven Labs - [https://elevenlabs.io/](https://elevenlabs.io/)
- Chemistry Lab Classroom by [styloo](https://www.fab.com/sellers/styloo) [https://fab.com/s/24083491ee1f](https://fab.com/s/24083491ee1f)
- MC Sample Pack by [MoCap Central](https://www.fab.com/sellers/MoCap%20Central) - [https://fab.com/s/71059470c6ce](https://fab.com/s/71059470c6ce)
- “audio to face Metahuman unreal engine 5.5 | Animate face from your voice” by [MR GFX Unreal](https://www.youtube.com/@MR_GFX) -  https://www.youtube.com/watch?v=ld5gwpR72R8
- “Easy way To Add Any Animation To Metahumans | MetaHuman animation library” by  [MR GFX Unreal](https://www.youtube.com/@MR_GFX) -  https://www.youtube.com/watch?v=bV1mquFImGQ
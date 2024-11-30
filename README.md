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

[Vídeo de apresentação](https://github.com/user-attachments/assets/b182e6c4-423b-45bf-b5c0-1b855b95087b)

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

[v1-waltinho.webm](https://github.com/user-attachments/assets/f838d83d-58f7-4741-88c9-e55bf74514a4)

**Versão final:**

[v2-waltinho.webm](https://github.com/user-attachments/assets/c4dbba70-81f3-488a-b456-02c8fa90160f)

# 5. Criação da cena

Utilizamos o motor Unreal Engine 5.5 para a criação da cena de apresentação do nosso humano virtual. Seguimos os passos do tutorial do YouTuber MR GFX Unreal para implementação da animação facial com o áudio que geramos com IA!

### 5.1 Demonstração da animação da fala

[Demonstração da animação da fala](https://github.com/user-attachments/assets/eac8a264-e69b-4451-b9dd-a5258983b677)

Demonstração da animação da fala

### 5.2 Demonstração da implementação do áudio na animação


https://github.com/user-attachments/assets/ace9feba-55ee-4e7c-88ff-137914fa78f4


Demonstração da implementação do áudio na animação

### 5.3 Demonstração da implementação da animação de fala no personagem


https://github.com/user-attachments/assets/211e1355-d697-41ee-9480-a22b9b999c8c


Demonstração da implementação da animação de fala no personagem

# 6. Indo além!

Baseado no tutorial do YouTuber MR GFX Unreal e utilizando assets gratuitos da biblioteca Fab, decidimos implementar uma animação corporal no nosso personagem, junto com uma ambientação baseada na série Breaking Bad, usando um asset de laboratório!

### 6.1 Demonstração da implementação de animação corporal e cenário de laboratório


https://github.com/user-attachments/assets/88fd4dd9-de19-4302-83aa-f61639cd67d0


Demonstração da implementação de animação corporal e cenário de laboratório.

### 6.2 Testagem do modo câmera para definição do enquadramento e gravação



https://github.com/user-attachments/assets/d6f430c1-3150-491d-9c44-31540e50790f


Testagem do modo câmera para definição do enquadramento e gravação.

# 7. Versão final!

Por fim, fizemos a exportação da gravação feita pela câmera do motor, unimos os arquivos de áudio (.wav) e vídeo (.avi) e adicionamos algumas edições usando o Clipchamp, exportamos para .mp4 e subimos no YouTube!


https://github.com/user-attachments/assets/3ac47627-9c44-4e60-a175-433ba27a0df6


Vídeo final de apresentação do projeto.

[Também, é possível visualizar o resultado no YouTube.](https://youtu.be/cD5qMl9XRCI)

# 8. Referência e créditos

- Meta Human Creator by Unreal Engine - [https://metahuman.unrealengine.com](https://metahuman.unrealengine.com/)
- Voice Generation and Cloning by Eleven Labs - [https://elevenlabs.io/](https://elevenlabs.io/)
- Chemistry Lab Classroom by [styloo](https://www.fab.com/sellers/styloo) [https://fab.com/s/24083491ee1f](https://fab.com/s/24083491ee1f)
- MC Sample Pack by [MoCap Central](https://www.fab.com/sellers/MoCap%20Central) - [https://fab.com/s/71059470c6ce](https://fab.com/s/71059470c6ce)
- “audio to face Metahuman unreal engine 5.5 | Animate face from your voice” by [MR GFX Unreal](https://www.youtube.com/@MR_GFX) -  https://www.youtube.com/watch?v=ld5gwpR72R8
- “Easy way To Add Any Animation To Metahumans | MetaHuman animation library” by  [MR GFX Unreal](https://www.youtube.com/@MR_GFX) -  https://www.youtube.com/watch?v=bV1mquFImGQ

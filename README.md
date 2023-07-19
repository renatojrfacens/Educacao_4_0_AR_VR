# Educacao_4_0_AR_VR

Projeto em AR/VR para a matéria de Business Strategy & Agile do curso de pós-graduação em Arquitetura de Software

# Objetivo

O objetivo do projeto Educação 4.0 - AR/VR é através de estudos de caso e desenvolvimento técnico criar um ambiente simulado com VR
e um componente funcional com AR, com intuito de criar um laboratório de testes para atividades práticas para alunos e funcionários 
que estudam ou trabalham remotamente e não conseguem presencialmente executar uma tarefa prática.

# Ferramentas Utilizadas

Para o desenvolvimento do objeto em AR foi utilizado a plataforma Unity para criar objetos em 3D para realidade aumentada, para isso foi necessário
utilizar bibliotecas e importações específicas para o gerenciamento do projeto, a ferramenta principal integrada ao Unity foi o toolkit Vulforia e o
UniGLTF para importação de materiais com extensão .gltf(objetos 3D). 

Outra ferramenta utilizada para a visualização do objeto em AR foi a aplicação DroidCam, um dispositivo que foi instalado tanto no computador em
que o projeto estava sendo executado, quanto no celular do usuário, dessa forma o aplicativo simula a câmera de reconhecimento de objetos 3D. 

Além dessas ferramentas foi necessário usa o Visual Studio para a criação de scripts em C# que foram utilizadas nas funções das tags inforativas. 

As imagens em formato 3D foram retiradas de forma gratuita pelo site Sketchfab e pelo Tinkercad.

Os ambientes VR foram criados utilizando inicialemente o Glitch que é um editor de código online que hospeda e implanta instantaneamente as alterações feitas. Com ele nós usamos html e javascript para criar a estrutura básica da aplicação, juntamente com o A-FRAME que é um web framework utilizado para buildar experiências de realidade virtual.

Os elementos em 3D foram retirados do 3dwarehouse, e junta a ele foi utilizado o Blender que é um software de modelagem 3D.

# Execução

Para executar o conteúdo é necessário importar o arquivo do GitHub **packageeducacao4.0** para o Unity, nele contém os Assets necessários para a
execução do programa. Dentro das pastas dos assets existe as imagens targets,os objetos 3D e o script em C# para executar as funções.

# Scaneamento com QR Code 

Para realizar a ampliação do objeto 3D a partir de uma folha foi utilizado um QR Code, ele foi gerado no intuito de servir como
imagem target (imagem base) para a ampliação do objeto em realidade aumentada, dessa forma é possível que o usuário utilizando o aplicativo DroidCam,
consiga visualizar um objeto a partir de uma figura, que no caso foi o QRcode.

# Tags informativas para os componentes 

As tags informativas são quadros informativos apontando informações e especificações do objeto em AR, no caso o objeto selecionado foi o arduíno uno,
dessa forma ao se aproximar do componente uma tag irá aparecer informando que tipo de componente é aquele no arduíno.

# Componentes para o Arduino 

Foi atribuído a imagem do arduíno todos os componentes existentes na placa além de um led, o logo do projeto Educação 4.0 e as tags informativas,
é possível rotacionar o objeto e aproximar para ter maior visualização e aprofundamento, utilizando os comandos via script as tags informativas só
aparecem caso o usuário se aproxime do componente específico do arduíno. 

# Utilização dos Ambientes VR

Os ambientes VR já estão hospedados para qualquer um poder acessar, só é necessário obter o link, que o prório Glitch fornece.

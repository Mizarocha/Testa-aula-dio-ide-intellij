🔍🔍
# Testa-aula-dio-ide-intellij

## IDe Java Intellij

# Pré-requistos
☑ Sistema operacional (Windows e/ou Linux)      
☑ Conta no GitHub   


#  Instalação/Configuração

## ▫ Windows 

✅ Instalação OpenJDK      
✅ Configuração de variável de ambiente   
✅ Instalação do Eclipse   
✅ Instalação do IntelliJ    

## ▫ IntelliJ 
 
✅ Diferenças entre versões     
✅ Conhecendo um pouco por dentro da IDE     
✅ Criando seu primeiro projeto Java no IntelliJ     
✅ Atalhos e Produtividade     
✅ Conectar seu projeto no GitHub     


 ## Instalação IntelliJ IDEA Community
✅ 1. Entre no site ofical do [INTELLIJ](https://www.jetbrains.com/idea/download/#section=windows)        
✅2. Escolha a opção Community e faça o download        
✅3. Descompacte a pasta e vamos para o terminal        
✅4. Abra o terminal (Ctrl + Alt + t) e entre no diretório que você descompactou No meu caso, na pasta Downloads Ideal        
▪ cd Downloads/IdealC         
✅ 5. Entre na pasta bin        
▪ cd bin          
✅ 6. Execute o arquivo de instalação idea.sh        
▪ ./idea.sh        

##  Instalação Git
✅1. Abra o terminal (Ctrl + Alt + t) e vamos verificar se temos o git instalado:        
• git --version           
✅ 2. Execute o comando:          
• sudo apt-get install git-all        
✅ 3. Confirme novamente se o git realmente está instalado:        
• git --version          
✅ 4. Vamos começar as configurações iniciais:          
▪ 4.1 Cofigurar o nome de usuário          
• git config --global user.name "Seu nome"        
▪  4.2 Configurar o endereço de e-mail:​ É de suma importância que o ENDEREÇO DE E-MAIL SEJA O MESMO DO GITHUB afim de evitar conflitos!         
•  git config --global user.email "Seu e-mail"           
▪  4.3 Vamos conferir a lista de configurações:          
• git config --list           
✅ 5. Pronto, git instalado e configurado com sucesso!         


# Windows

## ◽ Instalação JDK Zulu

Aqui no windows, vamos fazer o download do OpenJDK Zulu. As compilações do Azul Zulu do OpenJDK são compilações de código aberto, testadas pelo TCK e certificadas do OpenJDK. O Zulu Blue está disponível para uma ampla variedade de plataformas de hardware e sistemas operacionais. A documentação do Azul Zulu inclui notas de lançamento, um guia de instalação e licenças de terceiros.

☑ 1. Entre no SITE AZUL          
☑ 2. Faça o download do arquivo .zip do JDK 11.0.11+9. No meu caso, o x86 64-bit         
☑ 3. Vá no drive C://Arquivo de Programas         
☑ 4. Caso não tenha um diretório com o nome Java, crie        
☑ 5. Entre neste diretório e descompacte o download do zip JDK Zulu 11.0.11+9 neste diretório        
☑ 6. Vamos configurar o ambiente JAVA_HOME:                       
▪  6.1 Menu iniciar -> Editar as varáveis de ambiente do sistema                 
▪  6.2 Irá abrir a janela Propriedades do Sistema, escolha a aba Avançado, em seguida clique em variáveis de Ambiente               
▪  6.3 Na janela Variáveis de Ambiente, crie um novo Variáveis do sistema                
▪  6.4 Abrirá uma jabela: Nova Variável de Sistema.          
▪  6.5 Nome da variável: JAVA_HOME            
▪  6.6 Valor da variável:em seguida OK.O valor da variável é o caminho do diretório que você descompactou o zip JDK Zulu 11.0.11+9 no passo5                    
▪  6.7 Na mesma janela Variáveis do Sistema, localize a variável Path, selecione e clique a opção Editar...                    
▪  6.8 Clique na opção Novo e cole o mesmo caminho do passo 5 acrescentando \bin           
▪  6.9 Continue com o path selecionado e clique na opção Mover para Cima até chegar no topo            
☑ 7. Pronto, finalizada a configuração. Próximo passo é conferir se está instalado tudo certinho       
☑ 8. Abra o Prompt de Comando: Menu iniciar -> cmd         
☑ 9. Vamos conferir mais uma vez se o Java está instalado na nossa máquina            

 • java -version

# Phishing para captura de senhas do Facebook

_________________________________________________________________________________________________

## ferramentas usadas

- Kali Linux instalado na VM
- settoolkit

### Configurando o Phishing no Kali Linux

- Primeiro você deve configurar o Kali em modo bridge na VM

*Seleciona o kali na VM > Acessa as configurações > Rede/Networking > Seleciona o modo bridge

- Depois que configurado acessa o Kali
- Acessa o terminal como ADMIN

*Comando para acessar o terminal >`sudo su` 

*Insira a senha de usuário

*Obtendo o endereço da máquina:`ifconfig`

- Inicie com o comando o setoolkit:`setoolkit`
- Tipo de ataque (1):`Social-Engineering Attacks`
- Vetor de ataque(2):`Web Site Attack Vectors`
- Método de ataque(3):`Credential Harvester Attack Method`
- Método de ataque(2):`Site Cloner`
- Se ja aparecer seu IP apenas de um ENTER, caso contrario insira seu IP e de ENTER
- URL para clonar: [http://www.facebook.com](http://www.facebook.com/)
- Agora no seu PC acesse uma pagina anonima e insira o IP DO KALI
- Para testar o funcionamento acesse com usuário e senha teste
- Agora ele vai dar uma travada de leve, ele vai logar na conta do facebook caso ele nao esteja em navegador anonimo e caso a conta do usuario ja esteja logada, porem como estamos usando em forma de teste ele so vai aparecer a pagina de login novamente
- Volte no terminal do kali e procure por

POSSIBLE URSERNAME FIELD FOUN; email=(email que voce digitou na pagina de login falsa)

POSSIBLE PASSWORD FIELD FOUND: pass=(senha que voce digitou na pagina de login falsa)

#FOI TESTADO COM OS SITES:

*FACEBOOK - SUCESSO

*DIO.ME - FAIL

*COLABORAREAD - FAIL

CONCLUSÃO: Foi concluido que nao sao todos os sites que voce consegue usar essa tecnica

TELA COM USUARIO E SENHA DO FACEBOOK

![senha_e_login_capturado](https://user-images.githubusercontent.com/99220549/206729963-26f86828-73a3-4ef3-b3fb-de44679dd45f.png)

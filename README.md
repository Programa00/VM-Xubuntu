## Programa00

Programa de estudos para iniciar mulheres na programação.

Iniciativa das alunas do Eixo de Computação da Universidade Virtual do Estado de São Paulo - UNIVESP

## VM Linux

Para nossos estudos usaremos uma máquina Linux.

Para isso, escolhemos o uso de máquina virtual, e Linux Xubuntu, por ser leve e ao mesmo tempo amigável
com usuários vindos do Windows.

```
VM escolhida: Oracle VirtualBox 6.1

Linux escolhido: Xubuntu LTS 20.4 
```


## Instalação da VM

Faça o download da VirtualBox no link abaixo:

[VirtualBox 6.1.6 para Windows](https://download.virtualbox.org/virtualbox/6.1.6/VirtualBox-6.1.6-137129-Win.exe)

[VirtualBox 6.1.6 para Macintosh - Apple](https://download.virtualbox.org/virtualbox/6.1.6/VirtualBox-6.1.6-137129-OSX.dmg)


## Instalação do Linux dentro da VM

Faça o download da imagem da máquina abaixo:

[Xubuntu para máquina virtual](https://transferxl.com/06jXygR991BS6c)

Essa imagem serve tanto para uso na VirtualBox, como na VMWare e no VirtualPC.

Nesse tutorial, usaremos o VirtualBox.

### Instalação usando o VirtualBox

Dentro do VirtualBox clique em IMPORTAR

![01 - Dentro do VirtualBox clique em IMPORTAR](https://github.com/Programa00/VM-Xubuntu/blob/master/01-importar.png)

Selecione o .ova que você acabou de baixar

![02 - Selecione o .ova que você acabou de baixar](https://github.com/Programa00/VM-Xubuntu/blob/master/02-selecionar-ova.png)

![03 - selecionando](https://github.com/Programa00/VM-Xubuntu/blob/master/03-selecionar-ova.png)

Clique em CONTINUAR e depois em IMPORTAR

![04 - Clique em CONTINUAR](https://github.com/Programa00/VM-Xubuntu/blob/master/04-clique-continuar.png)

![05 - e depois em IMPORTAR](https://github.com/Programa00/VM-Xubuntu/blob/master/05-clique-importar.png)

Inicie a VM clicando na seta VERDE

![06 - iniciar a VM clicando na seta VERDE](https://github.com/Programa00/VM-Xubuntu/blob/master/06-inicie-a-VM.png)

Nosso Xubuntu iniciando :heart_eyes:

![07 - Xubuntu iniciando dentro da VM](https://github.com/Programa00/VM-Xubuntu/blob/master/07-VM%20iniciando.png)

Usuário: Programa00

Senha: 1234


Atenção aos itens marcados: Leiam o arquivo, usem o Chrome para navegar, mudem o teclado na bandeirinha do Brasil se necessário. O coelhinho azul é o menu do nosso Xubuntu. Os ícones do rodapé controlam coisas como: tamanho de tela (eu uso 1024 x 768), volume, etc.

![08 - Atenção aos itens do desktop](https://github.com/Programa00/VM-Xubuntu/blob/master/08-atencao-aos-itens.png)

Instalação concluída!

## Tive um erro, e agora?
### Configurando a sua BIOS

Se você encontrar o seguinte erro iniciando sua VM 
```
VT-x/AMD-V hardware acceleration has been enabled, but is not operational. Your 64-bit guest will fail to detect a 64-bit CPU and will not be able to boot.
```
![10 - erro após a instalação](https://github.com/Programa00/VM-Xubuntu/blob/master/10-erro.png)

A razão é que a virtualização VT-x/AMD-V não está habilitada na sua BIOS.

Você precisará acessar sua BIOS para ativá-la.


A opção estará em lugares diferentes dependendo da marca e modelo da sua placa mãe. Geralmente a ativação da opção VT-x/AMD-V pode ser encontrada na parte dedicada ao processador.

BIOS Antiga :

![11 - Bios Antiga](https://github.com/Programa00/VM-Xubuntu/blob/master/11-bios-antiga.png)

BIOS Asus UEFI BIOS

![12 - BIOS Asus UEFI](https://github.com/Programa00/VM-Xubuntu/blob/master/12-asus-uefi-bios.png)

BIOS Dell

![13 - BIOS Dell](https://github.com/Programa00/VM-Xubuntu/blob/master/13-dell.png)

Depois dessa opção estar ativada salve as alterações e reinicie seu computador para que as mudanças surtam efeito.

Se durante a sua instalação você tiver um BIOS diferente, faça uma captura de tela para que eu possa completar esta lista.


### Feito com :heart: por Erica Suguimoto (bot)

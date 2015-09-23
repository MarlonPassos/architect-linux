![logo](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/logo.png)


 
O [Architect](http://architectlinux.boardhost.com/index.php) Linux é um projeto que visa transformar a instalação do [Arch Linux](https://www.archlinux.org/) em algo intuitivo, automático e totalmente gráfico, deixando todo o processo de instalação do Arch extremamente simples. 


Architect – [Download-iso](http://sourceforge.net/projects/architect-linux/files/latest/download)  

###Instalando Architect Linux:

```
A instalação foi realizada em uma máquina Virtual com as seguintes configurações: 
Disco: 8 GB
Memória RAM: 700 MB
```
VirtualBox-[Download](https://www.virtualbox.org/wiki/Downloads)


Se for instalar no seu computador,  baixe a imagem ISO, crie um pendrive inicializável ou queime a imagem em um CD. Dependendo da configuração de sua BIOS, talvez você precise alterá-la para permitir que seu computador procure primeiro pelo pendrive/CD.


####Siga o passo a passo abaixo:




Ao efetuar o boot você será levado para está tela. 

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch01.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch02.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch03.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch05.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch06.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch07.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch08.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch09.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch10.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch11.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch12.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch13.png)

` Salve com Ctrl+o | Ctrl+x  para sair `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch14.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch15.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch16.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch17.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch18.png)

` Selecione o hd onde será instalado o sistema`

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch19.png)

` Nesse caso só iremos criar duas partições uma para o sistema (/) e a outra para o swap`

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch20.png)

` Selecione DOS (padrão para MBR)...`

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch21.png)

` Selecione a opção Nova `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch22.png)

` Criando a partição swap, neste caso o tamanho é de 700M, normalmente se utiliza o dobro do tamanho da memória RAM `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch23.png)

` Selecione a opção Primária `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch24.png)

` Selecione a opção Tipo `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch25.png)

` Selecione a opção 82 `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch26.png)

` Selecione o espaço livre / opção Nova `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch27.png)

` Criando a partição raiz (/), todo o espaço disponivel `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch28.png)

` Selecione a opção Primária `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch29.png)

` Marque a partição do sistema como inicializável `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch30.png)

` Agora grave as alterações na opção 'Gravar', escreva 'sim' para aceitar e depois saia da tela de particionamento com a opção 'Sair' `



![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch33.png)

` Pule essa opção... `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch34.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch35.png)

` Selecione sda2 para ROOT/partição raiz (/) `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch36.png)

` Selecione Ext4 `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch37.png)

` Selecione a particção SWAP sda1 `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch38.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch39.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch40.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch41.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch42.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch43.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch44.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch45.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch46.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch47.png)

` Selecione sim para instalar Grub no /dev/sda `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch48.png)

` Pule essa opção, o sistema irá instalar driver correto... `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch49.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch50.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch51.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch52.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch53.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch54.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch55.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch56.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch57.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch58.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch59.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch60.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch61.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch62.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch63.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch64.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch65.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch66.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch67.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch68.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch69.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch70.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch71.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch73.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch74.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch75.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch76.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch77.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch78.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch79.png)

` Para Arch Linux temos vários ambientes gráficos, entre eles, o KDE, Gnome, BlackBox, Xfce, *Lxde, etc.. `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch80.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch81.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch82.png)

` Independente do ambiente selecione SIM... `

![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch83.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch84.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch85.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch86.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch87.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch88.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch89.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch90.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch91.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch92.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch93.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch94.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch98.png)
![arch](https://github.com/MarlonPassos/architect-linux/blob/master/screenshot/arch99.png)



#####[Configurações básicas pós instalação](https://github.com/MarlonPassos/architect-linux/blob/master/ArchLinuxNotes.txt).


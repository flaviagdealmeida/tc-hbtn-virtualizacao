# Apresente uma solução de como deve ser a criação de uma máquina virtual no Hyper-V.

# Habilitar o uso do hyper-v
    - antes de Instalar o Hyper-V execute o Windows Update para garantir que sua máquina está totalmente atualizada.
    - abra o Server Manager do Windows Server 2008 R2
    - clique em Roles e Add Roles
    - na tela Before you Begin clique em Next
    - na tela Select Server Role marque Hyper-V e clique em Next
    - clique em Next
    - na tela Create Virtual Networks Selecione o adaptador de rede que será usada para as máquinas virtuais e clique em Next
    - para finalizar clique em Install
    - a máquina precisa ser reiniciada para que o processo seja concluído. Clique em Close

============================================================================================================
# Demonstre de uma maneira simples porque essa prática é considerada um hipervisor do Tipo 2.
    - A VM rodará sobre um SO host, por isso é considerada do hypervisor tipo 2


============================================================================================================
# Realize uma nova pesquisa para configuração do Servidor Físico, levando em consideração que o artigo é de 2011, qual a configuração ideal para um servidor suportar três máquinas virtuais dos mesmos tipos apresentados no artigo.
    - Acredito que o hardware apresentado no artigo precise de upgrade, pois para ter uma boa performance de acordo com as funcionalidades exercidas para cada novo servidor, seria necessaria a readequação do tamanho da memoria RAM e tambem do disco rígido.

# CCNA - HANDS ON - LAB 1 | DHCPv4 TYPES

![LAB DHCP TYES](https://user-images.githubusercontent.com/71329433/190261076-a2f9c560-144f-47e5-bc52-e9023dd543ae.png)



>Bem vindo novamente, fico feliz em tê-lo nesse ambiente. Através do Lab.DHCPv4.Types vou lhe mostrar exemplos das configurações, e documentações para endereços IPv4. Assim facilitando, a gerência, alocações dos endereços, com tudo  isso facilitando a sumarização de rotas e engenharia do tráfego de redes. 

### Ajustes e melhorias estão por vir 🚧 EM CONSTRUÇÃO 🚧

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

# 💡 Projects
- [ ] Tarefa 1 - Instalado o EVE-NG  e as imagens dos roteadores que serão utilizadas neste conteúdo.
- Link Aqui >

- [ ] Tarefa 2 - Planejamento dos endereços IPv4 e desenho da topologia.
- Link Aqui >

- [ ] Tarefa 3 - Configuração Básica dos Roteadores e SW's layer 3. 
- Link Aqui >

- [ ] Tarefa 4 - Estabelecendo conectividade para Internet, RTR-OPERADORA e RTR-MATRIZ.
- Link Aqui >

- [ ] Tarefa 5 - Configurando os diversos tipos de DHCPv4 em diferetes Unidades (SOHO)
- Link Aqui >

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:
<!---Estes são apenas requisitos de exemplo.o--->
* Você tem uma máquina `<Windows >`. Indique qual sistema operacional é compatível / não compatível.
* Você instalou a versão mais recente de `<Windows>`

Requisitos recomendados de Hardware

	1.1. Processador: 4 ou mais núcleos lógicos - série AMD-V / RVI ou Intel VT-X / EPT
	1.2. Memória RAM: 8 Gb (mínimo 4Gb).
	1.3. DISCO: 50Gb
	
Referência: https://www.eve-ng.net/documentation/installation/system-requirement

Dicas
Componentes da Instalação
O EVE-NG é uma máquina virtual Linux.
O acesso do usuário ao EVE-NG é via navegador Web (Chrome, Firefox., etc).
É recomendado, no entanto, a instalação do EVE Client para integração de outros programas ao browser, como o Putty e Wireshark.

Referência : https://www.eve-ng.net/index.php/download/


## 🚀 Instalando <EVE - NG>

Para instalar o <EVE-NG>, siga estas etapas:

1 ) Instalação da Máquina Virtual

	1.1. Crie um login em my.vmware.com
  
	1.2. Baixe e instale o seguinte programa:
  
VMWare Workstation Player

	2.3. Baixe a máquina virtual (VM) do EVE-NG OVA
  
  Referência: https://drive.google.com/drive/folders/1NlhBCZT75bycqZVa4XS6DwA4sc0FmnBp?usp=sharing
  Senha descompactação: githuboliveied
	
	2.4. Adicione a VM do EVE-NG ao VMWare Workstation
  
Abra o VMWare Player
- Clique "Open a Virtual Machine"
- Localize e abra o arquivo EVE Community VM.ova e clique "Import"
-Depois edite as configurações da máquina virtual '<eve-ng OVA>'.

![eve-ng config](https://user-images.githubusercontent.com/71329433/190730117-ed81f67e-30c5-474c-b9a0-5bf3ca446c73.png)

	2.5. Pode iniciar agora a Máquina Virtual

Se tudo correr bem, aparecerá uma tela com as seguintes informações:

![eve-ng tela login](https://user-images.githubusercontent.com/71329433/190728602-9aedc18b-ef40-45f5-ac90-e76b44e3470c.png)

Acesso ao Eve-ng Community - CLI
user: root
Password: eve

Acesso ao Eve-ng Community - WEB
user: Admin
Password: eve

## ☕ Usando <nome_do_projeto>

Para usar <nome_do_projeto>, siga estas etapas:

```
<exemplo_de_uso>
```

Adicione comandos de execução e exemplos que você acha que os usuários acharão úteis. Fornece uma referência de opções para pontos de bônus!

## 📫 Contribuindo para <nome_do_projeto>
<!---Se o seu README for longo ou se você tiver algum processo ou etapas específicas que deseja que os contribuidores sigam, considere a criação de um arquivo CONTRIBUTING.md separado--->
Para contribuir com <nome_do_projeto>, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/71329433?s=400&u=33ea05db0ac10b145e9897248250db20b3eecdea&v=4" width="100px;" alt="Foto do Evandro Duarte de Oliveira no GitHub"/><br>
        <sub>
          <b>OliveiED</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://s2.glbimg.com/FUcw2usZfSTL6yCCGj3L3v3SpJ8=/smart/e.glbimg.com/og/ed/f/original/2019/04/25/zuckerberg_podcast.jpg" width="100px;" alt="Foto do Mark Zuckerberg"/><br>
        <sub>
          <b>Mark Zuckerberg</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Steve Jobs</b>
        </sub>
      </a>
    </td>
  </tr>
</table>


## 😄 Seja um dos contribuidores<br>

Quer fazer parte desse projeto? Clique [AQUI](CONTRIBUTING.md) e leia como contribuir.

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](#CCNA - HANDS ON - LAB 1 | DHCP TYPES)<br>

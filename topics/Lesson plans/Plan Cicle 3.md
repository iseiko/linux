# Ciclo III - Advanced

<h3 align='center'>27. Compilação do Kernel Linux</h3>
- Código-fonte;
- Configuração do Kernel;
- Selecionando drivers e módulos essenciais;
- Compilação: `make`, `make modules`, `make modules_install`;
- Instalação: `vmlinuz`, `System.map`, `/boot`;
- Criando módulos compiláveis;
- Debugging de problemas de compilação;
- Otimização.

<h3 align='center'>28. Criação de um Sistema de Arquivos Raiz</h3>
- Diretórios e binários essenciais;
- Dependências;
- Bibliotecas compartilhadas necessárias;
- Criação de device nodes com `mknod`;
- Configuração mínima: `/etc/passwd`, `/etc/group`, `/etc/hostname`, `/etc/fstab`;
- Criação do arquivo de configuração do shell: `/etc/profile`, `.bashrc`;
- `chroot`;
- `tar`, `cpio`.

<h3 align='center'>29. Bootloader e Inicialização Customizada</h3>
- GRUB;
- Entradas de boot customizadas;
- Parâmetros de kernel;
- initramfs customizado;
- Scripts de inicialização;
- Ordem de boot;
- Troubleshooting de boot;
- U-Boot.

<h3 align='center'>30. Integração de Ferramentas Essenciais</h3>
- Compilando ferramentas: `busybox`;
- Compilando shells alternativos: `dash`, `zsh`;
- Compilando editores: `nano`, `vim`;
- Compilando ferramentas de rede: `iproute2`, `openssh`, `curl`, `wget`;
- Compilando ferramentas de sistema: `htop`, `tmux`, `screen`;
- Compilando ferramentas de desenvolvimento: `gcc`, `make`, `git`;
- Gerenciando dependências entre ferramentas;
- Otimização;
- Criando symlinks para compatibilidade.

<h3 align='center'>31. Configuração de Rede e Serviços Básicos</h3>
- Configuração de rede: interfaces, IP, DNS, gateway;
- Arquivos de configuração;
- Ferramentas de rede;
- DHCP vs. IP estático;
- Configuração de SSH;
- Firewall básico;
- Serviços essenciais;
- Sincronização de tempo;
- DNS local.

<h3 align='center'>32. Gerenciamento de Pacotes Customizado</h3>
- Escolhendo um gerenciador;
- Como organizar pacotes;
- Criando pacotes;
- Assinando pacotes;
- Repositório local;
- Configurando o gerenciador de pacotes na distribuição;
- Automatizando builds;
- Versionamento e dependências;
- Atualizações.

<h3 align='center'>33. Otimização, Segurança e Finalização</h3>
- Auditoria de segurança;
- Hardening;
- Otimização de performance;
- Redução de tamanho;
- Testes;
- Documentação;
- Instaladores;
- Imagens;
- Versionamento.

<h3 align='center'>34. Distribuição e Deployment</h3>
- Hospedando a distribuição;
- Criando checksums e assinaturas;
- Documentação;
- Comunidade;
- Feedback e iteração;
- Contribuições;
- Licença;
- Marketing;
- Sustentabilidade.

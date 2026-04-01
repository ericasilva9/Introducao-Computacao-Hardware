# Introducao-Computacao-Hardware #
## Sistema Operacional Windows ##

**Sistema Operacional estudado:**Microsoft Windows

**ALUNA:** Erica Pereira Da Silva
**Prof.ª:** Kadidja Valéria

---

## Histórico e Evolução ##

A Microsoft foi fundada em 1975 por Bill Gates e Paul Allen. O Windows 1.0 chegou em 1985 como a primeira interface gráfica sobre o MS-DOS. O primeiro grande sucesso comercial foi o Windows 3.0 (1990), com 10 milhões de cópias em 18 meses. O Windows 95 revolucionou a computação pessoal ao introduzir o Menu Iniciar e a barra de tarefas. O Windows XP (2001) tornou-se o mais estável e longevo da história, utilizado por mais de 13 anos. O Vista (2007) foi um fracasso por ser pesado e instável, enquanto o Windows 7 (2009) restaurou a reputação da empresa. O Windows 11 (2021) trouxe integração com IA via Copilot e hoje detém cerca de 73% do mercado global de SO para desktop.

## Arquitetura do Kernel ##

O Windows utiliza o **Windows NT Kernel**, de arquitetura **híbrida** — combinando características do modelo monolítico (serviços como drivers e gerenciamento de memória no modo kernel, para alto desempenho) com o micronúcleo (organização em camadas e modularidade).

## Segurança e Isolamento ##

O sistema implementa quatro camadas de proteção: separação entre modo usuário e modo kernel, Controle de Conta de Usuário (UAC), isolamento de processos e sistema de permissões NTFS para controle de acesso a arquivos.

## Ecossistema e Casos de Uso ##

O Windows domina o segmento de desktops e laptops, é forte em servidores corporativos via Windows Server e Azure, possui presença em dispositivos embarcados com Windows IoT, e perdeu o mercado mobile após a descontinuação do Windows Phone. Na prática, é usado por gamers (DirectX 12), criadores de conteúdo (Adobe CC), estudantes (Microsoft 365), hospitais, datacenters e até agências espaciais como a NASA.

## Vantagens e Limitações ##

Entre as vantagens destacam: interface intuitiva, segurança nativa com Windows Defender e amplo suporte de hardware, como limitações custo de licença, fragmentação entre versões, ecossistema fechado (lock-in) e curva de aprendizado para recursos avançados.

## Reflexão ##

O Windows é um caso de estudo rico em engenharia de software: mostra como decisões arquiteturais (kernel híbrido), estratégia de mercado e experiência do usuário moldam décadas de evolução tecnológica. O fracasso do Vista e o sucesso do XP e do 7 evidenciam que desempenho e estabilidade são requisitos não funcionais críticos em sistemas operacionais.

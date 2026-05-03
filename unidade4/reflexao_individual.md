# Reflexão Individual – Aula 11

**Nome:** Erica Pereira Da Silva 
**Matrícula:** 22611949 
**Disciplina:** Introdução à computação  

---

## "Qual topologia seria mais adequada para a rede da minha residência e por quê?"

### Análise das Topologias

A **topologia em barramento** foi amplamente utilizada nas primeiras redes Ethernet, com um único cabo coaxial compartilhado por todos os dispositivos. No ambiente residencial atual, ela seria inadequada: qualquer falha no cabo central derruba toda a rede, o tráfego é compartilhado (gerando colisões), e a tecnologia está praticamente obsoleta.

A **topologia em anel** utiliza um token circulante para controlar o acesso ao meio. Embora elimine colisões, uma falha em qualquer ponto do anel pode comprometer a comunicação de todos os dispositivos. Além disso, a adição de novos dispositivos exige interrupção temporária da rede, o que a torna pouco prática para o uso doméstico.

A **topologia em malha** garante alta redundância cada dispositivo pode se comunicar com qualquer outro por múltiplos caminhos. Contudo, seu custo de implementação é elevado e a complexidade de configuração é incompatível com o ambiente residencial, sendo mais indicada para infraestruturas críticas como backbones de operadoras e datacenters.

### Topologia Recomendada: Estrela

A **topologia em estrela** é, sem dúvida, a mais adequada para uma rede residencial. Nela, todos os dispositivos computadores, notebooks, smart TVs, consoles e impressoras conectam-se a um único ponto central, que em uma residência moderna é o **roteador Wi-Fi** (geralmente com switch integrado).

**Razões que justificam essa escolha:**

1. **Isolamento de falhas:** Se um cabo ou dispositivo falhar, apenas aquele host é afetado. Os demais continuam operando normalmente, ao contrário do barramento (falha central derruba tudo) e do anel (falha interrompe o circuito).

2. **Facilidade de instalação e manutenção:** Adicionar ou remover um dispositivo basta conectá-lo ou desconectá-lo do roteador/switch, sem precisar interromper a rede.

3. **Custo acessível:** Roteadores domésticos com switch integrado de 4 a 8 portas são baratos e amplamente disponíveis. A topologia estrela é, de longe, a mais comum no mercado consumidor.

4. **Desempenho:** Cada dispositivo possui sua própria conexão dedicada ao ponto central. Ao contrário do barramento, não há disputa pelo meio físico no segmento de cada host, eliminando colisões nas conexões com fio.

5. **Suporte a tecnologias atuais:** Tanto o cabeamento (Ethernet UTP Cat6) quanto o Wi-Fi (802.11ax / Wi-Fi 6) operam na topologia estrela o roteador é o ponto central tanto para conexões com fio quanto para conexões sem fio.

### Cenário Prático

Na minha residência, a rede já opera em topologia estrela: o roteador Wi-Fi 6 recebe a fibra óptica (FTTH) do provedor e distribui o acesso à internet por Wi-Fi (5 GHz) para notebooks e smartphones, e por Ethernet (UTP Cat6) para o computador e a smart TV que exigem conexão mais estável e rápida.

### Conclusão

A topologia estrela alia simplicidade, confiabilidade e custo-benefício, sendo a escolha natural para redes residenciais. Sua prevalência no mercado refletida em praticamente todo roteador doméstico disponível confirma sua adequação para esse contexto. As demais topologias, embora relevantes para cenários específicos (corporativos, industriais ou históricos), não oferecem vantagens práticas para o ambiente doméstico.

---

**Referência:**  
TANENBAUM, A. S.; FEAMSTER, N.; WETHERALL, D. J. *Redes de Computadores*. 6. ed. São Paulo: Bookman, 2021.

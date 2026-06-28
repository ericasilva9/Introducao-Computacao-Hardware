# Filme: A REDE SOCIAL
# Aula 14 – Segurança da Informação: Conceitos, Atributos e Ameaças

## Descrição do Trabalho
Este documento reúne a entrega completa da atividade prática de Laboratório de Informática referente à Aula 14. O conteúdo aborda os conceitos fundamentais de Segurança da Informação, ameaças e vulnerabilidades, um estudo de cenário focado no filme A Rede Social (The Social Network) e uma reflexão individual sobre o papel do fator humano.

---

## 1. Conceitos Fundamentais de Segurança da Informação

### Definição (ISO/IEC 27000:2018)
A Segurança da Informação é definida como a preservação da confidencialidade, integridade e disponibilidade da informação. Além disso, outras propriedades, como autenticidade, responsabilidade (accountability), não repúdio e confiabilidade, também podem estar envolvidas. O objetivo é proteger os dados contra acessos não autorizados, modificações ilícitas ou indisponibilidade de sistemas.

### Atributos Principais (A Tríade CID + Privacidade)

* *Confidencialidade:* É a garantia de que a informação só será acessível por pessoas, entidades ou processos autorizados. É o princípio do sigilo (ex: senhas fortes, criptografia).
* *Integridade:* Refere-se à salvaguarda da exatidão e da completude da informação e dos métodos de processamento. Garante que os dados não foram alterados de forma indevida ou acidental (ex: controle de versão, hashes criptográficos).
* *Disponibilidade:* É a garantia de que a informação e os sistemas estarão acessíveis e utilizáveis sempre que uma entidade autorizada necessitar (ex: backups, sistemas redundantes contra quedas).
* *Privacidade:* É o direito de um indivíduo de controlar como suas informações pessoais (nome, fotos, dados bancários, hábitos) são coletadas, armazenadas, processadas e compartilhadas. Vai além da confidencialidade, pois envolve consentimento e a legislação aplicável (como LGPD e GDPR).

---

## 2. Ameaças e Vulnerabilidades

### Ameaças Digitais Comuns
* *Phishing:* Técnica de fraude online onde o atacante se passa por uma entidade confiável (por e-mail, SMS ou sites falsos) para enganar a vítima e roubar dados sensíveis, como senhas e números de cartão de crédito.
* *Malware (Software Malicioso):* Termo genérico para qualquer software criado para causar danos ou explorar sistemas. Inclui vírus, trojans (cavalos de Troia), spywares (espiões) e ransomwares (sequestro de dados mediante resgate).
* *Engenharia Social:* É a arte de manipular psicologicamente as pessoas para que executem ações ou divulguem informações confidenciais. Baseia-se na ingenuidade, medo ou urgência do usuário, sem necessariamente usar ferramentas técnicas.

### Vulnerabilidades Técnicas e Humanas
* *Vulnerabilidades Técnicas:* São falhas no design, implementação ou configuração de softwares e hardwares. Exemplos incluem: sistemas operacionais desatualizados (sem patch de segurança), portas de rede abertas indevidamente, e bancos de dados sem criptografia.
* *Vulnerabilidades Humanas:* Referem-se ao comportamento dos usuários. Exemplos incluem: uso de senhas fracas ou repetidas, o hábito de anotar senhas em locais inseguros, clicar em links suspeitos, ou a falta de treinamento básico em segurança.

### Impactos Potenciais
A exploração dessas vulnerabilidades por ameaças pode causar:
* *Impacto Financeiro:* Roubo de fundos, multas regulatórias, perda de contratos e pagamento de resgates.
* *Impacto Reputacional:* Perda de confiança por parte de clientes e parceiros devido ao vazamento de dados.
* *Impacto Operacional:* Paralisação das atividades da empresa pela indisponibilidade de sistemas vitais.
* *Impactos Legais:* Processos judiciais por quebra de leis de privacidade (como a LGPD/GDPR).

---

## 3. Estudo de Cenário: Comentários sobre o filme "A Rede Social" (Opção B)

### O Filme e a Retratação de Ameaças Digitais
O filme A Rede Social (The Social Network, 2010) narra a fundação do Facebook por Mark Zuckerberg. Embora não seja um filme clássico de "hackers e invasões militares", ele ilustra perfeitamente as bases de incidentes de segurança e privacidade no desenvolvimento de software e plataformas corporativas.

Logo no início do filme, Zuckerberg cria o "Facemash". Para isso, ele realiza *ataques cibernéticos reais: invade (hackeia) os diretórios de alunos (*facebooks) de diversas casas da Universidade de Harvard. Ele burla sistemas de segurança rudimentares da época (vulnerabilidades técnicas), faz scraping (raspagem de dados) e baixa fotos de alunas sem qualquer consentimento.

### Conceitos de Segurança da Informação Presentes
* *Quebra de Confidencialidade e Privacidade:* Ocorre claramente quando dados (fotos) restritos aos diretórios universitários são expostos publicamente no Facemash sem autorização das alunas.
* *Indisponibilidade (Ataque de DoS Acidental):* Quando o Facemash é lançado, ele viraliza rapidamente. O alto volume de tráfego de alunos acessando o site derruba a rede de Harvard. Este é o princípio de um ataque de Negação de Serviço (Denial of Service - DoS), onde o servidor não suporta a carga de requisições e fica indisponível para uso legítimo.
* *Propriedade Intelectual (Integridade do negócio):* O conflito com os irmãos Winklevoss levanta a questão da segurança da informação em nível corporativo: a proteção de ideias e a confidencialidade de projetos em fase de desenvolvimento.

### Reflexão Crítica: Ficção x Realidade
A realidade retratada no filme reflete a cultura do Vale do Silício de "move fast and break things" (mova-se rápido e quebre as coisas). Na ficção baseada em fatos, a preocupação com a segurança e a privacidade é nula frente ao desejo de escalar o sistema e ganhar popularidade. 

Trazendo para a realidade atual, esse comportamento explica por que grandes corporações de tecnologia hoje enfrentam tantos problemas judiciais e vazamentos massivos de dados. O filme nos ensina, por meio de um cenário real, que quando sistemas são construídos ignorando os princípios de Security by Design (Segurança desde a concepção) e Privacy by Design, o impacto a longo prazo afeta a privacidade de bilhões de usuários globalmente.

---

## 4. Reflexão Individual

### "Por que o fator humano é considerado o elo mais frágil da segurança da informação?"
Enquanto os sistemas tecnológicos operam sob regras lógicas e previsíveis, os seres humanos são guiados por emoções, hábitos e cansaço. Por isso, o fator humano é o elo mais frágil da segurança: é muito mais fácil e barato para um criminoso enganar uma pessoa do que quebrar uma criptografia complexa.
 Os atacantes utilizam a **engenharia social** e o *phishing* para explorar gatilhos como a curiosidade, a pressa ou o medo, manipulando funcionários a clicarem em links maliciosos ou revelarem credenciais. Além disso, falhas cotidianas como o uso de senhas fracas, o compartilhamento de acessos e a falta de atenção anulam a eficácia de firewalls e softwares caros.
 O filme *A Rede Social* exemplifica isso: os sistemas de Harvard foram expostos não por um software externo ultra-avançado, mas pelas ações de um usuário interno que explorou as brechas físicas e lógicas do campus. Portanto, a tecnologia sozinha não basta; a verdadeira segurança exige a conscientização e o treinamento contínuo das pessoas.

# Referência
[A REDE SOCIAL. In: "Wikipédia: a enciclopédia livre. Disponível em: Wikipédia" – A Rede Social. Acesso em: 25 maio 2026."]

# Caderno de Estudos: Cibersegurança

## 🎯 Contexto e Objetivos

### Contexto
Este caderno temático foi desenvolvido como parte do Desafio de Projeto da **DIO**, utilizando a ferramenta **NotebookLM** da Google para apoiar a curadoria, síntese e estruturação do conhecimento. O tema central escolhido foi **Cibersegurança**, abordando desde os pilares fundamentais de segurança da informação até o panorama atual de ameaças (incluindo riscos associados à IA generativa e infraestruturas críticas).

### Objetivos de Estudo
O principal objetivo deste projeto é estabelecer um plano de estudos estruturado para orientar minha transição de carreira, **saindo do nível iniciante ("do zero") rumo à atuação profissional em Cibersegurança**. 

Para alcançar essa meta, este caderno busca atingir os seguintes objetivos específicos:
* **Compreensão Conceitual:** Dominar os pilares essenciais da segurança da informação (Tríade CIA, superfície de ataque e higiene digital).
* **Mapeamento de Ameaças e Defesas:** Entender o funcionamento dos principais vetores de ataque modernos (Phishing, Ransomware, Deepfakes, MitM) e as estratégias defensivas aplicáveis (MFA, VPN, Defesa em Profundidade, Red/Blue Team).
* **Domínio do Vocabulário Técnico:** Construir um glossário prático e categorizado para superar a barreira dos jargões e siglas em inglês da área.
* **Engenharia de Prompts:** Praticar a formulação de comandos estratégicos no NotebookLM para acelerar o aprendizado, realizar simulações de incidentes e gerar rotinas de revisão contínua.

## 📚 Curadoria de Fontes
Foram utilizados os seguintes materiais como base de conhecimento (inseridos no NotebookLM):
1. [Principais ameaças de segurança em 2026 e impacto no Brasil](https://ibsec.com.br/principais-ameacas-de-seguranca-em-2026-e-impacto-no-brasil/)
2. [The Ultimate Cybersecurity Roadmap for 2026: From Beginner to Security Professional](https://dev.to/samsalatini/the-ultimate-cybersecurity-roadmap-for-2026-from-beginner-to-security-professional-pd2)
3. [Cibersegurança do Zero à Prática](https://app.santanderopenacademy.com/pt-BR/program/ciberseguranca-do-zero-a-pratica)

## 🧠 Engenharia de Prompts e "Cicatrizes"
Durante o estudo no NotebookLM, os seguintes testes de prompts foram realizados:

* **Prompt Estratégico 1:** *"Pode me explicar, detalhadamente, o que é cibersegurança?"*
  * **Variação testada:** *"Pode explicar, com exemplos práticos, o que é cibersegurança?"*
  * **Dificuldades (Troubleshooting):** A IA inicialmente cumpriu bem meu pedido, explicando de forma simples e precisa o que é a cibersegurança, mas senti falta de exemplos, e portanto refinei para o segundo prompt.
  * **Resposta obtida e Referências:** A **cibersegurança** (ou segurança cibernética) é o conjunto de estudos, técnicas e práticas dedicado a proteger computadores, servidores, dispositivos móveis, redes e dados contra roubos, danos, invasões ou acessos não autorizados [1]. O seu objetivo fundamental é preservar a **Tríade CIA**: a confidencialidade, a integridade e a disponibilidade dos recursos digitais [2]. Para entender como ela funciona no dia a dia, vale analisar alguns **exemplos práticos de ameaças e de como a cibersegurança atua para combatê-las**.

* **Prompt Estratégico 2:** *"Agora pode me listar os termos fundamentais para entender sobre cibersegurança, e explica-los brevemente?"*
  * **Variação testada:** *"Muitas vezes, quando leio um artigo, página ou vejo um video sobre cibersegurança fico um pouco perdida devido aos termos usados da área. Pode me dizer e explicar eles?"*
  * **Dificuldades (Troubleshooting):** No primeiro exemplo ela pegou vários termos soltos e voltou me explicando. Refinando para o segundo, ela me trouxe uma resposta bem mais completa, explicando detalhadamente os conceitos, criando o que ela disse ser o **dicionário essencial de cibersegurança**.
  * **Resposta obtida e Referências:** É muito comum sentir esse estranhamento no início, pois a cibersegurança utiliza muitos jargões técnicos em inglês e siglas específicas [1]. Para ajudar na sua leitura de artigos, relatórios e vídeos, apresento este **dicionário essencial de cibersegurança** dividido por áreas temáticas.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados do Assunto

**1. Engenharia Social e Phishing**  
A **engenharia social** ocorre quando criminosos manipulam a confiança e o comportamento humano para obter informações confidenciais sem necessidade de violência física [4].
* **Como a cibersegurança protege:** Através do uso de **filtros de e-mail e anti-phishing**, implementação de **Autenticação Multifator (MFA)** e **treinamentos contínuos de conscientização** para que os usuários aprendam a identificar mensagens e abordagens suspeitas [9].

**2. Riscos em Redes Wi-Fi Públicas**  
O uso de redes sem fio abertas e públicas em locais como cafés, aeroportos ou shoppings expõe o tráfego de dados a interceptações [12].
* **Como a cibersegurança protege:** Através do uso de **VPNs (Redes Privadas Virtuais)** para criptografar a comunicação, **antivírus/anti-malware** atualizados no dispositivo e navegação exclusiva em sites com protocolo seguro HTTPS [9].

**3. Ransomware (Sequestro de Dados)**  
O *ransomware* é um tipo de software malicioso projetado para bloquear ou criptografar os arquivos de um dispositivo, exigindo o pagamento de um resgate para liberar o acesso [18][19].
* **Como a cibersegurança protege:** Utilizando a **regra de backup 3-2-1** (manter 3 cópias de dados em 2 mídias diferentes, sendo 1 cópia offline/isolada), **ferramentas de proteção de endpoint/antivírus** e gestão rigorosa de atualizações para fechar brechas de software [15].

**4. Golpes com Inteligência Artificial e Deepfakes**  
A evolução da inteligência artificial permitiu que golpistas automatizem e personalizem ataques em grande escala [24].
* **Como a cibersegurança protege:** Estabelecendo **processos formais de validação** (como confirmação por um segundo canal de comunicação ou uso de palavras-chave familiares/corporativas) e treinando equipes e indivíduos para checar o contexto antes de tomar atitudes sob pressão [27][28].

**5. Proteção de Infraestruturas Críticas e Indústrias**  
A cibersegurança também se aplica à proteção de sistemas físicos que controlam serviços essenciais para a sociedade, como usinas de energia, redes de água e transporte [29][30].
* **Como a cibersegurança protege:** Aplicando a **segmentação rigorosa de redes**, uso de **firewalls industriais**, controle de acesso físico/lógico e monitoramento contínuo de anomalias operacionais em tempo real [9].

---

### 2. Glossário de Conceitos

#### 2.1. Conceitos Fundamentais de Segurança
* **Tríade CIA**: Os três pilares da segurança — **Confidencialidade** (evitar acesso não autorizado), **Integridade** (garantir dados exatos e sem alterações) e **Disponibilidade** (manter o sistema no ar para uso legítimo) [2][3].
* **Ativo (Asset)**: Qualquer elemento valioso da organização ou pessoa, incluindo dados, hardware, softwares, redes, instalações ou indivíduos [4][5].
* **Superfície de Ataque (Attack Surface)**: A soma de todos os pontos de entrada, portas e sistemas expostos onde um invasor pode tentar encontrar uma brecha [6][7].
* **Higiene Digital (Cyber Hygiene)**: O conjunto de práticas e rotinas diárias simples (como atualizar softwares e usar senhas fortes) para reduzir os riscos digitais [8][9].

#### 2.2. Ameaças, Golpes e Softwares Maliciosos
* **Malware**: Nome genérico para qualquer código ou programa projetado para causar danos ou infectar dispositivos [10].
* **Ransomware**: Tipo de malware que bloqueia ou criptografa arquivos e sistemas, exigindo o pagamento de um resgate para liberar o acesso [11].
* **Engenharia Social**: Ação de manipular psicologicamente ou enganar a vítima para que ela entregue informações confidenciais voluntariamente [14][15].
* **Phishing, Smishing e Vishing**: Golpes de engenharia social aplicados por **e-mail** (phishing) [16], **SMS/mensagens de texto** (smishing) [17] ou **chamadas de voz** (vishing) [17].
* **Spearphishing**: Uma campanha de phishing hiper-direcionada e personalizada para uma pessoa ou organização específica [18].
* **Deepfake**: Conteúdo de áudio, vídeo ou imagem adulterado ou clonado por inteligência artificial para simular pessoas reais em fraudes [19][20].
* **Vulnerabilidade Zero-Day (Dia Zero)**: Uma falha de segurança recém-descoberta para a qual o fabricante ainda não desenvolveu uma correção ou atualização [21][22].
* **Ataque DoS / DDoS**: Ataque de negação de serviço que envia tráfego massivo a um sistema ou servidor até sobrecarregá-lo e tirá-lo do ar [23].
* **Man-in-the-Middle (MitM)**: Ataque em que o invasor se insere secretamente entre duas partes comunicantes para interceptar ou alterar os dados enviados [24][25].
* **Keylogger**: Software malicioso que grava secretamente tudo o que o usuário digita no teclado [15][26].
* **Backdoor**: Uma porta de acesso secreta criada ou mantida em um sistema para contornar as autenticações normais de segurança [27].
* **Shadow AI**: O uso de ferramentas de IA generativa por colaboradores sem autorização ou governança da equipe de TI [28].

#### 2.3. Falhas e Avaliações Técnicas
* **Vulnerabilidade**: Um ponto fraco no design, na implementação ou no controle operacional de um sistema [29].
* **Exploit**: Um código ou ferramenta criada especificamente para aproveitar uma vulnerabilidade [29].
* **CVE (Common Vulnerabilities and Exposures)**: Um dicionário público e padronizado que lista vulnerabilidades conhecidas mundialmente [29].
* **Pentest (Teste de Invasão)**: Uma simulação de ataque autorizada e controlada feita por profissionais para identificar brechas antes dos criminosos [30].
* **CTF (Capture The Flag)**: Competições e desafios em formato de quebra-cabeça técnico para treinar habilidades de invasão e defesa [33][34].

#### 2.4. Defesa, Operações e Arquitetura
* **Red Team & Blue Team**: O **Red Team** é a equipe ofensiva que simula ataques reais [35][36]; o **Blue Team** é a equipe defensiva que monitora, detecta e responde a incidentes [35][36].
* **SOC (Security Operations Center)**: O Centro de Operações de Segurança responsável pelo monitoramento contínuo da infraestrutura [37].
* **Firewall & WAF**: Dispositivos ou softwares que filtram o tráfego de rede e de aplicações web para bloquear conexões não autorizadas [15].
* **MFA / 2FA (Autenticação Multifator)**: Exigência de duas ou mais provas de identidade (como senha + código de aplicativo) para realizar login [41][42].
* **Privilégio Mínimo (Least Privilege)**: Princípio de conceder a cada usuário ou programa apenas os acessos estritamente necessários para sua função [43][44].
* **Defesa em Profundidade**: Estratégia de segurança disposta em múltiplas camadas sobrepostas [44][45].
* **Criptografia Pós-Quântica (Quantum-Safe)**: Novos algoritmos desenvolvidos para resistir ao poder de quebra da computação quântica [46][47].

#### 2.5. Governança e Regulamentação
* **NIST CSF**: A estrutura de segurança cibernética do Instituto Nacional de Padrões e Tecnologia dos EUA, organizada em seis funções: *Governar, Identificar, Proteger, Detectar, Responder e Recuperar* [4][48].
* **LGPD e ANPD**: A **Lei Geral de Proteção de Dados Pessoais** no Brasil [13][49] e a **Autoridade Nacional de Proteção de Dados**, órgão que fiscaliza o seu cumprimento [13][50].

---
  
### 3. Prompts Reutilizáveis
*(Comandos estratégicos prontos para apoiar futuras revisões, testes de conhecimento e simulações sobre o tema)*

#### 🧪 Testes de Conhecimento e Simulados
* *"Me faça 3 perguntas de múltipla escolha sobre os tipos de Malware citados no texto para testar meus conhecimentos."*
* *"Com base no material, crie 5 questões no estilo de provas de certificação de Cibersegurança (ex: CompTIA Security+) com gabarito comentado ao final."*
* *"Gere 10 flashcards no formato 'Pergunta em cima / Resposta oculta abaixo' focando nos termos do glossário."*

#### 🔍 Explicações e Comparações Técnicas
* *"Resuma os principais pontos de vulnerabilidade de uma rede Wi-Fi pública e como se proteger."*
* *"Monte uma tabela comparativa entre Red Team, Blue Team e Purple Team, destacando objetivos, ferramentas e atuação de cada um."*
* *"Explique a Tríade CIA usando uma analogia do dia a dia fora do mundo digital."*

#### 🛡️ Cenários Práticos e Resposta a Incidentes
* *"Simule um e-mail falso de Engenharia Social (Phishing) e me peça para identificar 3 'red flags' (sinais de alerta) na mensagem."*
* *"Crie um cenário hipotético de ataque por Ransomware em uma empresa e descreva o passo a passo da equipe de resposta a incidentes."*

#### 📋 Checklists e Aplicação Prática
* *"Crie um checklist de 5 passos práticos para eu aplicar hoje e melhorar a minha Higiene Digital nos meus dispositivos pessoais."*
* *"Quais são as melhores práticas para configurar Autenticação Multifator (MFA) de forma segura?"*

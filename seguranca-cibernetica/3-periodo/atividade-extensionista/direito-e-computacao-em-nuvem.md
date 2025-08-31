# **Direito e Computação em Nuvem (Cloud Computing): proteção e privacidade na era digital**    
**Feito por Thaianna A. Hirota**

### **O que é Cloud Computing?**   
A computação em nuvem se refere ao fornecimento de recursos computacionais, tais como: servidores, armazenamento de dados, banco de dados, redes, softwares e até IAs, pela internet e permite que usuários/empresas acessem e utilizem essas ferramentas sem a necessidade de manter uma infraestrutura física própria.   
Existem três modelos principais de computação em nuvem: **IaaS, PaaS e SaaS.**   

 
   - **IaaS:** significa Infraestrutura como Serviço. No caso, IaaS oferece a infraestrutura básica de computação, como servidores virtuais, redes, armazenamento e até sistemas operacionais, mas sem a necessidade de gerenciar hardware físico. O usuário pode utilizar e controlar os recursos de computação sem precisar se preocupar com a manutenção física dos servidores.
   
      Exemplo: AWS EC2, a Amazon Web Services. O EC2 significa Elastic Compute Cloud, em que a AWS oferece servidores virtuais em nuvem e os usuários podem configurar conforme suas necessidades e podem escolher o sistema operacional, a quantidade de CPU, memória, armazenamento que precisa pra rodar o aplicativo e tudo mais. Porém, vale ressaltar que, quanto melhores as configurações, mais caro será o plano contratado. Outro exemplo é a Microsoft Azure Virtual Machines que também é bastante utilizada, pois além de ter as funções similares a da AWS e Google Cloud, ela tem a vantagem de fazer a integração do Azure com outras ferramentas da Microsoft, como: Windows Server, Active Directory, SQL Server, etc.

      Situação de uso: Uma empresa precisa rodar uma aplicação de e-commerce e exige escalabilidade durante eventos de alto tráfego, como por exemplo, uma black friday. Ao utilizaar um IaaS, a empresa pode provisionar mais servidores virtuais durante o evento e reduzir sua infraestrutura assim que o tráfego voltar ao normal.

      Situação 2: hospedar um servidor de banco de dados ou rodar uma aplicação de grande escala.

      Situação 3: vamos voltar para cibersegurança que é o MEU foco principal. É muito comum contratar esse tipo de serviço em cibersegurança, pois as empresas tem total controle sobre a infraestrutura e podem implementar soluções de segurança em nível de rede, servidores e armazenamento. Isso é útil para empresas que precisam de proteção robusta em ambientes altamente dinâmicos e escaláveis. O que geralmente são contratados: Firewall como Serviço (FWaaS), em que os firewalls gerenciados na nuvem que protegem redes virtuais de tráfego indesejado e podem ser configurados para filtrar pacotes e impedir acessos não autorizados a dados e serviços hospedados na nuvem. Esse firewall é implementado diretamente na rede do provedor de nuvem e garante a filtragem de tráfego antes de entrar no servidor ou aplicação. Assim como ocorre a contratação de serviços de firewall, temos também os de controle de acesso e autenticação, backup e restauração de dados, detecção de ameaças e monitoramento, etc.
     
   - **PaaS:** significa Plataforma como Serviço. O PaaS oferece ferramentas de desenvolvimento e deployment de aplicativos, além da infraestrutura. Ele elimina a complexidade de gerenciar sistemas operacionais e infraestrutura, permitindo que os desenvolvedores se concentrem no desenvolvimento de aplicações sem se preocupar com o ambiente subjacente.

     Exemplo: Google App Engine (GAE): permite que os desenvolvedores criem e implantem aplicativos em uma plataforma escalável sem se preocupar com a administração de servidores, pois ele oferece suporte a várias linguagens de programação como python, java, go e php, e também cuida da infraestrutura por trás do aplicativo. Temmos também Heroku que é bem popular entre desenvolvedores de startups e projetos pequenos, ele oferece uma plataforma simples pra construir, implantar e escalar aplicações, além de abstrair a infraestrutura subjacente, permitindo que os desenvolvedores se concentrem nas funcionalidades do aplicativo. Outro exempli é o Microsoft Azure App Service que além dessas funcionalidades também tem a integração dele com as ferramentas do Azure.

     Situação de uso: ums equipe de desenvolvedores de software precisa criar uma aplicação web, sem se preocupar com a infraestrutura de servidores ou a escalabilidade. Ao usar o PaaS, como o Google App Engine, por exemplo, eles podem focar totalmente no código do aplicativo enquanto a plataforma cuida da escalabilidade automática conforme a demanda.

     Situação 2: além das empresas se concentrarem no desenvolvimento de suas aplicações sem se preocupar com a infraestrutura subjacente, elas também tem acesso a ferramentas que ajudam a integrar a cibersegurança no ciclo de vida de desenvolvimento de software. Exemplo: a segurança de aplicações em desenvolvimento (DevSecOps), temos Azure DevOps, GitHub Actions, em que essas ferramentas de integração contínua/entrega contínua (CI/CD), permitem integrar práticas de segurança diretamente no processo de desenvolvimento de software. Com a integração de ferramentas de segurança no pipeine de desenvolvimento, como testes de vulnerabilidade ou análise estática de código, as equipes podem detectar falhas de segurança logo no início do desenvolvimento, antes de colocar o código de produção.

   - **SaaS:** significa Software como Serviço. Esse é o modelo que basicamente está "pronto pra uso", pois os provedores oferecem aplicações completas, acessíveis via internet. Os usuários não precisam se preocupar com a infraestrutura ou desenvolvimento do aplicativo, basta usar a ferramenta. o SaaS é a solução hospedada e gerenciada pelo provedor.

     Exemplo: Google Workspace (antigo G Suite):  oferece várias ferramentas como Gmail, Google Drive, Google Docs, Sheets, entre outras, que são acessadas via navegador. Não há necessidade de instalação ou manutenção de software porque tudo está em nuvem. Outro exempli é o Microsoft qye tanbém conta com várias ferramentas de produtividades que são acessadas via web ou nativos no desktop, com a infraestrutura e gerenciamento totalmente feitos pela Microsoft. O Salesforce é uma das plataformas mais conhecidas de CRM (customer relationship management) em que a empresa oferece marketing, analytics, automaçao e gerenciamento de vendas que são totalmente acessíveis via navegador.

     Situação de uso: uma empresa de vendas pode usar o salesforce para gerenciar sua base de clientes e acompanhar as interações de vendas sem se preocupar com a instalação e manutenção do sistema. Tudo o que eles precisam é de um navegador de internet para acessar o software que é hospedado e gerido pelo provedor do Salesforce.

     Situação 2: em cibersegurança,  as soluções em SaaS geralmente se concentram em detecção de ameaças, gestão de identidades, proteção de endpoints e gerenciamento de riscos. No caso da proteção de endpoint, temos o CrowStrike, Zscaler, que monitoram dispositivos conectados a rede, como notebooks, smartphones, servidores, para pdetectar e previnir ataques de malware, ransomware e outras ameaças. Esse serviço atua diretamente no dispositivo ou rede, monitorando comportamentos suspeitos e bloqueando ameaças em tempo real.


Cada um desses modelos de nuvem oferecem soluções adaptadas a diferentes necessidades e níveis de controle. Se uma empresa precisa de controle total sobre sua infraestrutura e segurança, o **IaaS** é a melhor opção. Se o foco for desenvolvimento ágil de software com segurança integrada, o **PaaS** é o mais adequado. Já as soluções prontas e fáceis de usar, é mais indicado o **SaaS**, pois oferecem ferramentas poderosas já prontas.   
   
   
### **DESAFIOS PARA A PROTEÇÃO E PRIVACIDADE**   

A computação em nuvem envolve o armazenamento de dados sensíveis em servidores remotos e em diferentes setores. Os desafios para isso, incluem: proteção de dados pessoais, jurisdicionalidade, segurança cibernética e transparência e controle do usuário.   

   - Proteção de dados pessoais: como a nuvem centraliza grandes volumes de dados pessoais, incluindo informações financeiras, de saúde e comportamento dos usuários, todo o processo que inclui desde a coleta, armazenamento e tratamento, devem seguir normas legais que garante a privacidade e segurança.
   - Jurisdicionalidade: os dados são armazenados em servidores localizados em diferentes países, e surgem questões sobre qual legislação se aplica, especialmente quando há variação nas leis de proteção de dados entre os países, exemplo: GDPR da Europa vs a lei dos EUA.
   - Segurança cibernética: a proteção contra acessos não autorizados, vazamento de dados e ataques cibernéticos, como crackers, ransomwares, são um desafio constante. As empresas precisam implementar m edidas robustas de segurança, tais como: criptografia, autenticação multifatorial, controle de acesso, etc.
   - Transparência e controle do usuário: os usuários precisam entender como seus dados são tratados. A falta de clareza nas políticas de privacidade de provedores de nuvem podem gerar desconfiança.

   
### **REGULAÇÃO E LEGISLAÇÃO**   

  A legislação sobre proteção de dados está evoluindo em todo o mundo. O intuito é criar uma rede de proteção mais forte para os dados pessoais armazenados em nuvem.   
  No Brasil, houve a criação da Lei Geral de Proteção de Dados, mais conhecida como LGPD. Ela foi criada baseada na Regulamentação Geral de Proteção de Dados (GDPR) na União Européia. A LGPD foi criada para regular a coleta e uso de dados pessoais, e assim, garantir mais controle ao cidadão sobre como os seus dados são tratados pelas emoresas no Brasil e empresas que processam dados de cidadãos brasileiros.   
  Os dados pessoais são aqueles que identificam uma pessoa, como por exemplo, CPF, nome, endereço. Já os dados sensíveis são informações relacionadas a saúde, etnia, opiniões políticas, etc. Esses dados devem ser coletados com consentimento do titulos dos dados, e eles tem o direito de acessar, corrigir excluir ou até mesmo, migrar seus dados para outros serviços.    Com a LGPD, as organizações precisaram ser transparentes em relação ao uso de dados e devem adotar medidas para proteger as informações que coletam. Inclusive, houve a nomeação de um Encarregado de dados, também conhecido como DPO, que tem a responsabilidade de gerenciar esses dados em conformidade com a Lei.   
  Caso as empresas não façam o gerenciamento correto dos dados, a LGPD possui multas severas devido a violação das normas, e podem chegar a 2% do faturamento da empresa, mas com um limite de R$ 50 milhões por infração.   


### **DIREITO E COMPUTAÇÃO EM NUVEM NA ERA DIGITAL:**   
A computação em nuvem tem revolucionado a forma como as empresas e usuários lidam com armazenamento, processamento e gestão de dados. Entretanto, ela também traz desafios para a proteção dos dados pessoais e da privacidade.   
   
O direito digital e privacidade nessa era, desempenham um papel fundamental ao garantir que os direitos dos indivíduos não sejam violados no uso de tecnologias como a computação em nuvem.   
   
A LGPD exige que tanto o controlador (responsável por coletar dados), quanto o operador (geralmente o provedor de serviços de nuvem), garantam que os dados estejam protegidos e devem incluir medidas de seguranças adequadas para evitar o acesso não autorizado, o vazamento e a manipulação inadequada dos dados. Além do mais, deve haver transparência quanto ao uso de dados e ao cumprimento de direitos dos titulares, como  o direito a eliminação e acesso aos dados quando o titular dos dados solicitar.     
   
As principais causas de vazamentos de dados na computação em nuvem são: por erros de configuração dos servidores de nuvem, acessos não autorizados como os de hackers ao explorarem as vulnerabilidades, por erro humano em que um funcionário envia por engano um arquivo contendo dados pessoais a um destinatário errado, ataques de phishing e malwares conseguem acessas as credenciais de logim de funcionários, e por backup em que os dados antigos ou backups não criptografados podem ser recuperados e acessados por agentes maliciosos.    
   
Há várias soluções para mitigar esses vazamentos em nuvem. As mais comumente utilizadas são: implementação da criptografia de dados, autenticação multifatorial (MFA), moniutoramento e auditoria contínuos, treinamento e conscientização dos funcionários, segregação de acesso e privilégios em que geralmente utilizam o Zero Trust, etc.   
   
Para responder a um vazamento de dados, primeiramente ocorre a identificação e contenção imediata, em que se faz o isolamento do incidente e bloqueio do acesso comprometido para evitar mais danos. Após isso, deve ser feito uma investigação inicial para determinar a extensão do vazamento. Depois desses procedimentos, deve-se notificar a autoridade reguladora, no nosso caso, a LGPD, pois ela exige que em casos de vazamento ela seja notificada em até 72 horas após a detecção do incidente. Essa notificação deve conter detalhes sobre o incidente, tais como: natureza dos dados vazados, número de pessoas afetadas e as medidas tomadas. Após isso, os titulares dos dados também devem ser notificados, principalmente se o vazamento puder resultar em danos significativos, como fraude ou roubo de identidade. A informação dos titulares sobre o ocorrido deverá também conter as medidas que eles possam tomar para se proteger, como por exemplo, monitorar as suas contas bancárias e até mesmo alterar senhas. Depois de todos os procedimentos, deve0se fazer uma avaliação de danos para a recuperação, em que deve ser feita uma análise do impacto do incidente e das consequências para os  dados pessoais afetados, e deve-se implementar planos de recuperação de dados, se necessário, e estabelecer estratégias para evitar incidentes futuros.   
 Para a detecção desses vazamentos e vulnerabilidades, há muitas ferramentas de detecçãp de intrusão (IDP/IPS), análise de logs e auditoria, testes de penetração e vulnerabilidades.   
    
 Mitigar, detectar e responder a incidentes de segurança, são passos fundamentais para proteger os dados e garantir a conformidade com a LGPD. A implementação de tecnologias de segurança, políticas adequadas de acesso e treinamento contínuo são essenciais para reduzir os riscos de vazamento de dados e responder de maneira eficiente caso ocorram.    
     
 A LGPD exige que as empresas adotem essas medidas rigorosas para proteger os dados pessoais, especialmente quando esses dados estão sendo processados ou armazenados na computação em nuvem. As empresas devem entender que, além de obter os benefícios da nuvem, é obrigatório garantir que os dados pessoais sejam tratados com o devido cuidado e respeito pela privacidade. Com as medidas adequadas, é possível proteger tanto os dados dos titulares quanto a reputação da empresa, assegurando  o cumprimento a LGPD e criando um ambiente digital mais seguro e confiável para todos.   


     

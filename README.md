# Phishing-Login-SeToolKit

---

🚨 **Phishing e Social Engineering Toolkit (SET) - Educação em Cibersegurança**

---

⚠️ **Aviso Legal**

Este projeto utiliza o **Social Engineering Toolkit (SET)** exclusivamente para fins educativos. Nosso objetivo é conscientizar sobre as técnicas usadas por atacantes para realizar **phishing** e ensinar você a reconhecer e mitigar essas ameaças.

**Importante**: Qualquer tentativa de uso indevido desta ferramenta fora de ambientes controlados e sem autorização explícita pode violar normas éticas e leis. Este material destina-se única e exclusivamente à educação em cibersegurança e testes de segurança defensiva.

---

🔍 **O que é Phishing?**

**Phishing** é um ataque de engenharia social onde criminosos enganam usuários para roubar credenciais de login, dados bancários ou informações pessoais.

**Exemplo comum**: Um atacante pode enviar um e-mail falso, fingindo ser seu banco, alertando sobre um suposto problema na conta. Esse e-mail te redireciona para um site falso, idêntico ao real, onde você insere seus dados sem saber que está sendo enganado.

---

🎭 **Características Comuns de Ataques de Phishing**

* ✅ E-mails ou mensagens que parecem legítimas.
* ✅ Links suspeitos que redirecionam para sites falsos.
* ✅ Solicitação de login ou informações bancárias.
* ✅ Avisos falsos sobre problemas na conta.
* ✅ Incentivo para clicar, baixar arquivos ou instalar software.

---

🛡️ **Social Engineering Toolkit (SET)**

O **SET** é uma poderosa ferramenta open-source, pré-instalada no Kali Linux, projetada para testes de segurança e simulações de ataques.

---

🔧 **Recursos Principais do SET**

1.  **Automação de ataques de phishing**: Permite criar campanhas falsas para testes internos.
2.  **Captura de credenciais**: Simula roubo de senhas para análise de vulnerabilidades.
3.  **Geração de payloads**: Cria scripts maliciosos para testes de segurança.
4.  **Módulos de Engenharia Social**: Inclui *email spoofing*, *SMS spoofing* e ataques via dispositivos USB.

**Importante**: Use o SET apenas em ambientes autorizados, para fins de educação e testes defensivos.

---

🛠 **Recursos Adicionais**

* 📖 [Documentação oficial do SET](https://www.trustedsec.com/social-engineer-toolkit-set/)
* 🔒 [Guia de prevenção contra phishing](https://www.gov.br/pt-br/servicos/prevenir-se-de-phishing-e-golpes-na-internet)
* 🛡️ [Práticas recomendadas em cibersegurança](https://www.cisa.gov/topics/cyber-threats-and-advisories/cybersecurity-best-practices)

---

### Ferramentas Necessárias

* **Kali Linux**
* **Setoolkit** (pré-instalado no Kali Linux)

---

💡 **PASSOS PARA O TESTE**

1.  No terminal do Kali, rode `sudo setoolkit`.
2.  Escolha `y` para aceitar os termos.
3.  Selecione `1: Social Engineering Attack`.
4.  Selecione `2: Website Attack Vectors`.
5.  Selecione `3: Credential Harvester Attack Method`.
6.  Selecione `2: Site Cloner`.
7.  Insira seu endereço IP local (para descobrir, use `ifconfig` no terminal).
8.  Insira a URL do site que deseja clonar.
9.  Abra seu navegador e digite o endereço de IP local para rodar o phishing.
10. Pronto! A página de login foi clonada e está idêntica à real.
11. As credenciais de login da Vítima foram capturadas com sucesso.

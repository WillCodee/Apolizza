# Apolizza Corretora de Seguros — Site Institucional

Site institucional da **Apolizza Corretora de Seguros**, hospedado em [apolizza.com](https://apolizza.com).

---

## Tecnologias

- HTML5 + CSS3 + JavaScript puro (sem frameworks)
- Google Fonts (Poppins)
- Ícones SVG inline
- Intersection Observer API para animações de scroll
- Google Maps embed para localização

---

## Envio de E-mails — EmailJS

O formulário de cotação do site utiliza **[EmailJS](https://www.emailjs.com/)** para envio de e-mails diretamente do front-end, sem necessidade de back-end ou servidor próprio.

### Como funciona

1. O visitante preenche o formulário de cotação (nome, telefone, e-mail, ramo de seguro e mensagem)
2. Ao enviar, o JavaScript do site chama a API do EmailJS com os dados do formulário
3. O EmailJS processa a requisição e envia o e-mail via SMTP da HostGator
4. O e-mail chega na caixa `relacionamento@apolizza.com` com formatação profissional

### Configuração

| Parâmetro | Valor |
|-----------|-------|
| Plataforma | EmailJS (https://www.emailjs.com/) |
| SDK | @emailjs/browser@4 via CDN (jsDelivr) |
| Service ID | service_osmhqnn |
| Template ID | template_yavneyk |
| SMTP Host | mail.apolizza.com (HostGator) |
| SMTP Porta | 465 (SSL) |
| Remetente | relacionamento@apolizza.com |

### Plano gratuito

O plano gratuito do EmailJS inclui **200 e-mails por mês**, o que é suficiente para o volume de cotações esperado. Caso o volume aumente, é possível fazer upgrade diretamente no painel do EmailJS.

### Parâmetros enviados no template

| Parâmetro | Descrição |
|-----------|-----------|
| from_name | Nome do solicitante |
| telefone | Telefone para contato |
| email | E-mail do solicitante |
| ramo | Ramo de seguro selecionado |
| ramo_assunto | Nome curto do ramo (usado no assunto do e-mail) |
| mensagem | Mensagem adicional |
| data_hora | Data e hora da solicitação |

---

## Contato

- **WhatsApp:** +55 71 98119-3987
- **E-mail:** relacionamento@apolizza.com
- **Endereço:** Av. Luís Viana Filho, 13223 — Hangar Business Park, Hangar 6, Sala 211 — Salvador/BA
- **Instagram:** @apolizza (https://www.instagram.com/apolizza)
- **LinkedIn:** Apolizza Corretora (https://www.linkedin.com/in/apolliza-corretora-de-seguros-1660013b7)

---

## Hospedagem

Site hospedado na **HostGator** via cPanel File Manager, na pasta `public_html`.

**CNPJ:** 15.728.440/0001-37

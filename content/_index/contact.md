+++
fragment = "contact"
#disabled = true
date = "2022-06-02"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Entre em Contato conosco"
subtitle  = "sua dúvida é muito bem vinda"

# PostURL can be used with backends such as mailout from caddy
post_url = "https://example.com/mailout" #default: formspree.io
email = "mail@example.com"
button = "Send Button" # defaults to theme default
button_text = "Enviar Mensagem"
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Seu Nome *"
  #error = "" # defaults to theme default

[fields.email]
  text = "Seu E-mail *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Seu Telefone *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Sua Mensagem *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++

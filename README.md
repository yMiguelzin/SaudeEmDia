<div align="center">

# 🩺 Saúde em Dia
### Sistema Mobile de Gestão de Saúde

</div>

---

## 📌 Visão Geral do Projeto
Aplicativo mobile desenvolvido no **Kodular** e integrado com uma base de dados relacional no **Supabase**, focado na organização e no controlo de saúde pessoal, consultas, medicamentos e histórico unificado.

---

## 📁 Estrutura do Repositório

* **`SaudeEmDia_oficial.aia`:** Código-fonte completo com as 12 telas do aplicativo (autenticação, painel principal, gestão de consultas, medicamentos, histórico e edição de perfil com validação de dados).
* **`schema.sql`:** Script SQL completo com a estrutura de tabelas e views do Supabase.
* **`SaudeEmDia_oficial.apk`:** APK COMPLETO.

---

## 🗄️ Base de Dados (Supabase)

O projeto está estruturado com os seguintes componentes no Supabase:
* **`usuarios`** — Gestão de dados cadastrais, credenciais de acesso, CPF, CEP e contacto.
* **`consultas`** — Controlo e registo de marcações médicas, doutores e locais.
* **`medicamentos`** — Acompanhamento de remédios e dosagens associados aos utilizadores.
* **`vw_historico`** — View relacional que unifica o histórico de consultas e medicamentos num único fluxo.

> O código SQL completo para recriar esta arquitetura encontra-se no ficheiro `schema.sql` na raiz deste repositório.

---

## 💻 Como Executar no Kodular (Modo Desenvolvedor)

1. Descarrega o ficheiro **`.aia`** disponibilizado neste repositório.
2. Acede à plataforma oficial do [Kodular Creator](https://creator.kodular.io/).
3. No menu superior, clica em **File** > **Import project (.aia) from my computer** e seleciona o ficheiro.
4. Para testar em tempo real, instala a aplicação **Kodular Companion** no teu dispositivo Android, acede a **Test** > **Connect to Companion** e lê o QR Code gerado no ecrã.

---

## 📦 Como Gerar o APK

1. No painel do projeto no Kodular Creator, clica no botão **Export** localizado no menu superior.
2. Seleciona a opção **Android App (.apk)** e clica em **Save APK to my computer**.
3. Transfere o ficheiro `.apk` gerado para o teu telemóvel e procede à instalação.

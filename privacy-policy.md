# Política de Privacidade — Contador de Água

**Última atualização:** 12 de maio de 2026

Esta Política de Privacidade descreve como o aplicativo **Contador de Água** ("nós", "nosso" ou "aplicativo") coleta, usa, armazena e protege suas informações quando você utiliza nossos serviços em dispositivos móveis.

Ao utilizar o aplicativo, você concorda com a coleta e o uso de informações de acordo com esta política. Esta política está em conformidade com a **Lei Geral de Proteção de Dados Pessoais (LGPD — Lei nº 13.709/2018)** do Brasil e com o **Regulamento Geral sobre a Proteção de Dados (GDPR)** da União Europeia.

---

## 1. Controlador dos Dados

O controlador responsável pelo tratamento de dados pessoais coletados por este aplicativo é:

- **Aplicativo:** Contador de Água
- **Contato:** ti@greycom.com.br

Em caso de dúvidas, solicitações ou exercício de direitos, entre em contato pelo e-mail acima.

---

## 2. Dados que Coletamos

Coletamos os seguintes tipos de informação:

### 2.1. Informações fornecidas por você

- **Nome de exibição** (opcional): apenas para personalização da interface.
- **E-mail**: usado para autenticação da conta.
- **Senha**: armazenada de forma criptografada (hash) por nosso provedor de autenticação.
- **Foto de perfil** (opcional): se você optar por enviar.
- **Meta diária de hidratação** e **registros de consumo de água**: para gerar suas estatísticas pessoais.

### 2.2. Informações coletadas automaticamente

- **Identificadores do dispositivo** (ID de publicidade): usado pela rede de anúncios para exibir publicidade.
- **Dados técnicos**: sistema operacional, versão do aplicativo, idioma — para diagnóstico e melhoria do serviço.
- **Notificações push**: tokens necessários para enviar lembretes de hidratação que você configurar.

### 2.3. O que NÃO coletamos

- Não coletamos sua localização precisa (GPS).
- Não acessamos sua agenda, contatos ou mensagens.
- Não gravamos áudio ou vídeo.
- Não coletamos dados de saúde de outros aplicativos ou wearables.

---

## 3. Como Usamos seus Dados

Seus dados são utilizados exclusivamente para:

1. **Autenticar você** no aplicativo (Supabase Auth).
2. **Sincronizar seus registros** entre dispositivos.
3. **Calcular suas estatísticas** de hidratação (sequência, médias, metas atingidas).
4. **Enviar notificações** de lembretes que você mesmo configurou.
5. **Exibir publicidade** via Google AdMob (para usuários gratuitos).
6. **Diagnosticar problemas técnicos** e melhorar o aplicativo.

Não utilizamos seus dados para treinamento de modelos de IA, perfis de crédito, ou qualquer finalidade não declarada nesta política.

---

## 4. Compartilhamento de Dados com Terceiros

Compartilhamos dados estritamente necessários com os seguintes serviços:

| Serviço            | Finalidade                       | Dados                                                  | Política                            |
| ------------------ | -------------------------------- | ------------------------------------------------------ | ----------------------------------- |
| **Supabase**       | Autenticação e banco de dados    | E-mail, senha (hash), nome, foto, registros de consumo | https://supabase.com/privacy        |
| **Google AdMob**   | Exibição de anúncios             | ID de publicidade, dados técnicos do dispositivo       | https://policies.google.com/privacy |
| **Google Sign-In** | Login com Google (opcional)      | E-mail e nome do Google                                | https://policies.google.com/privacy |
| **Expo / EAS**     | Distribuição e notificações push | Token de push                                          | https://expo.dev/privacy            |

**Não vendemos seus dados** para terceiros sob nenhuma circunstância.

---

## 5. Anúncios e Consentimento (UMP)

O aplicativo exibe anúncios do **Google AdMob** para usuários do plano gratuito.

- Na primeira execução, exibimos um formulário de consentimento de privacidade (Google UMP) sempre que sua região (ex.: UE, Reino Unido, Brasil) exigir.
- Você pode escolher entre **anúncios personalizados** ou **anúncios não personalizados**.
- Você pode **alterar sua escolha a qualquer momento** indo em **Perfil → Privacidade e dados → Configurações de anúncios**.

Mesmo que você opte por anúncios não personalizados, continuaremos exibindo publicidade — apenas de forma genérica.

---

## 6. Onde seus Dados são Armazenados

- **Banco de dados (Supabase):** servidores localizados na região definida pelo Supabase (atualmente datacenters da AWS).
- **No seu dispositivo:** suas preferências locais e cache ficam em armazenamento seguro do app (`expo-secure-store` e `AsyncStorage`).
- **Tempo de retenção:** seus dados permanecem armazenados enquanto sua conta estiver ativa. Após exclusão da conta, removemos seus dados em até **30 dias**.

---

## 7. Seus Direitos (LGPD / GDPR)

Você tem o direito de:

1. **Acessar** os dados que mantemos sobre você.
2. **Corrigir** dados incompletos, inexatos ou desatualizados.
3. **Excluir** sua conta e todos os dados associados.
4. **Portabilidade** dos seus dados em formato legível por máquina.
5. **Revogar consentimento** dado anteriormente, a qualquer momento.
6. **Opor-se** ao tratamento de dados em determinadas situações.
7. **Reclamar** à Autoridade Nacional de Proteção de Dados (ANPD).

Para exercer qualquer desses direitos, envie um e-mail para **ti@greycom.com.br** com o assunto **"Direitos LGPD"**. Responderemos em até **15 dias úteis**.

### Como excluir sua conta dentro do app

A funcionalidade de exclusão de conta pode ser solicitada por e-mail enquanto não estiver disponível diretamente no aplicativo.

---

## 8. Segurança

Adotamos medidas técnicas e administrativas para proteger seus dados:

- Comunicação criptografada em trânsito (HTTPS / TLS).
- Senhas armazenadas como hash (nunca em texto puro).
- Tokens de sessão guardados em armazenamento seguro do sistema operacional.
- Acesso ao banco de dados restrito por regras de Row-Level Security (RLS).

Apesar disso, nenhum sistema é 100% seguro. Recomendamos que você utilize senhas fortes e não compartilhe seu acesso.

---

## 9. Crianças

O aplicativo **não é direcionado a menores de 13 anos** e não coletamos intencionalmente dados de crianças. Se descobrirmos que coletamos dados de um menor sem o consentimento dos responsáveis, esses dados serão excluídos imediatamente.

---

## 10. Alterações nesta Política

Podemos atualizar esta política periodicamente. A data da última atualização sempre estará no topo do documento. Alterações relevantes serão comunicadas dentro do aplicativo.

---

## 11. Contato

Dúvidas, sugestões ou solicitações?

**E-mail:** patricksimoes25@gmail.com

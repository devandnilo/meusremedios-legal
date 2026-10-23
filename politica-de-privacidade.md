# Política de Privacidade — Meus Remédios

**Última atualização:** [23/10/2026]

A sua privacidade é muito importante para nós. Esta Política de Privacidade explica como o aplicativo **Meus Remédios** ("nós", "nosso" ou "app") coleta, usa, armazena e protege as suas informações.

## 1. Informações que coletamos

### 1.1 Dados que você insere manualmente no app
O Meus Remédios armazena, **exclusivamente no seu dispositivo**:
- Nome, dosagem e apresentação dos medicamentos
- Horários e frequência das doses
- Histórico de doses tomadas
- Movimentações de estoque
- Observações e fotos que você optar por cadastrar
- Data de vencimento de receitas
- Perfis familiares (nome, cor, emoji)

Esses dados **nunca** são enviados aos nossos servidores — nós não temos servidores que recebem esses dados.

### 1.2 Dados que você opta por enviar ao Google Drive (backup)
Se você **vincular uma conta Google** e **ativar o backup**, o app cria um arquivo JSON no **Google Drive** dentro do escopo `appDataFolder` (uma pasta privada, inacessível a outros apps). Esse arquivo contém:
- Medicamentos, horários e doses
- Movimentações de estoque
- Perfis (quando aplicável)

O backup só acontece **após você autorizar explicitamente** e somente na sua própria conta Google. **Nós não temos acesso** a esse arquivo.

### 1.3 Dados anônimos de crash
Usamos o **Firebase Crashlytics** para detectar falhas do app. Quando o aplicativo fecha inesperadamente, é enviado:
- Modelo do dispositivo, versão do Android
- Stack trace do erro (código interno)
- Estado do app no momento do crash (ex: tela atual)

**NÃO** são enviados dados de saúde, nomes de medicamentos, nem informações pessoais identificáveis.

### 1.4 Informações de assinatura (Premium)
Se você assinar o Premium, a **Google Play Store** processa o pagamento. **Nós não armazenamos números de cartão**, dados bancários ou dados de pagamento. Recebemos apenas a confirmação da assinatura (plano e data de expiração) para liberar os recursos.

## 2. Como usamos suas informações
Usamos seus dados apenas para:
- Fazer o aplicativo funcionar como esperado (alarmes, histórico, estoque)
- Sincronizar o backup na sua conta Google Drive (se ativado)
- Corrigir bugs e melhorar a estabilidade
- Verificar e manter a assinatura Premium

**NÃO vendemos, alugamos ou compartilhamos** seus dados com terceiros.

## 3. Compartilhamento com terceiros
Os únicos terceiros que podem ter contato com seus dados são:

| Terceiro | Finalidade | Dados |
|---|---|---|
| Google Play Services | Login, backup, assinatura | E-mail da conta Google, token de assinatura |
| Firebase Crashlytics | Diagnóstico de falhas | Modelo do dispositivo, stack trace do erro |

Nenhum dado é compartilhado para fins publicitários.

## 4. Armazenamento e segurança
- **Dados locais:** guardados num banco de dados **criptografado** (SQLCipher AES-256), protegido por chave armazenada no Android Keystore.
- **Backup na nuvem:** criptografado em trânsito (HTTPS/TLS) e repouso (Google Drive).
- **Dados de crash:** mantidos pelo Firebase por 90 dias.

## 5. Seus direitos (LGPD)
De acordo com a Lei Geral de Proteção de Dados (Lei 13.709/2018), você tem direito a:
- **Acessar** seus dados (você já vê tudo no app)
- **Corrigir** dados (edições no app)
- **Excluir** dados (desinstalar o app apaga tudo do dispositivo; para excluir o backup do Drive, use a própria interface do Google Drive. Você também pode usar o botão "Excluir conta e dados" nas configurações do app)
- **Revogar consentimento** (desativar backup nas Configurações)

## 6. Crianças
O app não é destinado a crianças menores de 13 anos. Não coletamos intencionalmente dados de crianças.

## 7. Alterações
Podemos atualizar esta política periodicamente. A data no topo indica a última alteração.

## 8. Contato
Dúvidas? Entre em contato: **[deandnilo@gmail.com]**

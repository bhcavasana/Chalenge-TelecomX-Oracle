# 📖 Dicionário de Dados - Telecom X

Este documento descreve cada uma das colunas (features) utilizadas na análise de evasão de clientes da Telecom X. Os dados foram extraídos do arquivo `TelecomX_Data.json` e processados no notebook `TelecomX_BR_Analise.ipynb`.

| Coluna (Feature) | Descrição | Tipo de Dado / Exemplos |
| :--- | :--- | :--- |
| `customerID` | Identificador único para cada cliente. | `Texto` / `0002-ORFBO` |
| `Churn` | Indica se o cliente evadiu (cancelou o serviço) ou não. | `Categórico` / `Yes`, `No` |
| `gender` | Gênero do cliente. | `Categórico` / `Male`, `Female` |
| `SeniorCitizen` | Indica se o cliente é idoso (65 anos ou mais). | `Binário` / `1` (Sim), `0` (Não) |
| `Partner` | Indica se o cliente tem um(a) parceiro(a). | `Categórico` / `Yes`, `No` |
| `Dependents` | Indica se o cliente tem dependentes. | `Categórico` / `Yes`, `No` |
| `tenure` | Número de meses que o cliente permaneceu na empresa. | `Numérico (Inteiro)` / `9`, `67` |
| `PhoneService` | Indica se o cliente assina o serviço de telefonia. | `Categórico` / `Yes`, `No` |
| `MultipleLines` | Indica se o cliente tem múltiplas linhas telefônicas. | `Categórico` / `Yes`, `No`, `No phone service` |
| `InternetService` | Tipo de serviço de internet do cliente. | `Categórico` / `DSL`, `Fiber optic`, `No` |
| `OnlineSecurity` | Indica se o cliente assina o serviço de segurança online. | `Categórico` / `Yes`, `No`, `No internet service` |
| `OnlineBackup` | Indica se o cliente assina o serviço de backup online. | `Categórico` / `Yes`, `No`, `No internet service` |
| `DeviceProtection` | Indica se o cliente tem proteção para seus dispositivos. | `Categórico` / `Yes`, `No`, `No internet service` |
| `TechSupport` | Indica se o cliente tem suporte técnico contratado. | `Categórico` / `Yes`, `No`, `No internet service` |
| `StreamingTV` | Indica se o cliente assina o serviço de Streaming de TV. | `Categórico` / `Yes`, `No`, `No internet service` |
| `StreamingMovies` | Indica se o cliente assina o serviço de Streaming de Filmes. | `Categórico` / `Yes`, `No`, `No internet service` |
| `Contract` | Tipo de contrato do cliente. | `Categórico` / `Month-to-month`, `One year`, `Two year` |
| `PaperlessBilling` | Indica se o cliente aderiu à fatura eletrônica (sem papel). | `Categórico` / `Yes`, `No` |
| `PaymentMethod` | Método de pagamento utilizado pelo cliente. | `Categórico` / `Electronic check`, `Mailed check`, ... |
| `MonthlyCharges` | Valor da cobrança mensal do cliente. | `Numérico (Float)` / `65.6`, `59.9` |
| `TotalCharges` | Valor total cobrado do cliente ao longo de todo o contrato. | `Numérico (Float)` / `593.3`, `542.4` |
| `Churn_Binary` | Versão numérica da coluna `Churn` para facilitar cálculos. | `Binário` / `1` (Churn), `0` (Não Churn) |

---
# ROPZ - Rede de Observação de Zonas Quentes 🌡️🔥

## Integrantes do Grupo
- **RM552648 - Diego Costa Silva**
- **RM553745 - Lucas Minozzo Bronzeri**
- **RM553870 - Thaís Ribeiro Asfur**

---

## 📌 Descrição do Problema
As **mudanças climáticas** têm provocado um aumento nos eventos de **calor extremo**, afetando principalmente **idosos, crianças** e pessoas com **doenças crônicas**. Esses grupos estão mais vulneráveis a problemas como insolação, desidratação e agravamento de doenças respiratórias.

Apesar disso, **faltam alertas personalizados** e instruções claras de prevenção para a população em risco.

---

## 💡 Descrição da Solução
O **ROPZ** é um sistema inteligente de **monitoramento climático** com alertas personalizados baseados na **localização do usuário** (CEP). Inspirado em ações da **Defesa Civil**, o sistema antecipa eventos críticos de calor e envia **notificações preventivas** com orientações claras.

### Funcionalidades principais:
- **Monitoramento automático** do clima com dados de API e sensores simulados
- **IA preditiva** para identificar zonas de risco
- **Alertas personalizados** por:
  - Aplicativo Mobile (React Native)
- **Dicas de prevenção** adaptadas ao nível de risco

---

## 🎯 Público-Alvo
- Idosos
- Crianças
- Pessoas com doenças respiratórias, cardiovasculares ou metabólicas
- Populações urbanas expostas ao calor extremo

---

## 📊 Estudo de Mercado
Aplicativos meteorológicos existentes (como Climatempo, AccuWeather e Inmet) fornecem **dados brutos**, mas não fazem **análise de risco personalizada** nem emitem **alertas adaptados ao perfil do usuário**.

O **ROPZ se diferencia** por:
- Antecipar eventos críticos com base em IA
- Personalizar alertas por região e gravidade
- Integrar recomendações práticas de saúde pública

---

## 🚀 Potencial de Mercado
- **Parcerias** com prefeituras e Defesa Civil
- **Integração** com escolas, postos de saúde e residências
- **Aplicabilidade social direta**, especialmente em épocas de onda de calor

---

## 🧠 Projeto de IA

A IA do projeto foi desenvolvida em **Python** utilizando bibliotecas como `pandas`, `scikit-learn`, `matplotlib` e `seaborn`.

### 🔹 Dados utilizados:
- Os dados de **temperatura** utilizados no treinamento do modelo foram **coletados a partir de uma simulação de sensores IoT**, simulando medições de temperatura em tempo real em diferentes regiões.

### 🔹 Features do modelo:
- Temperatura média e máxima
- Umidade relativa do ar
- Velocidade do vento
- Condições atmosféricas

### 🔹 Técnicas e Algoritmos:
- Random Forest
- Tecnica de SMOTE
- Normalização de dados
- Divisão treino/teste com validação de performance:
  - Acurácia
  - Precisão
  - F1-Score

### 🔹 Infraestrutura:
- **MongoDB** para armazenamento de alertas e perfis

---

## ⚙️ Funcionalidades
- ✅ Previsão de calor extremo com IA
- ✅ Alerta automático
- ✅ Simulação de sensores IoT
- ✅ Visualização de dados em tempo real

---

## 🔍 Autocrítica
- O modelo pode ser ainda mais preciso com dados meteorológicos reais históricos em larga escala.

## 🎥 Vídeos

[🔗 Vídeo sobre o projeto](https://youtu.be/-Vx6H45jRYA)  
[🔗 Vídeo pitch](https://youtu.be/O1Hr3DbmBR4)

# 💧 Consumo de Água

Aplicativo desenvolvido com Flutter para ajudar no registro e acompanhamento do consumo de água durante o dia.

## 🎯 Sobre o projeto

O aplicativo permite que o usuário registre seu consumo de água e acompanhe seu progresso em relação à meta diária.

Para realizar os cálculos, são utilizados:

* Data do consumo
* Quantidade de água ingerida em ml
* Peso do usuário em kg

### 📊 Cálculo da meta

A meta diária de água é calculada utilizando a fórmula:

**Meta diária = peso × 35**

A porcentagem de progresso é calculada com base na quantidade consumida:

**Porcentagem = (água consumida ÷ meta diária) × 100**

## ✨ Recursos disponíveis

* 💧 Registro do consumo de água
* 📅 Histórico dos registros
* ✏️ Alteração dos registros cadastrados
* 🗑️ Exclusão de registros
* 🎯 Definição automática da meta diária
* 📈 Acompanhamento da porcentagem da meta
* ➕ Soma do consumo realizado durante o dia
* 💾 Armazenamento dos dados no dispositivo
* 🌙 Opção de tema claro e escuro
* 🚀 Tela inicial (Splash Screen)
* 📊 Gráfico para visualizar o consumo
* 🎨 Interface personalizada

## 🛠️ Tecnologias utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Flutter** — desenvolvimento da aplicação
* **Dart** — linguagem de programação
* **SharedPreferences** — armazenamento local
* **FL Chart** — criação dos gráficos
* **JSON** — organização e conversão dos dados
* **Material Design** — componentes e estrutura visual

## ▶️ Como executar o projeto

Primeiramente, tenha o Flutter instalado e configurado no computador.

Depois, abra o terminal na pasta do projeto e execute:

```bash
flutter pub get
```

Após instalar as dependências, execute o aplicativo com:

```bash
flutter run
```

Também é possível executar o projeto diretamente pelo VS Code utilizando um dispositivo ou emulador configurado.

## 📱 Imagens do aplicativo

<p align="center">
  <img src="assets/images/telas.png" width="45%">
  <img src="assets/images/telas 22.png" width="45%">
</p>


## 📌 Observações

Os registros são armazenados localmente no dispositivo, permitindo que os dados continuem disponíveis mesmo depois de fechar o aplicativo.

O projeto foi desenvolvido como atividade prática para aplicar conceitos de desenvolvimento de aplicativos utilizando Flutter e Dart.

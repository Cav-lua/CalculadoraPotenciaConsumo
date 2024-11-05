# **APP Calculadora de Potência e Consumo de Eletrônicos**

> Um aplicativo Android para calcular o consumo de energia e o custo associado de diferentes aparelhos eletrônicos.

## 📱 Descrição

O **APP Calculadora de Potência e Consumo de Eletrônicos** permite que o usuário calcule o consumo de energia em kWh e o custo estimado de uso de dispositivos eletrônicos com base em sua potência, tempo de uso e o preço por kWh.

## 🔧 Funcionalidades

- [x] Entrada de dados (Potência do aparelho em Watts, Tempo de uso em horas e Preço por kWh)
- [x] Cálculo do consumo de energia (kWh) usando a fórmula: `CE = P * H / 1000`
- [x] Cálculo do custo associado usando a fórmula: `C = CE * PKWH`
- [x] Exibição do consumo e do custo estimado na tela de resultados
- [x] Interface escura e minimalista para uma experiência de usuário amigável

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **LinearLayout** para estrutura de layout simples e responsiva
- [x] **TextView** e **EditText** para entrada e exibição de dados
- [x] **Button** para acionar o cálculo

## 🛠️ Como Rodar o Projeto

Para executar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1. Clone o repositório:

    ```bash
    git clone https://github.com/Cav-lua/calculadora-potencia-consumo.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/calculadorapotenciaconsumo
│   │   │   │   └── MainActivity.java       # Classe principal para cálculos
│   │   │   └── res
│   │   │       ├── layout
│   │   │       │   └── activity_main.xml   # Layout da tela principal
│   │   │       └── values
│   │   │           ├── strings.xml         # Strings usadas no app
│   │   │           ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
```
🎨 Design e Prototipagem
A interface do app foi criada usando LinearLayout para manter a simplicidade e a clareza em diferentes tamanhos de tela.

O design é minimalista e fácil de usar, com uma paleta escura para uma experiência agradável.

🖥️ Telas do Aplicativo
Tela Principal

Na tela principal, o usuário insere a potência do aparelho em watts, o tempo de uso em horas e o preço do kWh. O aplicativo calcula e exibe o consumo e o custo associados.

![TelaPrincipal](https://github.com/user-attachments/assets/7dd6ace8-b96c-403b-b3eb-9bf35dc7cf47)

👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob os termos da licença MIT.

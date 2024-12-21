# Firebase Authentication App

Este é um aplicativo Android que implementa autenticação de usuários usando **Firebase Authentication**. O aplicativo permite que os usuários se registrem e façam login com email e senha. Além disso, oferece a funcionalidade de "Lembrar Email e Senha", armazenando credenciais localmente.

---

## 📋 Funcionalidades

- **Registro de Usuário**: Permite criar uma conta com email e senha.
- **Login Seguro**: Valida credenciais usando o **Firebase Authentication**.
- **Redirecionamento**: Após login bem-sucedido, redireciona para o console do Firebase.
- **Interface Responsiva**: UI simples e funcional com estilização personalizada.

---

## 🚀 Configuração

### Pré-requisitos

- **Android Studio** (versão mais recente).
- **Conta no Firebase**: [Firebase Console](https://console.firebase.google.com/).
- **Dispositivo ou Emulador**: Configurado no Android Studio.

### Passos para Configuração

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

2. **Abra o Projeto no Android Studio**:
   - Use a opção **Open** e selecione a pasta do projeto.

3. **Configure o Firebase**:
   - No console do Firebase, crie um novo projeto.
   - Adicione o pacote do aplicativo (ex.: `com.example.tela_login_firebase`).
   - Ative o método de autenticação com **Email/Senha**.
   - Baixe o arquivo `google-services.json` e adicione-o na pasta `app/` do projeto.

4. **Sincronize o Gradle**:
   - Clique em **File > Sync Project with Gradle Files** no Android Studio.

5. **Execute o Aplicativo**:
   - Escolha um dispositivo ou emulador configurado.
   - Clique em **Run > Run 'app'** para iniciar.

---

## 🖼 Screenshots

### Tela de Login
<img src="https://github.com/Micael-Resende/App_Login-Firebase/blob/main/images/app.jpg" alt="" width="300">

### Tela de Registro
<img src="https://github.com/Micael-Resende/App_Login-Firebase/blob/main/images/registro.jpg" alt="" width="300">

### Usuário cadastrado
<img src="https://github.com/Micael-Resende/App_Login-Firebase/blob/main/images/login-auth.jpg" alt="" width="300">

---

## 🛠️ Tecnologias Utilizadas

- **Kotlin**: Linguagem principal do desenvolvimento.
- **Firebase Authentication**: Gerenciamento de autenticação de usuários.
- **SharedPreferences**: Armazenamento local para credenciais.
- **Android Studio**: IDE para desenvolvimento.

---

## 📚 Como Usar

1. Abra o aplicativo e insira suas credenciais.
2. Clique em **Register** para criar uma conta, ou **Login** para acessar.
4. Após o login bem-sucedido, o aplicativo abrirá o navegador e redirecionará para o console do Firebase.

---

## 🤝 Como Contribuir

1. Faça um **fork** deste repositório.
2. Crie uma **branch** para suas alterações:
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. Envie suas alterações:
   ```bash
   git commit -m "Adicionada nova funcionalidade"
   git push origin feature/nova-funcionalidade
   ```
4. Abra um **Pull Request**.

---

## 🖋️ Licença

Este projeto está licenciado sob a [MIT License](LICENSE). Sinta-se à vontade para usá-lo e modificá-lo.

---

## 📧 Contato

Feito com ❤️ por [Micael Resende]. Se tiver dúvidas, entre em contato!


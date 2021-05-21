sudo npm install --global expo-cli
expo init imagigram
cd imagigram
yarn add @react-navigation/native @react-navigation/stack react-native-screens
expo install react-native-gesture-handler @react-native-community/masked-view
yarn start / expo start

Firebase (console.firebase.google.com):

1. Adicionar projeto
2. Autenticação / Primeiros passos / Ative o provedor E-mail/senha
3. Adicione um app para começar / Web / Copie firebaseConfig
4. expo install firebase
5. Cole firebaseConfig dentro de App /

Redux e Firebase Cloud Firestore:

yarn add redux react-redux redux-thunk

- Firestore

1. Criar banco de dados / Iniciar no modo de teste / Ativar
2. Iniciar uma coleção / users / email, password / deletar documento

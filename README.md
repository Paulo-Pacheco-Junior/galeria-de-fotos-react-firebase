### React | TypeScript | Firebase

Projeto para praticar React e configurar o Firebase como "Back-end" para armazenamento de imagens.

Obs: Para funcionar é necessário ter uma conta no Firebase,<br>
Criar um Projeto,<br>
Ativar o Firebase Storage em Armazenamento,<br>
Pegar os dados de configuração para preencher no .env(renomeie o .env.example para .env).<br>
Os dados são necessários no firebaseConfig que fica em libs/firebase.ts.<br>
O firebaseConfig recebe essas informações do .env<br>
<br>
const firebaseConfig = {<br>
  apiKey: process.env.REACT_APP_FIREBASE_APIKEY,<br>
  authDomain: process.env.REACT_APP_FIREBASE_AUTHDOMAIN,<br>
  projectId: process.env.REACT_APP_FIREBASE_PROJECTID,<br>
  storageBucket: process.env.REACT_APP_FIREBASE_STORAGEBUCKET,<br>
  messagingSenderId: process.env.REACT_APP_FIREBASE_MESSAGINGSENDERID,<br>
  appId: process.env.REACT_APP_FIREBASE_APPID<br>
};<br><br>

![firebase1](https://user-images.githubusercontent.com/78752003/181867418-409a4325-f7f5-4943-8d1d-ae837b2a8dfd.jpg)

REACT + FIREBASE
![firebase2](https://user-images.githubusercontent.com/78752003/181867421-b9820c28-43e3-4e0f-96ef-ac92cdaadf57.jpg)

## :arrow_forward: Como executar

- No seu terminal digite: `git clone https://github.com/Paulo-Pacheco-Junior/galeria-de-fotos-react-firebase.git`
- Entre no diretório: `cd galeria-de-fotos-react-firebase`
- Rode `npm install` para baixar as dependências
- Rode `npm start` para iniciar a aplicação

Por fim, a aplicação estará disponível em `http://localhost:3000`.

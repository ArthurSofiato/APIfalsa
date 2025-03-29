📱 Projeto API Falsa com Aplicação Mobile  

Este projeto consiste em uma API simulada utilizando o `json-server` para fornecer dados fictícios, desenvolvido com `Expo` que consome essa API.  

 🛠 Tecnologias Utilizadas  
- Backend: `json-server`, `Node.js`  
- Mobile: `React Native`, `Expo`  

 🚀 Como Executar  

 🔹 Backend (API Falsa)  
1. Navegue até a pasta do backend:  
     
2. Instale as dependências:  
     
   npm install  
     
3. Gere os dados iniciais:  
     
   node generate.js  
     
4. Inicie o servidor JSON:  
     
   npx json-server --watch db.json --port 3000  
     
   A API estará disponível em: [`http://localhost:3000`](http://localhost:3000).  

 🔹 Mobile (Aplicativo Expo)  
1. Acesse a pasta do projeto mobile:    
     
2. Instale as dependências:  
     
   npm install  
     
3. Inicie o aplicativo:  
     
   npx expo start  
     
   Agora, o Expo abrirá um painel interativo, permitindo rodar o app em um emulador ou dispositivo físico.  

 📌 Observações  
- Certifique-se de que o backend esteja rodando antes de iniciar o app mobile.  
- Para acessar no celular, escaneie o QR Code gerado pelo Expo e utilize o aplicativo Expo Go.  
- Caso esteja testando em um dispositivo físico, garanta que o backend e o celular estejam na mesma rede.  


📩 Autor: [Arthur Ramos Argenton Sofiato]

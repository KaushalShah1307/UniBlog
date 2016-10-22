# UniBlog
Cross-Platform Blog using React JS.

App
http://uniblog-using-reactjs.cosmicapp.co

About

The UniBlog is a portfolio blog app that renders html on the server to make all pages visible to search engines. Then after initial load from the server, it is converted to a single page application to allow for fast navigation between pages.

Notes

I tried to keep the organization as simple as possible. There are no client, server or shared component folders. All components are shared and the only difference between client and server are the entry points (app-client.js, app-server.js and app.js).

It uses the following:
1. React for UI views
2. Express for server side rendering
3. React Router for routing
4. React Hot Loader for hot loading in development
5. Flux for data flow
6. Cosmic JS for content management

Install

git clone https://github.com/KaushalShah1307/UniBlog/
cd UniBlog
npm install
Run development

npm run development
Go to http://localhost:8080

Run production

npm start
Go to http://localhost:3000

Configure your Cosmic JS bucket

After setting up your bucket on Cosmic JS, edit the config.js file and edit the slug to point to the slug of your bucket:

// config.js
export default {
  bucket: {
    slug: 'uniblog-using-reactjs'
  }
}

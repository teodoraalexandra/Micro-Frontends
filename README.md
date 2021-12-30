# Micro-Frontends

How to? 🔥

Install nx:
**npm install -g nx**

Create the app:
**npx create-nx-workspace@latest nx-micro-frontend**

Create the microfrontend:
**cd nx-micro-frontend**
**nx generate @nrwl/angular:app menu** (routing TRUE)

Setup Module Federation:
**ng add @angular-architects/module-federation --project msg-example --port 4200**
**ng add @angular-architects/module-federation --project menu --port 4201**

Run: 💣
**npm run run:all**

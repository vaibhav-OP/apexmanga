<div align="center">
    <img src="packages/client/public/logo.png" height="120"/>
    <h1>
        <a href="https://manganerdy.com">Manganerdy</a>
    </h1>
</div>
<p>Read Manga,Manwha,manhua online free, update fastest, most full, synthesized with high-quality images, with full English translation. all manga update daily.</p>

## Local Development
These instructions should get you set up ready to work on Manganerdy 🙌

### Getting Started
1. Install `nvm` then `node` & `npm`: `brew install nvm && nvm install`
2. Install `watchman`: `brew install watchman`
3. Install dependencies: `npm install`

You can use any IDE or code editing tool for developing on any platform. Use your favorite!

### Environment variables 
Create a `.env` file inside client and server package folder.
#### Client
- `NEXT_PUBLIC_serverURL` Backend url (e.g. http://localhost:8080)
- `NEXT_PUBLIC_serverName` Backend domain name (e.g. localhost)

#### Server
- `mongoURL` - MongoDB url
- `clientURL` - Frontend url (e.g. http://localhost:8080)
- `user_name` - Username for authentication
- `user_passwrd` - Password for authentication

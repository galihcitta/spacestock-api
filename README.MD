## SpaceStock REST API

Im using JSON-Server to create this API for serve data that the spacestock-web (https://github.com/galihcitta/spacestock-web) used.
Default url: http://localhost:3000

## Installation
1. Clone this reposity
2. Installing dependencies using npm

```
npm install
```
3. Run the server using this command
```
npm run json:server
```

4. The server will be running on

```
http://localhost:3000
```

**API Documentation**
#### GET `/apartment`
> returns all of apartment data

#### GET `/apartment/[id]`
> returns single specific apartment

#### GET `/apartment?[key]=[value]`
> return filtered apartment data
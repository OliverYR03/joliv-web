## Paso1: Instalar NodeJS y NPM usando nvm
Instalar node version manager con el siguiente comando

```bash
sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```
Acativar nvm con el siguiente comando:

```bash
. ~/.nvm/nvm.sh
```

usar nvm para instalar la ultima versiòn de Node.js con el siguiente comando:

```bash
nvm install node
```

Testear si node y npm estàn correctamente instalados a travès de la terminal:

```bash
node -v
npm -v
```

## Paso 2: Instalar git y clonar el repositori ode Github
Para instalar git correr el siguiente codigo

```bash
sudo yum update -y
sudo yum install git -y
```

Verificar instalación del git
```bash
git — version
```

Clonar repositorio

```bash
git clone https://github.com/g-susvs/api-zona-de-gol.git
```

Entrar a la carpeta del repositorio
```bash
cd api-zona-de-gol
nano .env
npm install
```
Crear el archivo .env y su configuración
```bash
MONGO_CNN=mongodb+srv://admin:oZsld368BdoJvmLD@mycluster.l8ftf.mongodb.net/zona_de_gol
JWT_SECRET=13415141324
CLOUDINARY_URL=
GOOGLE_CLIENT_ID=642936234405-ajlkds7kbcfe3b8fmd58ql4hub9g0cl6.apps.googleusercontent.com
GOOGLE_SECRET_ID=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

```

Instalar Node
```bash
npm install
```

## Paso3: Correr la aplicación

```bash
npm start
```


# apk-RN5

Para comenzar con el proyecto, es importante ejecutar los siguientes comandos y seguir los pasos:

1. Instalación del CLI de expo
```bash
npm install -g expo-cli
```

2. Crea un nuevo proyecto
```bash
npx expo init hello-world-app
```

3. Seleccionamos la plantilla "Blank (TypeScript)"

4. Creamos App.tsx en el proyecto y escribimos un texto que diga 'HELLO WORLD'

5. Probamos la aplicacion:
```bash
cd hello-world-app
npm start
```

6. Iniciamos sesion en Expo con
```bash
eas login
```
7. Una vez hecho eso, creamos el apk
```bash
eas build -p android --profile preview
```

Luego se nos proporcionara por consola un link como este para descargar el Apk:
https://expo.dev/accounts/rodrigo343/projects/hello-world-app/builds/4855fcad-46c4-49ef-ae3d-22ec07d92f17






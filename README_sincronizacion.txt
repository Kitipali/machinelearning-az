
# Guía rápida para mantener sincronizado el repositorio

Este repositorio está conectado a:
- **origin** → Tu fork en GitHub (https://github.com/Kitipali/machinelearning-az)
- **upstream** → El repositorio original de Joanby (https://github.com/joanby/machinelearning-az)

## 1. Verificar los remotos
```bash
git remote -v
```

Debes ver algo así:
```
origin   https://github.com/Kitipali/machinelearning-az.git (fetch)
origin   https://github.com/Kitipali/machinelearning-az.git (push)
upstream https://github.com/joanby/machinelearning-az.git (fetch)
upstream https://github.com/joanby/machinelearning-az.git (push)
```

## 2. Traer los cambios del repositorio original (upstream)
```bash
git pull upstream master
```

## 3. Resolver posibles conflictos
Si hay conflictos, Git te los mostrará y deberás resolverlos manualmente,
luego ejecutar:
```bash
git add .
git commit
```

## 4. Subir los cambios a tu fork (origin)
```bash
git push origin master
```

## 5. Mantener siempre la carpeta al día
Repite el flujo cuando quieras traer las últimas actualizaciones de Joanby
y mantener tu fork sincronizado.
